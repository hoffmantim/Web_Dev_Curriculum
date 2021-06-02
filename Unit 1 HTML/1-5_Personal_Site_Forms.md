# 1.5: Building our Personal Site: HTML Forms

Let's build the __About Me__ and __Contact Me__ pages.

![Image][1]

### Adding Pages

In your project folder, create two new files:

* `about_me.html`
* `contact.html`

### Linking to Pages

Your main page should include two `<a>` tags, one each for the __About Me__ and __Contact__ pages. Change the `href=` attribute of your About Me page so it points to the file you just created. Do the same for your Contact page.

#### About Me Page

Open the `about_me.html` file and add the HTML boilerplate. Use the skills and HTML elements you've learned about so far to create your page. You can organize this page any way you'd like, but it should include more detailed (but brief) information about yourself. Try to use several HTML elements on this page (not just `<h1>` and `<p>` tags).

### HTML Forms

Your Contact page will include a form your visitors can fill out to request information.

Forms are defined by the `<form>` tag. Most fields in your form will be made up of both a `<label>` element and an `<input>` element.

```
  <form action='mailto:hoffmant@hilbertk12.org' method='POST'>
    <label for='name'>Your Name</label>
    <input type='text' id='name' name='name'>
  </form>
```

The `<form>` tag requires (at least) two attributes:
  * `action` - this is the route your form will point to; often this is another page on your site
  * `method` - usually either __GET__ or __POST__; this tells the site what to _do_ with the form data (we'll worry about this later)

The `<label>` needs a `for=` attribute which must match the `id=` attribute of an `<input>`:
  * This is what "connects" the label to the input.
  * If a user clicks on the label, the cursor will automatically head to the associated input.

The `<input>` also has a `type=` and a `name=` attribute:
  * Type can be `'text'`, `'password'`, `'submit'`, and others.
  * If an `<input>` does __not__ have a name attribute, it's content will __*not*__ be submitted with the form data.
  * We will use the name attribute to get data from our forms when we work with JavaScript later.

#### The Contact Me Form

Your __Contact Me__ page should have an `<h1>` at the top that reads "Contact Me". Beneath that, you can include either a phone number or email in a `<p>` tag (if you include both, consider an unordered list instead).

Under your contact info, create a `<form>`. Include a `<label>` and `<input>` for:

  * User name (`type='text'`)
  * Email address (`type='email'`)
  * Message (use a `<textarea>` instead of an `<input>`; the `rows=` and `cols=` defines the size of the input box)

```
  <textarea name='message_body' id='message_body' rows='8', cols='30'></textarea>
```

Create a `<label>` and `<input>` with the text "Subscribe to my newsletter?". The input `type=` will be 'checkbox'.

```
  <label for='email_list'>Subscribe to my newsletter?</label>
  <input type='checkbox' id='email_list' value=''>
```

Open the `contact.html` file and add the HTML boilerplate.








[1]:
