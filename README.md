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

```javascript
let x = [];

console.log(x);
console.log(x.length);
console.log(typeof x);

let z = ['bat', 'ball', 'car'];

console.log(z);
console.log(z.length);
console.log(typeof z);

console.log(z[0]);
console.log(z[1]);
console.log(z[2]);
```

```javascript
let arr = ["bat", "ball", "car", "bike", "laptop", "gun", "music"];

for (let i = 0; i < arr.length; i++) {
  console.log(`Array position ${i} = ${arr[i]}`);
}
```

```javascript
let arr = ["bat", "ball", "car", "bike", "laptop", "gun", "music"];

arr.forEach((value, index) => {
  console.log(`${index} have ${value}`);
});

arr.forEach((value) => {
  console.log(`${value}`);
});
```

```javascript
let x = [];

x.push("bat");
x.push("ball");
x.push("car");
x.push("book");
x.push("food");

console.log(x);

let num = [];

for (let i = 1; i <= 100; i++) {
  num.push(i);
}

console.log(num);
```

```javascript
//LIFO

let x = [];

x.push("bat");
x.push("ball");
x.push("car");
x.push("book");
x.push("food");

console.log(x);

x.pop();

console.log(x);

x.pop();

console.log(x);
```

```javascript
let arrx = ["bat", "ball", "book"];

console.log(arrx);

delete(arrx[1]);

console.log(arrx);

arrx[1] = "car";

console.log(arrx);
```

```javascript
let arrx = ["bat", "ball", "book"];

delete(arrx[1]);

console.log(arrx);

let arrx2 = [];
arrx.forEach((value) => {
  if (value) {
    arrx2.push(value);
  }
});

console.log(arrx2);
```

```javascript
let x = ["hello", "user", "Sayan", "!"];

console.log(x);

let str = x.join(" ");

console.log(str);

let str2 = x.join("-");

console.log(str2);
```

```javascript
var yourName = "Amit Kumar Srivastav";

console.log(yourName);

let arr = yourName.split(" ");

console.log(arr);

console.log(typeof yourName);
console.log(typeof arr);

console.log(yourName.length);
console.log(arr.length);
```

```js
function x1(para) {
  let x = 10;
  if (para == 25) {
    let x = 25;
    console.log(x);
  }
  console.log(x);
}

x1(25);
```

