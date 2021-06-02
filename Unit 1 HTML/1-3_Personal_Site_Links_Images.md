# 1.3: Building our Personal Site: Links and Images

Let's add a few things to make our pages more visually appealing and useful

![Image][1]


### The `<img>` element

To add images to your site, use the `<img>` tag

Some tags, like `<img>` are __self-closing__: you will _not_ include a closing `</img>` tag. Instead, everything will go _inside_ the tag.

### HTML Attributes

The `<img>` tag relies on HTML __attributes__ to function

Attributes are contained inside an element's opening tag. All HTML elements can have attributes.

Attributes provide additional information about an element. Attributes are always specified in the opening tag. Attributes usually come in name/value pairs like:

`name='value'`

### `<img>` Attributes

Your image tag should have two attributes for now (later we may add more):

* `src=' '` This will indicate the image __source__.
* `alt=' '` The __`alt`__ or "alt text" attribute is used by assistive devices for visually impaired users.

### Adding an Image

First, save your image file into the same folder as your `index.html` file. The `src` attribute should be the name of the file. The `alt` attribute should be a short description of the image:

`<img scr='logo.png' alt='page logo>`

### Adding Links

Linking to another page (or to another part of the same page) is one of the most basic functions of websites. Links are added with the `<a>` tag ('a' is for __anchor__). Like the `<img>` tag, the `<a>` tag requires the use of attributes.

To add a link, wrap the text you want displayed in an `<a>` tag (don't forget the closing tag). Put the destination (the URL) in an `href=` attribute:

```
  <a href='http://www.google.com'>Click Here</a>
  <a href='aboutMe.html'>About Me</a>
```

### Level Up Your Page

1. Use an `<img>` tag to add an image to the top of your page, above the `<h1>` with your name.
2. At the bottom of the page, below your skills, add a couple of links. One should be to an __"About Me"__ page and one to a __"Contact Me"__ page.
3. Use `href='about-me.html'` and `href='contact-me.html'` for these links (we'll build the pages later).


[1]: https://github.com/hoffmantim/Web_Dev_Curriculum/blob/master/Unit%201%20HTML/1-3_Links_Images.png?raw=true
