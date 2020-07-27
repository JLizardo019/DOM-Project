# Instructions

1. Read over the index.html and style.css files to understand how they are organized.
2. Using only the script.js, your job is write code that will make the text within the h3 tag change to "Ta Da!" when the button is clicked. You are not allowed to change the index.html or the style.css.
3. Within the script.js, define a constant variable called mybutton.
4. Use the function querySelector() to select for the button on your webpage using the DOM. Save the result in your variable mybutton.
5. Define a new function called onClick. <br>Within your function, use the function getElementbyId() to select for the h3 html tag.<br>
Change the inner html of your h3 to the string "Ta da!".
6. Add an event listener to your button that has a callback to your function onClick(). 