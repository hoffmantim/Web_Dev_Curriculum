# 2.1: More CSS

Remember that HTML is used to give your page both __structure__ and __content__. CSS is used to give the page __style__. 

First, we're going to need a way to orgainze our HTML into _containers_ so we can style the parts of the page we want to.

### DIVs

The `<div>` tag is used to organize content in HTML. According to MDN:

> As a "pure" container, the `<div>` element does not inherently represent anything. Instead, it's used to group content so it can easily be styled using the `class` or `id` attributes, [etc.]

Using a `<div>` won't, by itself, do anything to your page. The `<div>` allows you to __style__ chuncks of content, though, by using attributes such as __id__ or __class__.

### IDs

You can add an `id` to an HTML element in the opening tag. An `id` allows you to identify an element in your CSS (or JavaScript) and style it uniquely. 

There can only be __ONE__ `id` with a given name per page.

### Classes

Classes are similar to id's. However, two or more elements may share a single class. That is, you can use a class to identify (and style) several elements on your page.

In addition, an element may have more than one class.

![Image][1]

### Using Classes and Id's

The `<div>` above has an id of `"skills-section"` and two classes. The classes are `"text-box"` and `"second-class"`. The `<h1>` has a class of `"header"`.

You can style elements uniquely by referring to their classes or id. In CSS, a _class_ name is preceded by a period. In CSS, an _id_ name is preceded by a pound sign (#).

![Image][2]
![Image][3]

### Level Up Your Site

It's time to add some style to your personal portfolio site.

#### Add Some Color
1. Inside your Personal_Site folder (alongside your index.html & other html files), create a file called `style.css`.
2. Open both index.html and style.css in VS code.
3. Between the `<head>` tags, add the following line of code:
```
    <link rel="stylesheet" type="text/css" href="style.css">
```
4. Add a background color to the entire page
    * HINT: use the `<body>` tag or `<html>` tag as a selector to inure your backgound color covers the whole page.
    * Pick a color that won't hurt your users' eyes. Try using [colorhunt](https://colorhunt.co) to pick a nice color pallete (you'll be changing text colors next, so you want to pick colors that work well together).
    * If you click on a color from [colorhunt](https://colorhunt.io), it will copy the hexadecimal code for that color. As long as you put a # in front of this code in your CSS, you can use this to specify an exact color.
5. Add a different, compatible color to all of the `<h1>` and `<h2>` elements on your page. There are a few different ways you can add the same style to different selectors, like by using a class.
6. Add some color the `<p>` elements. You can use the same color for all or different colors; just make sure you page is readable.
7. If you need to change the color of the `<a>` elements or anything else to improve readability, go ahead and do so.

#### Font Size

1. Let's resize some of the text on your page.
2. Make all of your `<h1>` elements larger by changing the `font-size` to `40px`. Change the `font-size` of your `<h2>` elements to `30px`.

#### Other Pages

How can you add the __same__ styling to your About Me and Contact pages? Are there any other elements you need to take into consideration when styling these pages?


[1]: https://github.com/hoffmantim/Web_Dev_Curriculum/blob/master/Unit_2_CSS/CSS_ID_&_Class.png?raw=true
[2]: https://github.com/hoffmantim/Web_Dev_Curriculum/blob/master/Unit_2_CSS/CSS_Class_Declaration.png?raw=true
[3]: https://github.com/hoffmantim/Web_Dev_Curriculum/blob/master/Unit_2_CSS/CSS_ID_Declaration.png?raw=true