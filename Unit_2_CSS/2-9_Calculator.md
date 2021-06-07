# Calculator Challenge

Here's what you're going to make:

<p align="center">
    <img src="https://raw.githubusercontent.com/hoffmantim/Web_Dev_Curriculum/master/Unit_2_CSS/images/CSS_Calculator.png" width="20%">
</p>

We'll turn this into a working calculator later (like our Tkinter project last year), once we learn a little JavaScript.

### Step 1

Create a new folder or codepen called `calculator-app` and add an `index.html` and `styles.css` files to it. Link the CSS file in your `<head>`.

### Step 2

Everything on this page is going to be a `<div>` within a `<div>`. There's one `<div>` to hold the entire calculator. I used the id `#calculator` to identify it. Each row is a `<div>` with a descriptive and unique class name. Each button is a `<div>` within its row `<div>`, with the number or symbol as its contents

For example, the all-clear button would be:

`<div class="ac">AC</div>`

The back arrow, division, and multiplication symbols use Unicode:

* for the back arrow, the content of the `<div>` is `&larr;`
* the division symbol is `&#xF7;`
* the multiplication symbol is `&#215;`

### Step 3

The rest of our work will be done in CSS

You'll need to use grid to lay everything out.

* The top-level `<div>` that holds everything else will contain one column (you'll have to define the `grid-template-rows`).
* Each row `<div>` will need `grid-template-columns` defined.
* Remember that you can use `1fr`, `2fr`, etc.
* You can also define which "line" each item in a grid element starts and ends at.

In addition to the layout, you'll need to define borders, padding, background and text colors.

* The display box color I used is `#383838`.
* The border color is simply `"gray"`.
* The background of the number keys is `"lightgray"`.

You can make yours look even better than mine by using different colors, a better font, size, centering, and aligning things better, etc.