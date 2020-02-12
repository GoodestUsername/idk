Q1
You can autoclose an issue from a pull request by using the word closes #(number of issue) in commit message
Q2
You can autoclose more than one issue from PR by using commas, for example in commit message "this closes #1, closes #2, closes#3" will close issue #1, issue #2, issue #3
Q3
Example of using map.
named function declaration
var numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
var squaredNumbers = numbers.map(squareNumbers)
function squareNumbers(num) {
    return Math.pow(num, 2);
  }
document.getElementById("movieHistoryCard").innerHTML = "Squares of numbers 1-10 are:" + squaredNumbers;

anonymous function
var secondTetration = numbers.map(function(num) {
    return Math.pow(num, num)
})
document.getElementById("movieHistoryCar").innerHTML = "Second tetration of previous numbers are: " + secondTetration;

the transformation function we discussed in class is sometimes referred to as a callback function because it is passed into another
function as a variable, and the common name for the function passed in is called the callback function.
