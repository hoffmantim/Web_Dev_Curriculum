# 1.1: How Do We Build Webpages?

### Languages we will use

* __HTML__ provides _structure_ to a webpage
* __CSS__ provides _style_ to a webpage
* __JavaScript__ provides _interactivity_ and _logic_ to a Webpages


### HTML

* HTML stands for __Hyper Terminal Markup Language__
* What is a __markup language__?
  * a language that _annotates_ text so that the computer can manipulate that text
  * while there are others, HTML is probably the most common and useful


#### HTML Tags

HTML uses __tags__

* Tags are enclosed in brackets `<>`
* Anything between the `<` and `>` is a _tag_
* Tags give the browser instructions for how to display text and other page elements
* Most HTML elements require and _opening_ and _closing_ tag
```
<p>This is a paragraph of text written in HTML</p>
```
* The _paragraph tag_ consists of the opening `<p>` and closing `</p>` tags
* Everything between the opening and closing paragraph tags will be displayed on the screen


#### HTML Elements

* An HTML element usually consists of an opening tag, a closing tag, and the content in between
    ```
    <p>This entire line is one element</p>
    ```
* HTML elements can be (and almost always are) _nested_ inside each other
* The `<h1>` (heading) and `<p>` elements are _nested_ inside the `<body>` element which is in turn nested inside the `<html>` element

    ```
        <html>
        <body>

        <h1>My First Heading</h1>
        <p>My first paragraph.</p>

        </body>
        </html>
    ```

### Our First Website

* Create a folder called Unit 1
* Inside that folder, create a file called `index.html`
* Open `index.html` in VSCode
* Together, we'll create a "Hello World" web page

#### Heading Tags

* There are six tags we can use for headings, `<h1>` - `<h6>`
* The bigger the number, the smaller the heading
* In your `index.html` file, and an `<h1>` that includes the text "Hello World" (don't forget your closing tag)
