# 2.7: Float

The next section of our site should include a little bit about our interests, skills, or hobbies

<p align="center">
    <img src="https://github.com/hoffmantim/Web_Dev_Curriculum/blob/master/Unit_2_CSS/images/CSS_Float_Skills_Section.png?raw=true" width="85%">
</p>

### Float

__Float__ is a CSS property that takes its name and function from print media. If you've ever inserted a picture into a Word or Google Doc, you've probably played with the float property. In print text, words can either wrap around an image box or flow right over it like it wasn't there. Web pages work similarly.

Elements with `float` applied to them behave like images in print with words "wrapped" around them.

<p align="center">
    <a href="https://css-tricks.com/all-about-floats/"><img src="https://github.com/hoffmantim/Web_Dev_Curriculum/blob/master/Unit_2_CSS/images/CSS_Float_Example.png?raw=true" width="75%"></a>
</p>



### Float Properties

There are four values you can use for the float property:

* __Left__ and __Right__ will float elements those directions, respectivly.
* __None__ (the default): the element will not float.
* __Inherit__: the element will inherit the float value from its parent element.

Floats _can_ be used to define your page layout:

<p align="center">
    <a href="https://css-tricks.com/all-about-floats/"><img src="https://github.com/hoffmantim/Web_Dev_Curriculum/blob/master/Unit_2_CSS/images/CSS_Float_Layout.png?raw=true" width="60%"></a>
</p>

However, today there are other, far more popular and powerful tools for this, because floats can lead to unintended problems.

### Skills Section

Use `float` to layout your Skills section, such that each skill you include has an image that floats to the left or right of a `<div>` which includes an `<h3>` and a `<p>`. Style each item appropriately in your CSS. You will likely need to resize the images you include. You can chage the `height:` and/or `width:` using `px` or a percentage.

<p align="center">
    <img src="https://github.com/hoffmantim/Web_Dev_Curriculum/blob/master/Unit_2_CSS/images/CSS_Float_Skills_Section.png?raw=true" width="85%">
</p>

### Bonus

Using CSS, try to create the dotted lines I have above and below this section (hint: each dotted line consists of a single `<hr>` in the HTML; it's styled with CSS).