# 2.2: The Box Model

In addition to color and font size, CSS allows us to define the __layout__ fo our page in ways much easier than using something like a `<table>`. Essentially, CSS treats every element on our webpage as a box or series of boxes and allows us to manage its properties to determine where and how to place it on the page.

So far, all of our elements have just been rendered one after another. Let's change that.

The core elements of the CSS Box Model are:

* padding
* borders
* margins
* block boxes
* inline boxes

### Setup

Go to [codesandbox](https://codesandbox.io/) and click __create sandbox__. Choose the __vanilla__ template. 

Delete the `<div id="app"></div>' and `<script src="src/index.js"></script>` lines; delete the `index.js` file.

Add a `<link rel="stylesheet" href="src/styles.css">` into the `<head>` section (make sure the `href=` is correct). Add the following code to the `<body>` section

```
    <h1>Headings Are Block Elements</h1>
    <p>Paragraphs are block elements, too. <em>However</em>, em and strong elements are not. They are <strong>inline</strong> elements.</p>
    <p>Block elements define the flow of the HTML document, while inline elements to not</p>
```

Add the following declarations to your CSS file:

```
    h1, p {
        background-color: #DDE0E3;
    }

    em, strong {
        background-color: #B2D6FF;
    }
```

### Block and Inline Elements

The background color should allow you to see exactly how these to elements work together.

* Block boxes fill the width of their parent (in this case, the entire window), and their default height is determined by the content inside them.
* Each block box appears below the previous one.
* Inline elements don't affect vertical spacing.

Try overriding the behavior of the inline elements on your page:

```
    em, strong {
        background-color: #B2D6FF;
        display: block;
    }
```

Usually, you wouldn't want to turn `<em>` or `<strong>` elements into block elements, though. However, you could use `display: block;` to turn an `<a>` into a button or to format an `<img>`.

Turn your `<em>` and `<strong>` elements back into inline elements (either remove the line or change it to `display: inline;`).

### Content, Padding, Border, and Margin

The CSS box model determines the dimentsions of each element on a given page. Each box is given four properties:

* __Content__ - The text, image, or other media content in the element
* __Padding__ - The space between the box's content and its border
* __Border__ - The line between the box's padding and margin
* __Margin__ - The space between the box and surrounding boxes

The content is defined by HTML, the rest by CSS

![Image][1]

Go to this [tutorial](https://internetingishard.com/html-and-css/css-box-model/#changing-box-behavior) on the CSS box model and read / work through it to learn about how padding, borders, and margins work together to allow you to structure content on your webpage.

### Level up your site

Use what you've learned here to add some more style to your webpage. Add at least one border to an element and change the padding and margin of something to make the spacing and visual interest of your page more appealing.

[1]: https://github.com/hoffmantim/Web_Dev_Curriculum/blob/master/Unit_2_CSS/images/CSS_Box_Model.png?raw=true