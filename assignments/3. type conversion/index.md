1. 🎖 What's the output of the code below
```js
typeof "Joe";
// Answer: "string";
typeof 4;
// Answer: "number"
typeof NaN;
// Answer: "number"
typeof false;
// Answer: "boolean"
typeof function () {};
// Answer: "function"
var phone = 8983700;
typeof phone;
// Answer: "number"
typeof null;
// Answer: "object"
```

2. 🎖 Output of the code below
```js
// Convert num into string
var num = 45;
String(num);
// Answer: "45"
String(321);
// Answer: "321"
String(300 + 23);
// Answer: "323"
String(false);
// Answer: "false"
String(true);
// Answer: "true"
Number("3.18");
// Answer: 3.18
Number(" ");
// Answer: 0
Number("");
// Answer: 0
Number("22 44");
// Answer: NaN
Number(false);
// Answer: 0
Number(true);
// Answer: 1
```

3. 🎖 Output of the following

```js
var x = 10 + "1";
console.log(x);
typeof x;
// Answer: 101, type "string"
```