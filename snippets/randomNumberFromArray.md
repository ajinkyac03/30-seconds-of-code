---
title: Random number from an array
tags: array,random,math
expertise: intermediate
firstSeen: 2022-09-05T17:17:19+05:30
---

Generates a random number from the input array.

- Use `Math.random()` to generate a random number and map it in the array indices range.
- Use `Math.floor()` to make it an integer.

```js
const randomNumberFromArray = arr => arr[Math.floor(Math.random() * arr.length)];
```

```js
randomNumberFromArray([ 1, 3, 5, 7, 9 ]); // 3
```
