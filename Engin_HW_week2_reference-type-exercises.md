##Exercise Reference Exercises

##Complete this code

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

