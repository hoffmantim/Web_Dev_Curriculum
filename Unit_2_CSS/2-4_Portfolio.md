# 2.4: Personal Portfolio

We've done just about all we can with the basic personal site we've been working on. We'll start fresh and build a new, more professional looking site using all we've learned about HTML and CSS.

Start by going to [codesandbox](https://codesandbox.io/) and making a new sandbox using the "Vanilla" template. Call it what you want (`my_portfolio_site` might be appropriate).

* Delete the `<div id="app"></div>' and `<script src="src/index.js"></script>` lines; delete the `index.js` file.
* Add a `<link rel="stylesheet" href="src/styles.css">` into the `<head>` section (make sure the `href=` is correct).


To make sure you've done everything correctly so far, add a `background-color` to the `<body>` element by declaring it in your CSS file. Save everything, and you should see an empty window with the background you chose.

### Custom Fonts

The way browsers render fonts can be kind of confusing. Basically, you can use CSS to define the font your page should display in, but if your user's browser or computer doesn't have that font installed, it will default to something esle. You can define what this default behavior will be.

The syntax for defining a font-family in CSS is:

```
    p {
        font-family: 'Times New Roman', Times, serif;
    }
```

If "Times New Roman" isn't installed, the browser will default to Times, then to a basic serif font.

#### Google Fonts

There are a number of useful, sylized, and free fonts available to use on your site organized by Google at [Google Fonts](https://fonts.google.com).

To use a Google Font, you need to add a `<link>` in the `<head>` of your HTML file, or an `@import` line at the top of your CSS file. The Google Fonts site has this code and instructions for using it.

### Begin Your Site

Add a `<div>` to the `<body>` of your site to begin the top section. Begin building this section of your page so it looks something like the image below.

* Choose a couple fonts from [Google Fonts](https://fonts.google.com) (keep the `<p>` and other body text fairly simple).
* Set a background color for your text (use [colorhunt](https://colorhunt.co) if you'd like).
* Find or create an image. If you want a transparent background like mine, you'll need to use a `.png` file. I can help you create this.
Lay everything out so it's centered and spaced out well.

![Image](https://github.com/hoffmantim/Web_Dev_Curriculum/blob/master/Unit_2_CSS/images/CSS_Portfolio_Top.png?raw=true)

