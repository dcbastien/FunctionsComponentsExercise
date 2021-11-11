# FunctionsComponentsExercise

1a. Create a function component called Ghostbusters that returns the following string "Who you gonna call?"

1b. Below the Ghostbusters function component, use the ReactDOM Render method to render/display the Ghostbusters function component in the div with the id of "root" in the HTML file (HINT: Remember the ReactDOM Render method takes two parameters. Also, you will need to use a DOM selector to select the div with the id of "root". If this is done correctly you should see the Ghostbusters message display in Chrome)

2a. Below the ReactDOM Render method, create another function component called Tagline that returns the following text inside of an h1 element "We're ready to believe you."

2b. Below the Tagline function component, use the ReactDOM Render method again to render/display the Tagline function component in the div with the id of "root" in the HTML file (NOTE: Since only one React component can be rendered/displayed in an HTML element, the message from the Ghostbusters component will be replaced by the message in the Tagline component. You can comment out the first ReactDOM Render method if you would like, but it is not necessary)

3a. Create another function component called Janine that returns the following text inside of two separate h2 elements. First h2 element text: "I've quit better jobs than this.". Second h2 element text: "Ghostbusters, whaddya want?". (HINT: Remember only one parent/top element can be returned from a component)

3b. Below the Janine function component, use the ReactDOM Render method again to render/display the Janine function component in the div with the id of "root" in the HTML file

4a. Create another function component called MassHysteria that returns the following text inside of 3 separate unordered list item elements as well as the final text inside of a paragraph tag (NOTE: Remember you can use the emmet autocomplete to type out/create elements faster than typing them all out)…
First list item element text: "Fire and brimstone coming down from the skies! Rivers and seas boiling!"
Second list item element text: "Forty years of darkness! Earthquakes! Volcanoes!"
Third list item element text: "The dead rising from the grave!"
Paragraph element text: "Human sacrifice! Dogs and cats, living together! Mass hysteria!"

4b. Below the MassHysteria function component, use the ReactDOM Render method again to render/display the MassHysteria function component in the div with the id of "root" in the HTML file

5a. Create a function component called GhostbustersLogo that returns an img (Image) element using the following image: https://cdn.pixabay.com/photo/2016/07/13/18/41/ghostbusters-1515155_1280.jpg (HINT: Remember there is a special way/syntax for writing self closing elements/tags in JSX)

5b. Below the GhostbustersLogo function component, use the ReactDOM Render method again to render/display the GhostbustersLogo function component in the div with the id of "root" in the HTML file

6a. Below the ReactDOM Render method, create another function component called ToolsTalent.

6b. Inside the function component create a const variable called "w" and set the value to the following string: "We".

6c. Below the "w" variable, use the return keyword and parentheses so the function component returns the following text inside of an h1 element as well as an h3 element. However, you need to plug in the "w" variable for each place there is a "We".
h1 element text: "We had the tools."
h3 element text: "We had the talent."

6d. Below the ToolsTalent function component, use the ReactDOM Render method again to render/display the ToolsTalent function component in the div with the id of "root" in the HTML file

7a. Below the ReactDOM Render method, create another function component called GhostbustersAll that returns all of the function components that have been created so far in this exercise

7b. Below the GhostbustersAll function component, use the ReactDOM Render method again to render/display the GhostbustersAll function component in the div with the id of "root" in the HTML file

BONUS…
8a. Below the ReactDOM Render method, create another function component called DiceRoll.

8b. Inside the function component use Math.random to return a random number between 1 and 6 and set it to const variable called "die1"

8c. Below the die1 variable, use Math.random again to return a random number between 1 and 6 and set it to const variable called "die2"

8d. Below the die2 variable, have the DiceRoll function component return an h1 element. Inside the h1 element use a TERNARY that…
Sets the text for the h1 to "SNAKE EYES" if both die1 and die2 are equal to 1 
Or
If either die1 or die2 is NOT equal to 1 sets the text for the h1 to the values for each die like shown in this example: 2 & 5.

8e. Below the DiceRoll function component, use the ReactDOM Render method again to render/display the DiceRoll function component in the div with the id of "root" in the HTML file
