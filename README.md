# jQuery Plugin Play

So first of all, it's important to note that jQuery isn't a programming language in and of itself. jQuery is in fact a JavaScript library. JavaScript is one of the most widely used programming languages in the world, that is primarily used to control elements in the browser. jQuery is an library, or extension of JavaScript that allows us to do really cool things like shoot basketball hoops with a bowling ball or make Kanye disappear.

What's even cooler about jQuery is that a ton of developers have created `plugins` and made them free and available to the public to use. A plugin is a module of code written by another developer that we can incorporate into our projects in order to do cool things. It let's us enhance our projects without having to write a whole bunch of code ourselves.

There are some super useful jQuery plugins that do things like parallax scrolling, making grids and charts on your site, dealing with date and time stamps, etc. While all of those are fully functional, they're not super fun. 

In this lesson, you'll be playing with a collection of the most fun jQuery plugins!

## Let's Get Started

### Step 1:

Click `Open` at the top of this page to bring this lesson down so you can edit files in Nitrous.

<img src="https://s3.amazonaws.com/after-school-assets/new-open-in-nitrous.png">

### Step 2:

Open `index.html` in the browser by running in terminal `python -m SimpleHTTPServer 3000`. 

Once you have the server running, select `preview` and then `port 3000`.

<img src="https://s3.amazonaws.com/after-school-assets/nitrous-preview.png" alt="nitrous preview">


### Step 3:

You're going to code your solution in both `index.html` and `js/script.js`. Go ahead and open both files in the Nitrous text editor. 


### Step 4:

Take a look at `index.html` in the browser. It should be completely blank.


### Step 5:

In `index.html` we need to link the basic jQuery library and our custom jQuery file (`js/script.js`). Copy the following HTML and paste it in `index.html` right before the closing body tag:

```html
<script src="http://cdnjs.cloudflare.com/ajax/libs/jquery/2.1.1/jquery.min.js"></script>
<script src="js/script.js"></script>
```

This link gives us access to the basic jQuery library or our ability to write our own jQuery. Without this line of code, we can't use any jQuery.

### Step 6: Fart Scroll

Let's play with a great jQuery library, [Fart Scroll](http://theonion.github.io/fartscroll.js/]. You'll want to make sure your volume is on.

So first of all, in order for this to work you need to make sure there is enough content on your `index.html` to scroll down. Go ahead and fill it in with some HTML:

```html
<div>
  <img src="https://s3.amazonaws.com/after-school-assets/cat.gif">
</div>
<div>
  <img src="https://s3.amazonaws.com/after-school-assets/cat.gif">
</div>
<div>
  <img src="https://s3.amazonaws.com/after-school-assets/cat.gif">
</div>
<div>
  <img src="https://s3.amazonaws.com/after-school-assets/cat.gif">
</div>
<div>
  <img src="https://s3.amazonaws.com/after-school-assets/cat.gif">
</div>
<div>
  <img src="https://s3.amazonaws.com/after-school-assets/cat.gif">
</div>
<div>
  <img src="https://s3.amazonaws.com/after-school-assets/cat.gif">
</div>
<div>
  <img src="https://s3.amazonaws.com/after-school-assets/cat.gif">
</div>
<div>
  <img src="https://s3.amazonaws.com/after-school-assets/cat.gif">
</div>
<div>
  <img src="https://s3.amazonaws.com/after-school-assets/cat.gif">
</div>
<div>
  <img src="https://s3.amazonaws.com/after-school-assets/cat.gif">
</div>
<div>
  <img src="https://s3.amazonaws.com/after-school-assets/cat.gif">
</div>
<div>
  <img src="https://s3.amazonaws.com/after-school-assets/cat.gif">
</div>
```

Next, we need to link the Fart Scroll Source code. Copy the HTML below and paste it just below the jQuery tags above the closing body tag:

```html
<script src="http://code.onion.com/fartscroll.js"></script>
```

Last, we need to modify `js/script.js`. Copy the jQuery below, and paste it in `js/script.js` below the comment `//code your solution here!`:

```js
fartscroll();
```

Save your changes in both `js/script.js` and `index.html` and refresh the page in the browser. Scroll and hear the fart sounds!!


### Step 7: Fool.js

Next, we're going to play with another plugin called [Fool.js](https://github.com/idiot/fool.js). The plugin easily lets you set up pranks for your users.

We've provided the code for this library already (`js/fool.js`), but you need to link this file to your HTML file. Copy the code below and paste it in `index.html` just before the closing ball tag:

```html
<script src="js/fool.js"></script>
```

And now to use the plugin! There are a bunch of different pranks you can try.

```js
vanishingElements // hides random elements as they interact
questionTime // Sing spongebob with your browser
upsideDown //Flip the page upside down
h4xx0r // make the page 100% editable
wonky //make the page a little bit crooked
flash //makes the site flash on and off
crashAndBurn //Runs an endless loop. This will kill your browser!
shutter // Forces a shutter on the screen
unclickable //  Makes the page unclickable
```

In `js/script.js`, copy the code where you see the comment `//try fool.js here`:

```js
$.fool('prank-goes-here');
```

Replace the text `prank-goes-here` with the name of the prank you want to try, for example:

```js
$.fool('upsideDown);
```

Save the changes to the file and refresh in the browser to watch the prank happen!

## Done and Done

Lastly, you need to enter in terminal in Nitrous `learn submit`. This command will push your work to GitHub and mark this lesson as complete in Learn!

## Share Share Share!
Show of your work by taking a screenshot of your filled treasure box or code and share with **\#flatironcodeclub** and **\#jQueryPluginPlay**

## Reminder 

Don't forget to shut down your server by hitting `control` and `c` before you move on to other material!
