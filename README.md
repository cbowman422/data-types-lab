
#Data Type Labs

##Set Up

- Because this will be submitted through a GitHub pull request, fork the sample repository to create your own repository copy.
- Clone the forked repository into your local machine using `$ git clone` in the terminal, remember that this will create a NEW folder with the repository's name that you can then cd into.
- Create 2 new files, an `index.html` and add a script `main.js`.
- Import this JavaScript file in your HTML templates’s head tag: `<script src='main.js' defer></script>`
- Copy the following prompt into your `main.js` file, add your solution and then continue to the next prompt.
- Test your solution by logging your variables through the console - `console.log(Variables)` and running `$ node main.js` in the terminal.



/*
 * Prompt 1:
 *
 * Set the variable simpleMath to a number. In the 
 * console.log() multiply that variable by a new number. Do this for 
 * division, addition, subtraction and "division remainder" while using 
 * seperate lines for each.
 */

let simpleMath;

/*  // Example Answer => 
let simpleMath = 101;
console.log(simpleMath*100);
*/



/*
 * Prompt 2:
 *
 * Declare 3 variables using the variable names numberType, 
 * booleanType, and stringType. Set each variable to values 
 * with the respective data type (number, boolean, and string). Use 
 * typeof in your console.log() to double check your solutions.
 */



/*
 * Prompt 3:
 *
 * Take the following given variables containing string values, and using the 
 * + operator combine 3 unique words. String concatenation simply means to 
 * add one or more strings to another string and the + operator is a fast
 * method.
 */

let valR = "r";
let valE = "e";
let valA = "a";
let valD = "d";



/*
 * Prompt 4:
 *
 * With the following given variables containing number values, and using the 
 * + operator, return all of the variables together.
 */

let num0 = 0;
let num1 = 1;
let num2 = 2;
let num3 = 3;



/*
 * Prompt 5:
 *
 * Define variable favAdjective and assign it a string of your favorite
 * adjective. Define variable favFood and assign it a string of your
 * favorite food. Then define variable hackerName and assign a string with 
 * your hacker name and an introduction using string interpolation. Your hacker
 * name should be the combination of your favorite adjective and your
 * favorite food. String interpolation allows you to combine strings using
 * template literals, which can make your code easier to read.
 */

let favAdjective;
let favFood;
let hackerName;

/*  // Example Answer => 
  console.log(hackerName);
  "Hello my hacker name is smooth quesadilla"
*/



/*
 * Prompt 6:
 *
 * Write solutions to the following sub-prompts. The first one is done for you.
 */
 
//  A) A strict equal (===) statement that is true.
//  B) A loose-equal (==) statement that is true.
//  C) A less than (<) statement that is false.
//  D) A greater than (>) statement that is false.
//  E) A less than or equal (<=) that is true.
//  F) A greater than or equal (>=) that is false.
//  G) A strict unequal (!==) to create a statement that is true.
 
let comparison1 = "strict" === "strict";
let comparison2;
let comparison3;
let comparison4;
let comparison5;
let comparison6;
let comparison7;

//console.log(comparison1)



/*
 * Prompt 7:
 *
 * Given the variables, replace the -- in each sub-prompt so that the 
 * statement evaluates to true. The first one is done for you.
 */

let a = 7;
let b = 9;
let c = 11;
let d = 13;
let e = "fifteen";

// b -- a;
let operators1 = a == b;

// c -- d;
let operators2;

// "ten" -- "twelve";
let operators3;

// d -- c -- b;
let operators4;

// a -- b -- b;
let operators5;

// e -- "sixteen";
let operators6;

// 1 -- "one";
let operators7;



/*
 * Prompt 8:
 *
 * Arrange the following variables so that the ternary values are in 
 * ascending order.
 */

let tern1 = true? 7:6;
let tern2 = "false"? 3:9;
let tern3 = null? 1:2;
let tern4 = 5? 6:7;
let tern5 = false? 7:9;
let tern6 = "string" ? 1:8;



/*
 * Prompt 9:
 *
 * Retrieve "Nemo" from each of the following arrays.
 */

const array1 = ["Darla", "Nemo", "Bruce", "Chum"];
const array2 = [
  ["Bruce", "Chum", "Darla"],
  ["Chum", "Nemo", "Bruce"],
  ["Darla", "Bruce", "Chum"],
];
const array3 = [
  ["Chum", ["Darla", "Bruce"]],
  ["Darla", ["Bruce", ["Nemo"], "Chum"]],
];
const array4 = [
  ["Bruce", "Darla"],
  ["Darla", ["Bruce", ["Darla"], "Chum"], [["Bruce"]]],[["Nemo"]],["Darla"],
];

let retrieve1 = array1[1];
let retrieve2 = array2;
let retrieve3 = array3;
let retrieve4 = array4;



/*
 * Prompt 10:
 *
 * Use the length property, of an array, to get the length and the last
 * value of the following array.
 */

const array5 = [1,3,5,23,76,4,79,56,27,2,6];



/*
 * Prompt 11:
 *
 * Use the arrays to answer the following sub-prompts.
 */

const tyrannosaurus = ["Tyrannosaurus", 12, "land"];
const pterodactyl = ["Pterodactyl", 18, "air"];
const theropods = ["Theropoda", 8, "land"];

// The Tyrannosaurus feels jelous about being 12 feet tall, while
// the Pterodactyl is 18. The Tyrannosaurus stands on their tip toes now,
// change 12 to 13 to reflect the difference.

// Change tyrannosaurus name from "Tyrannosaurus" to "Rex".

// The Pterodactyl notices the Tyrannosaurus and decides to stop traveling
// by air to show the Tyrannosaurus they are still 18 feet tell. Remove
// air from the pterodactyl array and replace it with "land".

// Remove "land" from theropods array and add "water".
