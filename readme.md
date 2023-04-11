*Learning positions in css.*


step 4-
FontAwesome is a library of SVG-powered icons, many of which are freely available to use. You will be using some of these icons in this project, so you will need to link the external stylesheet to your HTML.

Add a link element with a rel of stylesheet and an href of https://use.fontawesome.com/releases/v5.8.2/css/all.css.

step 9-
Typically, HTML is rendered in a top-down manner. Elements at the top of the code are positioned at the top of the page. However, many times you may want to move the elements to different positions. You can do this with the position property.

Set the position property for the #back-wall element to absolute. An absolute position takes the element out of that top-down document flow and allows you to adjust it relative to its container.

When an element is manually positioned, you can shift its layout with top, left, right, and bottom. Set the #back-wall element to have a top value of 0, and a left value of 0.

Step 10
The z-index property is used to create "layers" for your HTML elements. If you are familiar with image editing tools, you may have worked with layers before. This is a similar concept.

Elements with a higher z-index value will appear to be layered on top of elements with a lower z-index value. This can be combined with the positioning in the previous lesson to create unique effects.

Since the back-wall element will need to appear "behind" the other elements you will be creating, give the back-wall element a z-index of -1.

Step 37
Time to use some FontAwesome icons.

The i element is used for idiomatic text, or text that is separate from the "normal" text content. This could be for italic text, such as scientific terms, or for icons like those provided by FontAwesome.

Within your #white-paper element, add four i elements. Give them all a class value of fas fa-music.

This special class is how FontAwesome determines which icon to load. fas indicates the category of icons (FontAwesome Solid, here), while fa-music selects the specific icon.
