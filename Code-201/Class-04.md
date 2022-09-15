## Structuring the web with HTML

- A basic link is created by wrapping the text or other content, see Block level links, inside an <a> element and using the href attribute, also known as a Hypertext Reference, or target, that contains the web address.

-  the href attribute, also known as a Hypertext Reference, or target, that contains the web address.

- Making sure links on our pages are accessible to all readers:
  -  Don't repeat the URL as part of the link text — URLs look ugly, and sound even uglier when a screen reader reads them out letter by letter.
  - Don't say "link" or "links to" in the link text — it's just noise. Screen readers tell people there's a link. Visual users will also know there's a link, because links are generally styled in a different color and underlined (this convention generally shouldn't be broken, as users are used to it).
  - Keep your link text as short as possible — this is helpful because screen readers need to interpret the entire link text.
  - Minimize instances where multiple copies of the same text are linked to different places. This can cause problems for screen reader users, if there's a list of links out of context that are labeled "click here", "click here", "click here".

### CSS Layout

- Normal flow if you haven't applied any CSS to change the way they behave. And, as we began to discover, you can change how elements behave either by adjusting their position in normal flow or by removing them from it altogether.

-  Ablock level element's content fills the available inline space of the parent element containing it and grows along the block dimension to accommodate its content. The size of Inline elements is just the size of their content. You can't set width or height on inline elements — they just sit inside the content of block level elements. If you want to control the size of an inline element in this manner, you need to set it to behave like a block level element (e.g., with display: block; or display: inline-block;, which mixes characteristics from both).

- Positioning allows you to take elements out of normal document flow and make them behave differently, for example, by sitting on top of one another or by always remaining in the same place inside the browser viewport.

- Static positioning is the default that every element gets. It just means "put the element into its normal position in the document flow — nothing special to see here.

- Relative positioning is the first position type we'll take a look at. This is very similar to static positioning, except that once the positioned element has taken its place in the normal flow, you can then modify its final position, including making it overlap other elements on the page.

- fixed positioning usually fixes an element in place relative to the visible portion of the viewport.

- Absolute positioning fixes an element in place relative to its nearest positioned ancestor (the initial containing block if there isn't one), fixed positioning usually fixes an element in place relative to the visible portion of the viewport.

## Functions — reusable blocks of code

- A function definition (also called a function declaration, or function statement) consists of the function keyword, followed by:

    The name of the function.
    A list of parameters to the function, enclosed in parentheses and separated by commas.
    The JavaScript statements that define the function, enclosed in curly brackets, { /* … */ }.

- Function Invocation is used to executes the function code and it is common to use the term “call a function” instead of “invoke a function”. The code inside a function is executed when the function is invoked.

- Parameters are essentially passed to functions by value — so if the code within the body of a function assigns a completely new value to a parameter that was passed to the function, the change is not reflected globally or in the code which called that function.

- Arguments object, you can call a function with more arguments than it is formally declared to accept. This is often useful if you don't know in advance how many arguments will be passed to the function. 

## 6 Reasons for Pair Programming

1. Greater efficiency
- This allows a developer to have the best quality code. Pair reviews will allow then to check out the functionality of eachothers code.

2. Work environment readiness
- This allows the Developer to get used to collabporating with others in a team setting.

## Things I want to know more about

- I want to learn more about using funtions and improving code quality.