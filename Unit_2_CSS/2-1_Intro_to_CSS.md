# 2.1: Intro to CSS

So far, we've used HTML to 

* Give our page __structure__ and organization
* Give our page __content__

What our page doesn't have is __style__

### CSS

CSS stands for __Cascading Style Sheets__. CSS works alongside HTML to give elements on a web page _style_. CSS can work on color, size, position, orientation, and other aspects of a page. CSS can also help us to easily provide different variations of our page for different screen sizes (think phone versus laptop).

CSS describes how HTML elements should be displayed.

### Anatomy of CSS

A CSS ruleset consists of a __selector__ and a __declaration block__.

![Image][1]

The __selector__ points to the HTML element to style. We can use tags like `<h1>` to select every instance of that kind of element on a page. There are other things we can use, too, though.

The __declaration__ defines the style to be added. You can declare several style definitions within each declaration block.

Each declaration consists of a CSS __property__ and a value separated by a colon and terminated with a semicolon.

What will happen to our page if we add the following CSS block?

![Image][2]

### Inline CSS

CSS styling can be added to individual HTML elements __inline__ using the `style=''` attribute

![Image][3]

### Internal CSS

CSS styling can be added using the `<style>` tag inside the `<head>`

![Image][4]

### External CSS

Probably the most common way to add CSS is with an external file. Use the `<link>` tag inside of the `<head>` to point to your CSS file (often called `style.css` or something similar). The `href=''` attribute points to the CSS file.

![Image][5]

We'll use an external CSS file to add some style to our personal site.

[1]: https://github.com/hoffmantim/Web_Dev_Curriculum/blob/master/Unit_2_CSS/images/CSS_Block.png?raw=true
[2]: https://github.com/hoffmantim/Web_Dev_Curriculum/blob/master/Unit_2_CSS/images/CSS_Declaration.png?raw=true
[3]: https://github.com/hoffmantim/Web_Dev_Curriculum/blob/master/Unit_2_CSS/images/CSS_Inline_Styling.png?raw=true
[4]: https://github.com/hoffmantim/Web_Dev_Curriculum/blob/master/Unit_2_CSS/images/CSS_Internal_Styling.png?raw=true
[5]: https://github.com/hoffmantim/Web_Dev_Curriculum/blob/master/Unit_2_CSS/images/CSS_External_Styling_Link.png?raw=true