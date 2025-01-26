INTRODUCTION :

This is the Project which creates a Scientific calculator which helps you to make calculations in math in a very easy manner. It is user-friendly as well as a faster calculator You can use this calculator 
not only for general use but also for your studies too. The logic used to create this project was not too difficult One who has a basic understanding of JavaScript and familiar with JS Functions concepts 
can understand in an easy manner. You can customize this project’s animation as well as logic as per requirement.
It’s one of the major projects you can use for your personal use as well as to present in your college.

EXPLAINATION :

This project consists of 3 web stacks that are HTML5, CSS3, and JavaScript(ES6). The role of JavaScript plays a very essential role for the logic implied in the code of this code. All the onclick events 
and conditions  are managed as per the user’s use by JavaScript Logic. So let us take a look at how the Logic is built behind the code of this project:
First of all, we have declared 3 constant variables that are const calculator , const display , const buttons these are used later in the code to access the elements in the HTML document by the querySelector
methods.

Let us discuss the work of these 3 constants one by one :

CONST CALCULATOR :

In this constant variable we have written document.querySelector(“#calculator”); This code has important logic to selects the HTML element with the class display inside the calculator element and assigns it to 
the display constant variable.

CONST DISPLAY :

The second constant we have declared is const display .
We have declared it with calculator.querySelector(“.display”); which the HTML element with the class display inside the calculator element and assigns it to the display constant variable.
This is the code which help user to enter the numbers in calculator.

CONST BUTTONS :

The button we have created in the calculator are the part of this code that is calculator.querySelectorAll(“button”);  It is declared to slect all the buttons elements inside of calculator elements and assign 
them to the buttons constant variables

So these are the 3 constants we have declared in the code

Now we discuss the functions of this codes

First function we have created Is buttons.forEach(button => { … });
This is created t use forEach method to loop from each button element in the button array
For each button, an event listener is formed using the method addEventListener..
whenever the button is clicked. The event listener access the click event and executes the anonymous function defined inside it.

The second function we have made is if (value === “clear”) { … }  this function has the ability to invoke as per the conditions given in the if statements as per the on click events.
If we click the button which has ‘clear’ then this code sets the text to ‘zero’
We have created some functions under the condition as per the click events & user inputs from that here is a function named (value === “backspace”) { … }
This function is created to remove the last character from the text content of the display element If and only if the clicked button has a value of “backspace”,

Another conditional function is (value === “=”) { … }:
When we click the button which has a value of “=” then this code executes the expression represented by the text content of the display element and sets the result as the text content of the display element.

The function (value === “+/-“) { … } has also the condition of invoking this function executes its code if the user clicks the button of ‘+ or –‘
if the text content of the display element starts with a “-“ the block of this function’s code removes it from display element
And from all of these conditional functions if any function does not satisfy any conditions the last block of code executes its code.
It sets the text content of the display element to the value of the clicked button.
the text content is replaced by the value of the clicked button If the text content of the display element was “0”
and the value of the clicked button is concatenated to the end of the text content. If the text content of the display element wasn’t “0”.
