## Is n divisible by x and y?

Instructions:

Create a function isDivisible(n, x, y) that checks if a number n is divisible by two numbers x AND y. All inputs are positive, non-zero digits.

### My Code :memo:
```js
const isDivisible = (n, x, y) => n % x ===0  && n %y===0 ? true : false;
```
