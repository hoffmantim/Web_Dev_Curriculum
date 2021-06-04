# 2.6: Flex and Navbar

We'll need to learn a few new concepts and tools in order to continue working on our portfolio. Specifically, we want our site to look good on whichever device someone views it on.

### Flexbox

The best way to explain __Flexbox__ is to let someone else do it. Work your way through [this tutorial](https://internetingishard.com/html-and-css/flexbox/) on CSS Flexbox.

### Navbar

A __Navbar__ is the navigation bar at the top of a webpage. Let's add one to your portfolio. This will have links to other important pages on your site. For now, it will include links to your _Home_ and _Contact Me_ pages.

Your navbar will look something like this:

<p align="center"> 
<img src="https://github.com/hoffmantim/Web_Dev_Curriculum/blob/master/Unit_2_CSS/images/CSS_Navbar.png?raw=true" style="width: 75%;" > </p>


First, above the existing content on your page, add a `<div>` with `class="nav-bar"`. Add two `<a>` hyperlinks, one for _Home_ and one for _Contact Me_. Each link should have a `class="nav-item"`. The _Contact Me_ link should have an `href="mailto:your_email.mail.com"`.

In your CSS file, add some style to your navbar. Give it a contrasting `background-color` so it stands out from the rest of your page. Make sure to pick something that works with your color palate. 

Use `display: flex;` and `flex-direction: row;` to align the content. __HINT__: You'll need at least one more CSS rule to keep the two links aligned to the left of the page.

Change the font, color, padding, margin, etc. of each `<a>` to make them readable and interesting. You can save time by using the class identifier.