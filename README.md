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

```js
let obj1 = {
  item1: "bat",
  item2: "ball",
  item3: "car",
  item4: "plane"
};

console.log(obj1);
console.log(Object.keys(obj1));
console.log(Object.values(obj1));
console.log(Object.keys(obj1).length);
console.log(Object.values(obj1).length);

if (Object.keys(obj1).length > 0) {
  console.log("Yes, is not empty");
} else {
  console.log("Yes, is empty");
}

if (obj1.item20) {
  console.log("Yes, item3 is avaliable in the object");
} else {
  console.log("No, item3 is no avaliable in the object");
}

if (obj1.hasOwnProperty('item20')) {
    console.log("Yes, item2 is avaliable in the object");
} else {
  console.log("NO, item2 is not avaliable in the object");
}

console.log(obj1);

delete obj1.item2;

console.log(obj1);

if (obj1.hasOwnProperty('item3')) {
    delete obj1.item3;
} else {
  console.log("item3 not found in the object set");
}

console.log(obj1);
```

```js

// single object
let obj1 = {
  item1: "bat",
  item2: "ball",
  item3: "car",
  item4: "plane"
};

// array of objects
let obj2 = [
  {
    "postId": 1,
    "id": 1,
    "name": "id labore ex et quam laborum",
    "email": "Eliseo@gardner.biz",
    "body": "laudantium enim quasi est quidem magnam voluptate ipsam eos\ntempora quo necessitatibus\ndolor quam autem quasi\nreiciendis et nam sapiente accusantium"
  },
  {
    "postId": 1,
    "id": 2,
    "name": "quo vero reiciendis velit similique earum",
    "email": "Jayne_Kuhic@sydney.com",
    "body": "est natus enim nihil est dolore omnis voluptatem numquam\net omnis occaecati quod ullam at\nvoluptatem error expedita pariatur\nnihil sint nostrum voluptatem reiciendis et"
  },
  {
    "postId": 1,
    "id": 3,
    "name": "odio adipisci rerum aut animi",
    "email": "Nikita@garfield.biz",
    "body": "quia molestiae reprehenderit quasi aspernatur\naut expedita occaecati aliquam eveniet laudantium\nomnis quibusdam delectus saepe quia accusamus maiores nam est\ncum et ducimus et vero voluptates excepturi deleniti ratione"
  },
  {
    "postId": 1,
    "id": 4,
    "name": "alias odio sit",
    "email": "Lew@alysha.tv",
    "body": "non et atque\noccaecati deserunt quas accusantium unde odit nobis qui voluptatem\nquia voluptas consequuntur itaque dolor\net qui rerum deleniti ut occaecati"
  },
  {
    "postId": 1,
    "id": 5,
    "name": "vero eaque aliquid doloribus et culpa",
    "email": "Hayden@althea.biz",
    "body": "harum non quasi et ratione\ntempore iure ex voluptates in ratione\nharum architecto fugit inventore cupiditate\nvoluptates magni quo et"
  }
];


console.log(obj2.length);

//by using for loop - print array of objects
for (let i = 0; i < obj2.length; i++) {
  console.log(`ID: ${obj2[i].id} -- Email: ${obj2[i].email}`);
}

//by using map - print array of objects
obj2.map((singleObj) => { console.log(`ID: ${singleObj.id} | Email: ${singleObj.email} | Name: ${singleObj.name}`)});
```

```js
obj2.filter((singleObj, singleObjPosition) => {
  console.log(`Array position ${singleObjPosition}`);
  console.log(singleObj.email);
});

obj2.map((singleObj, singleObjPosition) => {
  console.log(`Array position ${singleObjPosition}`);
  console.log(singleObj.id);
});
```

```js
const filterUsers = obj2.map((obj, pos) => {
  if (obj.id == 5 || obj.id == 2) {
    console.log("id = " + obj.id)
    console.log("name = " + obj.name)
    console.log("email = " + obj.email);
    console.log("==============================");
  }
});
```

```js
const users = obj2.filter((obj) => {
  return (obj.id == 2 || obj.id == 5) ? obj : null;
});
console.log(users);

const users = obj2.filter((obj) => (obj.id == 2 || obj.id == 5) ? obj : null );
console.log(users);
```

