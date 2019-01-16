# Kelvin-Weather
In this example of code I created, I was tasking with changing the temperature from kelvin to celusius and finding the fahrenheit.

app.js

//current temperature in kelvin
const kelvin = 100; 
//Converting kelvin to celsius
const celsius = kelvin - 273;
//conver celsius to fahrenheit
let fahrenheit = celsius * (9/5) + 32;
//round down fahrenheit variable.
fahrenheit = Math.floor(fahrenheit);
console.log(`The temperature ${fahrenheit} degrees fahrenheit.`);
