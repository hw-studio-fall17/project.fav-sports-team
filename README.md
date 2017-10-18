# Sports Team website

##### You're going to create a website for you favorite sports team. Once you've chosen your team, make sure to checkout their real website for ideas.


<!-- TODO ADD EXAMPLES: -->

## Look at what was given to you...
* You have three HTML files `home.html`, `schedule.html`, `gear.html`
* You have a `style.css` that is already linked to all of your HTML files using: `<link rel="stylesheet" type="text/css" href="style.css">` in the `<head>` tag
* jQuery is linked in the `<head>` of ALL of your HTML pages using: `<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>` in the `<head>` tags
* You have a `script.js` that is already linked in all of your HTML files using: `<script type="text/javascript" src="script.js"></script>` in the `<head>` tags
* There is a navigation bar in `home.html` that has some styles prewritten for you. Click on the links to make sure they are working properly. You will probably want to add more styling as you continue to build your website.

______________________________________________________________________________
## LEVEL ONE

### Home Page in `home.html`
* Change WEBSITE NAME to say something better
* Add a brief bio of the team
* Add a pump up video using the `<iframe>` tag. GOOGLE "HTML iframe tag" to figure out how to use it!
* Add a background color to this page

### Schedule Page in `schedule.html`
* Make a table using the HTML `<table>` tag that shows the team's schedule
* Add a 'ticket' button to each game. Here is a good example: 
<!-- TODO add example screenshot -->
![tour-dates example](images/example-tour-dates.png). You will need to google "how to make a button using HTML".


### Gear Page in `gear.html`
* Add at least 4 images of team gear that is for sale

______________________________________________________________________________
## LEVEL TWO

### Home Page
* Change your background color to be a linear-gradient() <-- google it! instead of one solid color
* Add a [google font](https://fonts.google.com/) to your page.
  * Click on the red plus sign of the font you want to use
  * Click on the black bar at the bottom of the page that says 1 Family Selected
  * Copy the `<link>` and put it inside the `<head>` tag in your HTML file
  * Follow the font-family instructions for your CSS
* Change the color of the text on your page


### Schedule Page
* Style your buttons to look better. Here are some CSS properties you will probably want to use:
  * `background-color`
  * `border-radius`
  * `padding`
  * `color`
  * `border`
  * `box-shadow`
* When the user clicks on the tickets button bring them to a website where they can buy tickets. HINT: you can do this using an `<a>` tag inside the `<button>` tag. See below...
  ``` HTML
  <button><a href="link_goes_here"></a></button>
  ```
* Add a `hover` effect to the buttons on your tour dates table, so that when you hover on the ticket buttons some of the colors change. (or something else changes!)

### Gear Page
* Add a parallax image to your page. [See an example here](https://www.w3schools.com/howto/howto_css_parallax.asp)


______________________________________________________________________________
## LEVEL THREE

### Home Page
* Make your navigation bar slowly fade in when the page loads. Hint: you will need to use the jQuery fadeIn() function. Google it if you forget how it works.
* Get rid of the underlines on the link tags in your navigation. Google "how to remove underlines from link tags with CSS"

### Tour Dates Page
* Create a secret spot on the page. When the user clicks on it, they will be alerted that they won season tickets! Follow the steps below:
  * Create a new HTML element to be clicked or decide which old HTML element you would like to use. Add an id to the element so that it is easy to select using jQuery.
  * Select your element in `script.js` using jQuery and save it in a variable.
    * ``` var exampleVariable = $("#example-id") ```
  * Call the onClick() jQuery function on your variable. 
  <!-- TODO link onClick() -->
  * Use the alert() function to create a pop up saying the user has won back stage passes 

______________________________________________________________________________
## LEVEL FOUR
### Other ideas
* Add a [slide show](https://www.w3schools.com/howto/howto_js_slideshow.asp) of images to one of the pages.
* Try to use spotify or soundcloud to embed a song on one of the pages

### CREATE!
* Use your creativity to make your website even more awesome!

______________________________________________________________________________