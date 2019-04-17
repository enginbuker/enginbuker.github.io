##Exercise Reference Exercises

###Complete this code

```js
  let value_1 = 5;
  let reference_1 = [1, 2, 3];

  let value_2 = value_1;
  console.assert(value_2 === value_1);

  let reference_2 = reference_1;
  console.assert(reference_2 === reference_1);

  value_2 = 6; // write this line
  console.assert(value_1 !== value_2);  
    
  reference_1[0] = reference_2[0] ; // write this line
  console.assert(reference_1[0] === reference_2[0]);

  // remove the array from memory
  reference_1 = null; // write this line
  reference_2 = reference_1; // write this line
  ````

##Exercise Array Exercises

###Complete the Assertions_1

```js

let a_1 = [10];
let a_2 = a_1;
console.assert(a_1 === a_2);

let b_1 = [11];
let b_2 = [12];
console.assert(b_1 !== b_2);

// ---

a_1.push(3);
a_2.push(3);
console.assert(a_1 === a_2);

b_1.push(5);
b_2.push(5);
console.assert(b_1 !== b_2);
````

##Exercise Array Exercises

###Complete the Assertions_2

```js

let a_1 = [5];
let a_2 = a_1;
console.assert(a_1 === a_2);

let b_1 = [6];
let b_2 = [7];
console.assert(b_1 !== b_2);

// ---

const key = 0;

a_1[key] = 3;
a_2[key] = 3;
console.assert(a_1 === a_2);

b_1[key] = 5;
b_2[key] = 5;
console.assert(b_1 !== b_2);
````

##Exercise Array Exercises

###Fill in the Blanks

```js

let arr_1 = [8,9,5]; // write this line
let arr_2 = [8,9,10]; // write this line
console.assert(arr_1 !== arr_2);
console.assert(arr_1[1] === arr_2[1]);

let key = 0;
console.assert(arr_1[key] === arr_2[key]);

arr_2[2] = 1; // write this line
arr_1[2] = arr_2[2]; // write this line
console.assert(arr_1[arr_2[2]] === arr_2[arr_1[2]]);

let arr_3 = [11,12,13]; // write this line
arr_3[key] = arr_1[0]; // write this line
console.assert(arr_1 !== arr_2);
console.assert(arr_3 !== arr_1);
console.assert(arr_3 !== arr_2);
console.assert(arr_3[key] === arr_1[0]);

let obj_3 = [1,1]
let obj_2 = [1,1]; // write this line
console.assert(obj_3[1] === obj_2[key]);
````

##Object Exercises

###Complete the Assertions_1
```js

let a_1 = {x: 4};
let a_2 = a_1;
console.assert(a_1 === a_2);

let b_1 = {y: 6};
let b_2 = {z: 7};
console.assert(b_1 !== b_2);

// ---

a_1.x = 3;
a_2.x = 3;
console.assert(a_1 === a_2);

b_1.y = 5;
b_2.z = 5;
console.assert(b_1 !== b_2);
````

