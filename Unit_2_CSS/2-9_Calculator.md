# Calculator Challenge

Here's what you're going to make:

<p align="center">
    <img src="" width="85%">
</p>

We'll turn this into a working calculator later (like our Tkinter project last year), once we learn a little JavaScript.

### Step 1

Create a new folder or codepen called `calculator-app` and add an `index.html` and `styles.css` files to it. Link the CSS file in your `<head>`.

### Step 2

Everything on this page is going to be a `<div>` within a `<div>`. There's one `<div>` to hold the entire calculator. I used the id `#calculator` to identify it. Each row is a `<div>` with a descriptive and unique class name. Each button is a `<div>` within its row `<div>`, with the number or symbol as its contents

For example, the all-clear button would be:

`<div class="ac">AC</div>

The back arrow, division, and multiplication symbols use Unicode:

* for the back arrow, the content of the `<div>` is `&larr;`
* the division symbol is `&#xF7;`
* the multiplication symbol is `&#215;`
