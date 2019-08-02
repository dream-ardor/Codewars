## Automorphic Number

A number is called Automorphic number if and only if its square ends in the same digits as the number itself.

Given a number, determine if it is Automorphic or not .

```js
//25 squared is 625, so it is automorphic
```

### :notebook:My Code
```js
const automorphic = n => Math.pow(n,2).toString().endsWith(n) ? 'Automorphic' : 'Not!!';

```
