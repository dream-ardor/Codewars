## Math Issues

Oh no, our Math object was "accidently" reset. Can you re-implement some of those functions? We can assure, that only non-negative numbers are passed as arguments. So you don't have to consider things like undefined, null, NaN, negative numbers, strings and so on.

Here is a list of functions, we need:
```js
Math.round()
Math.ceil()
Math.floor()
```
### :cd:My Code
```js
Math.round = function(number) {
  return Math.floor(number + 0.5); 
};

Math.ceil = function(number) {
  let a = Math.floor(number); 
  return a === number? number : a + 1;
};

Math.floor = function(number) {
  return ~~number; 
};
```
