```javascript
/**

JS Entry point:

var & let & const

**/


/*
we can not declared this variable more than 1 time
But we can overwrite the value of the variable
*/
let x = 25;
x = 100;
/*
the variable should be constant
we can not declared this variable more than 1 time
we can not overwrite the value of the variable
*/
const a = 45; 

/*
We can declared it more than 1 time
Also we can overwrite the value as well
*/
var z = 30;
var z = 56;
z = 90;

console.log(z);
```

```javascript
function fun1() {
  return 'Hello, User';
}

console.log(fun1());

function fun2(para1){
  return "Ok, your parameter is " + para1;
}

console.log(fun2(12));
console.log(fun2(14));
console.log(fun2(16));
console.log(fun2(22));

function fun3(x, y) {
  return x * y;
}

console.log(fun3(4, 5));

function fun4(amount, time, rate) {
  let x = ((amount * time * rate) / 100).toFixed(2);
  return `Your total intarest is ${x}`;
}

console.log(fun4(100, 5, 7));

```

```javascript
// ES6 == Ecma Script

const fun1 = () => {
  return "Hello User";
}

console.log(fun1());

const fun2 = (p1, p2) => {
  return `Your Multipication is ${p1 * p2}`;
}

console.log(fun2(3, 8));
```

