# Class 02 - Basics of HTML, CSS & JS

### HTML - Introduction to HTML

- HTML is called hyper text markup language 

- It is important to use semantics in our HTML so that the browser knows how to display things correctly.

- There are 6 levels of sub headings in Html {<h1>, <h2>, <h3>, <h4>, <h5>, and <h6>}

- The use for superscript <sup>  and subscript <sub> for marking up items like dates, chemical formulae, and mathematical equations so they have the correct meaning.

- The abbreviation <abbr> ellement is used to wrap around an abbreviation or acronym.

### How CSS is structured

- CSS can be applied to the HTML by:        
    - linking an external stylesheet contains CSS in a separate file with a .css extension.
    - An internal stylesheet resides within an HTML document. You place CSS inside a <style> element contained inside the HTML <head>.
    - Inline styles are CSS declarations that affect a single HTML element, contained within a style attribute

- We avoid using Inline stylesheet because  it is the least efficient implementation of CSS for maintenance. One styling change might require multiple edits within a single web page. Second, inline CSS also mixes (CSS) presentational code with HTML and content, making everything more difficult to read and understand. Separating code and content makes maintenance easier for all who work on the website.

- Properties: These are human-readable identifiers that indicate which stylistic features you want to modify. For example, font-size, width, background-color.

Ex: 
   h2 {
     color: black;
     padding: 5px;
   }

- This represents a CSS declaration that is meant to effect the H2 element.
- It is meant to change the color to black and add a padding size of 5px.
- Properties are the color and padding.

### JavaScript basics
 
- A string is enclose it in single quote mark

- 4 types of Javascript Operators

  - Addition 	Add two numbers together or  combine two strings. 

  + 	6 + 9; 'Hello ' + 'world!';

  - Subtraction, Multiplication, Division 	
  
  These do what you'd expect them to do in basic math. 	-, *, / 	9 - 3; 8 * 2; // multiply in JS is an asterisk 9 / 3;
  - Assignment 	As you've seen already: this assigns a value to a variable. 	= 	let myVariable = 'Bob';

  - Strict equality This performs a test to see if two values are equal. It returns a true/false (Boolean) result. 

- Functions are a way of packaging functionality that you wish to reuse.
  - This can solve a problem such as recording peoples opinions on a particluar problem.

### Making decisions in your code — conditionals

 

    What is the difference between the logical operator && and ||?

-  An if statement checks a condition and if it evaluates to true , then the code block will execute.

- if...else statements do the job of enabling conditional code well, but they are not without their downsides

- 3 different types of comparison operators.
  - === and !== — test if one value is identical to, or not identical to, another.
  - < and > — test if one value is less than or greater than another.
  - <= and >= — test if one value is less than or equal to, or greater than or equal to, another.

-  The difference between the logical operator && and ||
    && — AND; allows you to chain together two or more expressions so that all of them have to individually evaluate to true for the whole expression to return true.
    || — OR; allows you to chain together two or more expressions so that one or more of them have to individually evaluate to true for the whole expression to return true.



## Things I want to know more about