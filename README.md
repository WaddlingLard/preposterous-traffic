# Web Dev Starter Code

## Overview

This assignment highlights the importance of accessibility. There are many changes that reflect an accessible website and make it usable by all sorts of people. 

Steps to run the website:
1. To get this website running, first download this repository to your local directory.
2. Navigate to where it is located on your computer and then open VSCode.
3. Then, using Live Preview, use the key combination ctrl+shift+p and use the command 'Live Preview: Start Server'.
4. If you want to access the website via a web browser. User the url 'localhost:3000' to view the website.

## Accessibility Lab Answers

Color: Running a Lighthouse test shows that there is a contrast problem between the text in the background making it hard to read.

Semantic HTML:
1. Trying to use the keyboard shows that you cannot access the 'show comments' button.
2. Looking at the semantics, there are a lot of < br > tags is not good practice of HTML structure. These 'font' tags also need to be changed with < header > tags
3. The navigation menu < div > tag can be replaced with a < nav > tag which respects the semantics. That means the CSS will also have to reflect that change.

Images: The images need 'alt' attributes to describe what is happening in the image to improve accessibility.

Audio Player:
1. Provided a transcript next to the audio controls for deaf users.
2. If the browser does not support HTML audio. One way to deal with this is by providing a link to the audio instead.

Forms:
1. Implementing a hidden label allows people with screen readers to understand what the structure is but also not burdening sighted users.
2. Changing the < p > tags to < label > tags helps suffice the unambiguous nature.

Show/Hide Comment Control: To make the button keyboard-accessible, you will need to change the element from a < div > tag to a < button > tag instead. It will now make it tab-accessible and return-usable.

Table: Adding table headers and a caption will make reading the table with a screen reader more accessible.

Other Ideas:
1. For the links on the related section could highlight when the mouse hovers over. That will make it more accessible to give contrast from a static state.
2. Another thing that would help is increasing the font size. I feel in its current state it can be hard to read the text.


## Sources and Credits

- MDN Web Docs: https://developer.mozilla.org
