Create a for loop that iterates up to `100` while outputting **"fizz"** at multiples of `3`, **"buzz"** at multiples of `5` and **"fizzbuzz"** at multiples of `3` and `5`.

**Kevin:** I assume if neither fizz or buzz is outputted, the default output is the number.

```javascript
var output;
for (var i = 1; i <= 100; i++) {
  output = '';
  if (i % 3 === 0) {
    output += 'fizz';
  }
  if (i % 5 === 0) {
    output += 'buzz';
  }
  console.log(output || i);
}
```
