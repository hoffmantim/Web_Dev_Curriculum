# 2.5: Static and Relative Positioning

Remember how __Block__ and __Inline__ elements work:

* __Inline elements__ are only as tall and wide as the _content_ inside them.
* __Block elements__ are as wide as their _parent container_, but only as high as their content.

### Content is everything

The order that elements display on your page is determined (mostly) from the order in your HTML. If you want an image to appear above an `<h1>` for example, that `<img>` needs to come first in your HTML.

### Children Sit on Parents

A __parent__ element is any HTML element that "wraps" or contains another element. The `<div>` below is the _parent_ element and the `<h1>` is the _child_ of the `<div>`.

```
    <div>
        <h1>Hello World</h1>
    </div>
```

On your page, children sit _"closer" to the user_ and "further" from the screen. That is, children sit on "top" of their parent elements (if it were the other way, you'd never see the `<h1>` since it would be behind the `<div>`).

Essentially, this means that your webpage has an x-axis, a y-axis, and a z-axis.

* If we put a `<span>` inside of the `<h1>`, where would it sit on the z-axis?

### CSS Position

We can use the CSS `position:` property to change the default layout behavior of elements. To learn about the various values you can use with `position:`, check out this [tutorial page](https://css-tricks.com/almanac/properties/p/position/).

* Create a new folder or code sandbox called `css_challenge`.
* Add an `index.html` file and a `style.css` file.
* Add a `<link>` to the CSS file in your `<head>`.
* In the `index.html` file, create three `<div>`:
    * The first should have a `class="red"`
    * The second should ahve a `class="yellow:`
    * The third should have a `class="blue"`
    * Use your `style.css` file to give each of the `<div>` a height and width of `60px` and a `background-color` corresponding to its class name.
