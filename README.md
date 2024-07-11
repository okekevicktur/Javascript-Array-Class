
Classwork: JavaScript Arrays and Objects

Part 1: Arrays

Task:

Test your JavaScript knowledge of arrays by completing the following tasks:

*1. Create a JavaScript array fruits*

Create a JavaScript array called fruits with the following elements:

- apple
- banana
- orange
- grape
- strawberry

Example:

const fruits = ['apple', 'banana', 'orange', 'grape', 'strawberry'];

*2. Write a function getFruitIndex*

Write a function called getFruitIndex that takes a fruit name as an argument and returns the index of that fruit in the fruits array.

Example:

function getFruitIndex(fruitName) {
  return fruits.indexOf(fruitName);
}

*3. Write a function addFruit*

Write a function called addFruit that takes a new fruit name as an argument and adds it to the end of the fruits array.

Example:

function addFruit(newFruit) {
  fruits.push(newFruit);
}

*4. Write a function removeFruit*

Write a function called removeFruit that takes a fruit name as an argument and removes it from the fruits array.

Example:

function removeFruit(fruitName) {
  const index = getFruitIndex(fruitName);
  if (index !== -1) {
    fruits.splice(index, 1);
  }
}

Note: Use the getFruitIndex function to get the index of the fruit to be removed.

Testing:

Test your functions with different inputs to ensure they are working correctly.

Example:

console.log(getFruitIndex('apple')); // Output: 0
addFruit('watermelon');
console.log(fruits); // Output: ['apple', 'banana', 'orange', 'grape', 'strawberry', 'watermelon']
removeFruit('banana');
console.log(fruits); // Output: ['apple', 'orange', 'grape', 'strawberry', 'watermelon']

Good luck!
