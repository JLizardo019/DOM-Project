# Instructions

1. Read over the index.html and style.css files to understand how they are organized.
2. Using only the script.js, your job is write code that will only select the third button on the webpage and add a secret message on the page when it is clicked. You are not allowed to change the index.html or the style.css.
3. Within the script.js, define a constant variable called mybutton.
4. Use the function querySelectorAll() to select for the third button on your webpage using the DOM (Remember querySelectorAll returns an array!). Save the result in your variable mybutton.
5. Define a new function called onClick. <br>Within your function, use the function getElementbyId() to select for the secret p html tag.<br>
Change the inner html of your p tag to the string "You are amoung the selected few. Congrats!".
6. Add an event listener to your button that has a callback to your function onClick(). 