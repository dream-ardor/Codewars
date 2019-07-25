## Sum of a Beach

Beaches are filled with sand, water, fish, and sun. Given a string, calculate how many times the words "Sand", "Water", "Fish", and "Sun" appear without overlapping (regardless of the case).
### :shell:My Code
```js
const sumOfABeach = beach => (beach.match(/water|sand|fish|sun/gi)||[]).length;
```
