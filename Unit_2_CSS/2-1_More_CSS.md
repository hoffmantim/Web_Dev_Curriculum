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

1. Wrap the sections of your site with `<div>` tags (the header, the employment section, the skills section, etc.). 
2. Use some classes and at least one id to add some style elements to your personal site.
3. You can give each section its own background color, text color, etc. by adding an id and accessing it in CSS. Or you can give certain sections the same color (or other attribute) by giving them the same class.
