# Larger Number Finder

This project contains a set of JavaScript functions to find the largest number among a given set of numbers. The functions are designed to handle different numbers of inputs.

## Functions:

### `larger_5`
This function takes five numbers as input and returns the largest among them.

### `larger_4`
This function takes four numbers as input and returns the largest among them.

### `larger_3`
This function takes three numbers as input and returns the largest among them.

### `larger_2`
This function takes two numbers as input and returns the larger among them.

## Usage:

Each function can be called with the respective number of parameters, and it will return the largest number among them.

Example usage:

```javascript
// Example usage of larger_5 function
larger_5(2, 25, 18, 9, 3); // Logs: "Among the 5, the larger number is: 25"

// Example usage of larger_4 function
larger_4(2, 5, 18, 90); // Logs: "Among the 4, the larger number is: 90"

// Example usage of larger_3 function
larger_3(2, 5, 18); // Logs: "Among the 3, the larger number is: 18"

// Example usage of larger_2 function
var findNum = larger_2(10, 5);
console.log("Among the 2, the larger number is: " + findNum); // Logs: "Among the 2, the larger number is: 10"
