# JavaScript-Q4
Write a JavaScript function that takes a number as a parameter and throws a custom 'Error' if the number is negative.

function validate_Positive_Number(n) {
  if (n < 0) {
    throw new Error('Error: Negative numbers are not allowed.');
  }
  return n;
}

console.log(validate_Positive_Number(3));
console.log(validate_Positive_Number(-5));


**Sample Output:**

3
"error"
"Error: Error: Negative numbers are not allowed.
