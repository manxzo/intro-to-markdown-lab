# Introduction to Arrays

## Arrays

### 1. What is an Array?

An array is a list of items stored in one variable. Each item has a position, called an index, that starts from 0.

**Example**:

1. Create an array: `const fruits = ["Apple", "Banana", "Cherry"]`
2. Access the first item: `fruits[0]` gives "Apple".
3. To access other indexes: `fruits[2]` gives "Cherry".

> - Items in an array are in order and can be accessed by their index.
> - Arrays can store numbers, strings, or other types.
> - Arrays are useful for lists of data.

### 2. Looping Through an Array

There are many methods to loop through an array, but lets talk about two basic methods. Given the following array:

```js
const Array = [0, 1, 2, 3, 4];
```

1. `for` method

**Example**:

```js
for (let i = 0; i < Array.length; i++) {
  console.log(Array[i]);
}
/*
This would log
0
1
2
3
4
*/
```

2. `forEach` method

**Example**:

```js
Array.forEach((element) => {
  console.log(element);
});
/*
This would log
0
1
2
3
4
*/
```

### 3. Array Methods

There are so many different ways to modify and use the data in an array. Here are some simple examples of how we can modify them. We will use the array above as an example.

**Example**:

1. `Array.push` method

```js
Array.push(5); ///Adds 5 to the end
console.log(Array);
/*This would log
[0,1,2,3,4,5]*/
```

This method adds an element to the end of the array.

**Note**: This method along with `.pop` modify the original array.

2. `Array.pop` method

```js
Array.pop(); ///Removes the 5 we added earlier
console.log(Array);
/*This would log
[0,1,2,3,4]*/
```

3. `Array.slice` method

```js
const slicedArray = Array.slice(0, 2);
console.log(slicedArray);
/*This would log
[0,1]*/
```

These are just some examples of what we can do with arrays in JavaScript.

> _For more info about coding and arrays be sure to check out [Playcode](https://playcode.io/javascript/methods)!_
