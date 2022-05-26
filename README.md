# JavaScript PROJECT: Testing-Practice
## About
*JavaScript Unit Testing is a method where JavaScript test code is written for a web page or web application module.*

## THE ODIN PROJECT [Link](https://www.theodinproject.com/lessons/node-path-javascript-testing-practice)
### Using ES6 import statements with Jest
By default, the current version of Jest will not recognize ES6 import statements. In order for you to be able to use ES6 modules for this project you may do the following:
1. Install the @babel/preset-env package
```
npm i -D @babel/preset-env
```
2. Create a .babelrc file in the project’s root with the following lines of code:
```
{ "presets": ["@babel/preset-env"] }
```
This will allow you to use import statements. Note that in the Jest docs similar instructions are laid out [here](https://jestjs.io/docs/getting-started#using-babel)
### Assignment
Write tests for the following, and then make the tests pass!

1. A `capitalize` function that takes a string and returns it with the first character capitalized.

2. A `reverseString` function that takes a string and returns it reversed.

3. A `calculator` object that contains functions for the basic operations: `add`, `subtract`, `divide`, and `multiply`. Each of these functions should take two numbers and return the correct calculation.

4. A caesarCipher function that takes a string and returns it with each character “shifted”.<br>

  a. Don’t forget to test wrapping from `z` to `a`.<br>

  b. Don’t forget to test keeping the same case.<br>

  c. Don’t forget to test punctuation!<br>

5. An `analyzeArray` function that takes an array of numbers and returns an object with the following properties:`average`, `min`, `max`, and `length`.


