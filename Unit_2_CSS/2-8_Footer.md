# 2.8: Contact Button and Footer

Let's add a "Contact Me" button and a footer with some copyright info and other links.

### Step 1

First, below your __Skills__ section, add another dotted horizontal line.

<p align="center">
    <img src="https://github.com/hoffmantim/Web_Dev_Curriculum/blob/master/Unit_2_CSS/images/CSS_Float_Skills_Section.png?raw=true" width="85%">
</p>

Next, add a `<div>` for a "Get in Touch" section and one for a footer (similar to our navbar at the top).

<p align="center">
    <img src="https://github.com/hoffmantim/Web_Dev_Curriculum/blob/master/Unit_2_CSS/images/CSS_Footer.png?raw=true" width="85%">
</p>

### Custom Button

In your "Get in Touch" `<div>` add some text using an `<h2>` and `<p>` (or similar, depending on the info you want to add).

Below your text (still inside the `<div>`), add an `<a>` with a `class="btn"` and an `<href="mailto:yourmail@gmail.com">`. In your CSS file, add some rules for your `.btn` class:

* set a `border-radius:` of 12px
* set a `background-color:` (I used the same as my nav & footer)
* set a text color that offers enough contrast with your background to make it readable
* add a `box-shadow` (look this up for the syntax); your values should be `0 1px 3px` and a color appropriate for your chosen palatte
* add some padding so that it looks like a button

In your CSS file, add some rules for the __*pseudoclass*__ `.btn:hover`. These rules will change the look of your "button" when the user "hovers" the mouse over it. Change the `background-color` to a different, complimentary color (you may want to change the text color, too).

### Footer

Add a `<div>` below this section for your footer. Give this section a `background-color` (I used the same as my nav bar). Add three links to your Twitter page, your LinkedIn, and your GitHub (these can just point to twitter.com, LinkedIn, and Github). Alternately, you can link to other social media accounts; just make sure they're ones you want to share and have associated with your work.

Add an `a:hover` pseudoclass so that the color of the links changes and they become underlined when hovered over.

Include a copyright line with the year (it's a good idea to also use this space to credit any images you used from third party sources, like [flaticon.com](https://www.flaticon.com), using their rules).

### Tidy It Up

Make sure that everything looks the way you wnat it to and that your links all work correctly.

* Check for consistently spaced and well-aligned items. 
* Check the size and placement of all images, texts, buttons, etc.
* See what your page looks like if you change the size of the browser window. 
    * Do your nav bar and footer still look good?
    * Do the images in your skills section still float nicely?
    * Is everythign readable on a narrower screen?

Congratulations on your new portfolio site!