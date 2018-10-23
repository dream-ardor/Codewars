**INSTRUCTIONS**: Check to see if a string has the same amount of 'x's and 'o's. The method must return a boolean and be case insensitive. The string can contain any char.

**MY CODE**: 
```javascript
function XO(a) {
	same = a.toLowerCase();
	var b = 0;
	var c = 0;
	for (var d = 0; d < same.length; d++)
		if ("x" === same[d]) b++;
		else if ("o" === same[d]) c++;
	return b === c;
}
```
