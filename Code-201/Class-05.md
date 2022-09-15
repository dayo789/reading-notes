### Images, Color, Text

# HTML Media

- Alt is supposed to be a textual description of the image, for use in situations where the image cannot be seen/displayed or takes a long time to render because of a slow internet connection. 
    - We use alt texts to help impaired users, and is using a screen reader to read the web out to them. 

- The accesibilty of a image can be improved by adding a alt in html to help give a description to image for visual imapaired users.

## Image file type and format guide

- A example of when a figure element is usefeul in a HTML document is when annotatiing images.

- A Gif is a image with animation sequences. A SVG image is a image format ideal for user interface elements, icons, diagrams, etc., that must be drawn accurately at different sizes.

- The best type of image for a screenshot is Lossless WebP or PNG.

## Applying color to HTML elements using CSS

- The color property defines the foreground color of an HTML element's content and the background-color property defines the element's background color. These can be used on just about any element.

- Your friend asks you to give his colorless blog website a touch up. How would you use color to give his blog some character?What should you consider when choosing fonts for an HTML document?
    - I would create a color theme pallet for the website.

    - I would consider the type of font that I want to use in the HTML code and the best to pair it up with CSS.

- What do font-size, font-weight, and font-style do to HTML text elements?
    - font-style: Used to turn italic text on or off. Possible values are as follows (you'll rarely use this, unless you want to turn some italic styling off for some reason):

    normal: Sets the text to the normal font (turns existing italics off).
    italic: Sets the text to use the italic version of the font, if available; if not, it will simulate italics with oblique instead.
    oblique: Sets the text to use a simulated version of an italic font, created by slanting the normal version.

    - font-weight: Sets how bold the text is. This has many values available in case you have many font variants available (such as -light, -normal, -bold, -extrabold, -black, etc.), but realistically you'll rarely use any of them except for normal and bold:
    normal, bold: Normal and bold font weight.
    lighter, bolder: Sets the current element's boldness to be one step lighter or heavier than its parent element's boldness.
    100–900: Numeric boldness values that provide finer grained control than the above keywords, if needed.

    - Font size (set with the font-size property) can take values measured in most of these units (and others, such as percentages); however, the most common units you'll use to size text are:

    px (pixels): The number of pixels high you want the text to be. This is an absolute unit — it results in the same final computed value for the font on the page in pretty much any situation.
    ems: 1 em is equal to the font size set on the parent element of the current element we are styling (more specifically, the width of a capital letter M contained inside the parent element). This can become tricky to work out if you have a lot of nested elements with different font sizes set, but it is doable, as you'll see below. Why bother? It is quite natural once you get used to it, and you can use em to size everything, not just text. You can have an entire website sized using em, which makes maintenance easy.
    rems: These work just like em, except that 1 rem is equal to the font size set on the root element of the document (i.e. <html>), not the parent element. This makes doing the maths to work out your font sizes much easier, although if you want to support really old browsers, you might struggle — rem is not supported in Internet Explorer 8 and below.


- Describe two ways you could add spacing around the characters displayed in an h1 element.

    - The letter-spacing and word-spacing properties allow you to set the spacing between letters and words in your text. You won't use these very often, but might find a use for them to obtain a specific look, or to improve the legibility of a particularly dense font.


## Things I want to know more about

- I want to know more about building a proper website with CSS functions.
