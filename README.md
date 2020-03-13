# ITEC2838FinalProject
Final Project for Javascript course: Design template for Cinna~Roller
## Motivation
By way of meeting these great people at a group even for small businesses 

## How to Run
Basically most browsers will work

## Code Example
Show a small snippet of the code you are proud of and why.
I'm proud to have pretty much created most of the following because of what I've learned in the javascript course
Insert Code Here
```
var buttons = document.querySelector("image");       
      buttons.addEventListener("click", shopCart, false);
      var clicked = false;
      function shopCart(buttons)
      {
        //add variables for user input?
        var usrNum = prompt("How many would you like? ", "1");
         if(!clicked)
         {
          //expression to process whatever the user inputs and modify the console log to calculate...
           document.getElementById("total").innerHTML = "Total of your request is " + "$" + (usrNum * 4) + '\n' +" Phone number to reach us is: 435-599-0000";        }
```

## Tests
Utilizing the Google Chrome browser with developer tools enabled I was able to test
code. Editor was primarily VS-Code

## Contributors
Myself, book, and some internet searches for tips
