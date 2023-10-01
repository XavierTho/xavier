---
layout: game
title: JavaScript Playground
description: where tests are done
type: tangibles
courses: { week: {week: 4} }
---




<!-- Playground -->
<script>
  //Backslash Stuff
  const backSlash = "First\nSecondLine\t\\Second\nThird";
  console.log(backSlash);


  // Concatenation
  let coding = "Hello " + "World. "
  coding += "Coding is Fun! "
  coding += "Javascript > Python. "
  coding += "I'm " + person
  console.log(coding);

  // Length
  console.log(person.length);

  //Bracket Notation
  const firstName = "John";
  const firstLetter = firstName[0];
  console.log(firstLetter);

</script>



<!-- Arrays -->
<script>

  // Simple Arrays //

  //Data for a sandwich
  const sandwich = ["ham", "cheese", "bread"];
  console.log(sandwich)

  //Data for Xavier (Name and Age)
  const name = ["Xavier", 14];
  console.log(name)


  // Nested Arrays //

  //Two Arrays within an Array (Colorado & CSU Arrays within the Teams Array)
  const teams = [["Colorado", 43], ["CSU", 35]];
  console.log(teams)

  //Better way of formatting arrays by breaking each separate array into their own line
  const hobbits = [
    ["Frodo", "Baggins", 30], 
    ["Bilbo", "Baggins", 100]
  ]
  console.log(hobbits)


 // Array Data with Indexes //
  
  //Access Array Data with Indexes
  const tens = [10, 20, 30, 40, 50, 60, 70, 80, 90, 100];
  const ten = tens[0]
  console.log(tens[0]); //Output first value in array (10)
  console.log(ten); //Can also just call upon the variable with the value of tens[0] stored
 
  //Modify Array Dat with Indexes
  const twenties = [0, 40, 60, 80, 100];
  twenties[0] = 20; //Change first value in array (0) to 20
  console.log(twenties);

  //Access Multi-Dimensional Arrays With Indexes
  const states = [
    ["California", 1850],
    ["Texas", 1845],
    ["New York", 1788],
    ["Florida", 1845],
    [["Weird", 2023], "Hi!"]
  ];

  const subarray = states[2]; //Third Array within the States Array (New York)
  console.log(subarray);
  const nestedSubarray = states[4][0]; //First Array within the 5th Array ("Weird", 2023)
  console.log(nestedSubarray);
  const element = states[4][0][1]; // 2nd element within the first array of the 5th array  (2023)
  console.log(element);

  //Appending Arrays with push
   const alphabet = ["a","b","c","d"];
   alphabet.push("e","f","g","h"); //Add e, f, g, & h to the alphabet array
   console.log(alphabet)
  
   const numbers = [1,2,3];
   numbers.push([100,200,300]); //Add an array within the numbers array
   console.log(numbers)
   

 let x = 0;
 while(x < 100) {
  console.log("The number is " + x);
  x += 1;
 }

// Simplifed Version
 for (x = 0; x < 100; x++) {
    console.log("The number is " + x);
 }

</script>