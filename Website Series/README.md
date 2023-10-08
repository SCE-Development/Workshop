# Introduction
During this series we will learn HTML, CSS, and JS.

On day one we will go over elements of html, inline css styling, and setting up your website.

On day two we will go over css files, css classes, transitions and annimations.

On day three we will go over js, dom manipulation, API usage, and events.

In each folder titled "Week 1", "Week 2", "Week 3" you can find the completed demo code for that week. Everything in the demo will only use content from that week. For example, the code in "Week 2" will only use HTML and CSS that we've gone over. So if you're trying to follow along with the week 3 slides, you can copy and paste the code in week 2 and use it as a starter.

By the end of this workshop series you should have a website that looks like [this](Luceium.github.io).

# Day 1
### Install
- Git - to save your work
- Live Server - A VS code extension to display your changes without reloading

### Instructions
1. Make a repo in Github called `username`.github.io
1. clone the repo to your device
1. make an index file
1. set up a basic html layout with `!`
1. Set up Github pages
1. Start adding all your content with appropriate html elements
1. add inline css to make things a bit more pretty
1. push changes to github

### Notes
#### HTML

The main page should be called index.html
index.html will be loaded when the url to your website is called

The basic structure of an html file is
```html
<html>
    <head>
    </head>
    <body>

    </body>
</html>
```
Make comments with `<!-- my comment -->`

All elements will have a closing and ending tag. For example `<p> blah blah </p>`. If a tag has no inner content it's possible to have one tag. For example `<img />`.

Here are some of the more common elements that may be useful to you
- br - break line
- b - bold
- a - anchor, used too link to websites or part of your page
- p - paragraph, the default text element
- h1, h2, h3, ... - Headers of different levels
- div - a container with no styling
- span - a more limited inline container
- img - image
- table - table
    - tr - table row
    - th - table header
    - tr - table row
- ol - ordered list
    - li - list
- ul - unordered list
- iframe - displays content from outside of your website within the iframe

`<a>` tags are very useful. They can link to external pages, internal pages, and sections of our page.
To do this we give the anchor tag an attribute called `href`.
TO link to an external page put the url in the value of the href. For example `<a href="www.google.com">`. To link to an internal page, set the href to the file path to the target page's html file. An example could be `<a href="/extraPages/myPage.html">`. To link to a section of the page, mark an element with an id attribute (`<h1 id="name">`) then in the anchor tag list the target element's id. In this case our example is, `<a href="#name">`.

#### Dev tips
- Use emmet abbreviations
- Use an extension like Live Server too automatically refresh
- When trying things out with css, edit it in the browser console first
- Use inspect element tools to determine the sizing of elements
- A good layout is Code on one screen with a vertical monitor to the left split between the website on top and the console on the bottom

# Day 2 & Day 3
Please check out our slides for the next two workshops
[https://docs.google.com/presentation/d/1rODzPHlP0fmajGVogakojBsba3CxVjrERRPbnFHCbkk/edit?usp=sharing](https://docs.google.com/presentation/d/1rODzPHlP0fmajGVogakojBsba3CxVjrERRPbnFHCbkk/edit?usp=sharing)

# Post Workshop Series
You should now have the fundamental skills to build a simple website.
Our website is simple but effective. Our website design is good to share your work with employers but, if you want to take your website further you should! You can talk about your interests, show off your talents, and more.

Keep the conversation going in our personal website chanel

### Good Examples
sid.fyi
https://trustfuldev.github.io/stevenvu/


Author: Mauricio Curiel
Inspired by: https://github.com/Luceium/Luceium.github.io
