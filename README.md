# pythagoras-theorem
//Javascript which uses the theory of Pythagoras to calculate the length of c.
//
alert("Please only use positive numbers");
var a = prompt("What is the value of a?");
if (a <= 0) {
  alert("Only use a positive number for a");
}
var b = prompt("What is the value of b?");
if (b <= 0) {
  alert("Only use a positive number for b");
}
var c = (Math.sqrt((a * a) + (b * b)));
alert("The value of c is " + c);
