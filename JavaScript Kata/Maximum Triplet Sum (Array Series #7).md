## Maximum Triplet Sum (Array Series #7)

Task

Given an array/list [] of n integers , find maximum triplet sum in the array Without duplications .

Notes :
Array/list size is at least 3 .

Array/list numbers could be a mixture of positives , negatives and zeros .

Repetition of numbers in the array/list could occur , So (duplications are not included when summing).

### :diamond_shape_with_a_dot_inside:My Code
```js
const maxTriSum = numbers => {
let x = numbers.sort((a,b)=> b-a);
return [...new Set(x)].slice(0,3).reduce((a,b)=>a+b);
}
```
