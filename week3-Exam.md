Week 3 Examination

```js
let colors = ["red", "green", "yellow"]; // Colors array
let randomLight = Math.floor(Math.random() * colors.length); // Random number between 0 and 2
let trafficLight = colors[randomLight]; //Assigning randomLight to trafficLight
console.log(trafficLight); //Wanted to see the random color in my console

// My else-if statement
if (trafficLight === "green") {
  console.log("GO!");
} else if (trafficLight === "yellow") {
  console.log("WAIT");
} else {
  console.log("STOP");
}

let age = 2023 - 1988;
let firstName = "Angelica";

console.log(typeof age); //First typeof
console.log(typeof trafficLight); // Second typeof
console.log("Hi, my name is " + firstName + " and I am " + age + " years old."); // console.log with my variables

age = 2024 - 1988; //Overwrote variable
console.log("Hi, my name is " + firstName + " and I am " + age + " years old.");

let dice = Math.floor(Math.random() * 6) + 1; //PLaying around with Math.random
console.log(dice);
````
