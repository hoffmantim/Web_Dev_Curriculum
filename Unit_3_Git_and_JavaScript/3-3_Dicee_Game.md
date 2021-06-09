# 3.3: Dicee Game

This is what we'll create:

![Image][1]

### Set Up the Project
Start by creating a folder called `Dicee` and a folder inside that called `images`. Then, download the starter code here and place the files into the correct folders.

[index.html](https://docs.google.com/document/d/1oe_9Fnj-rqPfi10pWaiS70y4toE5gmuO8kdddGWUcyA/edit?usp=sharing)
[styles.css]()
[images]()

Last, add a `scripts.js` file to your project. Create the file, then add a `<script>` tag immediately above the __closing__ `</body>` tag at the bottom of your HTML file.

    `<script scr="scripts.js" charset="utf-8'></script>`


### Add the Dice Images
Using the `dice6.png` files in the `images` folder, add the dice as the source to both of the `<img>` elements on your page.

### Create a Random Number

Inside `scripts.js`, create a new variable called `randomNumber1`, then set the value of this variable to a random number between 1 and 6. Test it with `console.log` to make sure it works.

### Change the Image to a Random Dice

Use the random number you created to pick out a random dice image between dice __1__.png and dice __6__.png and place this image inside the left `<img>` element.

Do the same for the right hand dice (use `randomNumber2` for your variable).

### Show the Winner

Change the text in the `<h1>` (which currently says "Refresh Me") to show which user won or if there was a draw depending on the dice values of Player 1 and Player 2.

![Image][2]

So far, the dice images should only change if we refresh the page. Later, we can add a button to roll for us.

[1]: https://img-c.udemycdn.com/redactor/raw/2018-11-03_02-33-30-e969152f9728c3403db9258047ee2105.png?Expires=1623254246&Signature=InrzgiGefYznWlLXvQXF2s4OA~a9J5w2oDmcGOLiGbdMv2N9mTqAK6NzRUkRkZi9TO1R9QM6LCQsLTBoWTjT~bIH7ywAEDvK49I0wFVJdKPLiq6xaC64PMJWP2-KG1nKdprRPLxK0W3P9gwU-lAiMjImlHCCMs94TJmQJze-QGycGyBv4eAJkyzHIY83govUxpx6roqw~7FoXhOKMiJh~CAbLkfFFZhNZgelNHKdLB3Pz9AaKexdzTceYa2~VOnuWtQNpmyh9DMbJhDKOyoiCbP753kQVfg4KfJjzbc2D4x-BYmH0Qzwnkuxsrmf4xSF-qugMPOiAXvGwgPRESgm1g__&Key-Pair-Id=APKAITJV77WS5ZT7262A 
[2]: https://img-c.udemycdn.com/redactor/raw/2018-11-03_02-51-14-87553d9e0d570eab7ab9cb19af24f242.gif?Expires=1623254160&Signature=ODGZA~m5axiEfnUVWE1tyuHzXsJGLh4jMkyWF0yhgRdIyFGrZR~BJKQ0wFwZZ3efiCNfglHqRbsTf~irUyu5U7vLWFSVK8LHATsCnYL6hpYM4d-1Wog8ZJ0O89ABEmBRpx8RseE6x72E69jgqV3EsytM6-4vty3KCKTlHULsr6ZMsGvuvQnnDhK78Yc1bbK2yIpbMzvia5Xp1my~emsFcgEK0ZXnNaKYO-nuqfagFjA6~qOKqn0l4fuZim4euFWSc86Exm1O5zTv7BkKvwy76uhVESAIH6bF8vhx1VQTUQQAmkX4lGqkJJoJPVoXkrjUu08bReKS-nrgwPgCnCsTnw__&Key-Pair-Id=APKAITJV77WS5ZT7262A
