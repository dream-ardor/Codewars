## Array Comparator

You have two arrays in this kata, every array contain only unique elements. Your task is to calcualate number of elements in first array which also are in second array.

### :sa:My Code
```js
const matchArrays = (v,r) => v.filter(x => r.includes(x)).length;
```
