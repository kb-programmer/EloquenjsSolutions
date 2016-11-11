# EloquenjsSolutions
Solutions to exercises from Eloquent JavaScript book

Solution 02:1 Looping Triangle

```javascript

var triangle = "";

for (let x = 0; x < 8; x ++) {
  	triangle += "#";
  	console.log(triangle);
}
```
Solution 02:2 FizzBuzz

```javascript
for (let i = 1; i < 101; i ++) {
  if (i % 3 == 0 && i % 5 == 0) {
    	console.log("FizzBuzz");
  } else if (i % 3 == 0 && i % 5 != 0) {
    console.log("Fizz");
  } else if (i % 3 != 0 && i % 5 == 0) {
    console.log("Buzz"); 
  } else {
  	console.log(i);
  }
}
```

Solution 02:3 Chase Board

```javascript

var size = 8;

var chaseBoard = "";

for (let i = 0; i < size; i++) {
   
  for (let j = 0; j < size; j ++) {
     
    if ((i + j) % 2 == 0) {
		chaseBoard += "#";
    } else {
    	chaseBoard += " ";
    }
  }
  chaseBoard += "\n";
}
console.log(chaseBoard);
```
Minimum
```javascript
function min(num1, num2) {
  return num1 < num2 ? num1 : num2;
}
```

