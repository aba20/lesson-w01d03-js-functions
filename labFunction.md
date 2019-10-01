// define a youRock function that accepts a string argument of a name and returns a string using that name.

// Solution:

const youRock = function(name) {
  return "You Rock " + name + "!";
}
console.log(youRock("Hazim"));
console.log(youRock("Monsour"));
console.log(youRock("Reem"));



// Define a square function that accepts a number argument and returns that number multiplied by itself.

const youRock = function(num) {
  return num * num;
}
console.log(youRock());

// 3. Define a cube function that accepts a number argument and returns that number raised to the third power.

const youRock = function(num) {
  return num * num * num;
}
console.log(youRock());

// 4. Define a toTheFourth function that accepts a number argument and returns that number raised to the fourth power.
const youRock = function(num) {
  return num * num * num * num;
}
console.log(youRock());






// 5:

const calc = function(num1, num2, calculator) {
  

  if (isNaN(num1) || isNaN(num2)) 
    return 'it is not a number';

  if (calculator === "add")
    return num1 + num2;
  if (calculator === "substract")
    return num1 - num2;
  if (calculator === "devide")
    return num1 / num2;
  if (calculator === "multiply")
    return num1 * num2;
  
  else 
    return "calculator only accepts numbers"
}
console.log(calc());


// Lab: FizzBuzz Function


const fizbiz = function(num) {
  if (num % 3 === 0)
    return "Fizz";

  if (num % 5 === 0) 
    return "Buzz";
  if (num % 3 === 0 || num % 5 === 0)
    return "FizzBuzz";
  else
    return num
}

console.log(fizbiz())

// Lab: RainDrop Function

const rainDrop = function(num) {
  if (num % 3 === 0)
    return "Pling";

  if (num % 5 === 0) 
    return "Plang";
  if (num % 7 === 0)
    return "Plong";
  else
    return num.toString()
}

console.log(rainDrop())
