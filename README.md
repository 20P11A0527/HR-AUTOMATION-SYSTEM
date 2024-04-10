//First builtin function
function isEven(num) {
  return num % 2 === 0;
}
console.log(isEven(10));
console.log(isEven(11)); 

//Math functions in javascript
const radius = 5;
const area = Math.PI * Math.pow(radius, 2);
console.log("Area of the circle:", area);

//Number functions in javascript isfinite()
const num1 = 10;
const num2 = 3.14;
const notANumber = "hello";
const infinity = Infinity;
console.log(isFinite(num1)); 
console.log(isFinite(num2)); 
console.log(isFinite(notANumber)); 
console.log(isFinite(infinity));

//parsefloat()
const numberString = "3.14159";
const number = parseFloat(numberString);
console.log("Converted number:", number);

//parseInt()
const invalidString = "123abc";
const number = parseInt(invalidString);
console.log(number);

//String functions in javascript
//AtChar()
const message = "Hello World!";
const firstChar = message.charAt(0); // output:H
const lastChar = message.charAt(message.length - 1); // Output:!

//replace()
const newMessage = message.replace("World", "JavaScript"); // Output: Hello JavaScript!

//toLowerCase()
const lowerMessage = message.toLowerCase(); // Output: hello world!

//toUpperCase()
const upperMessage = message.toUpperCase(); // Output: HELLO WORLD!






