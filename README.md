# Let's Make A Website (For Absolute Beginners)

## About Me

My name is Jun Kagaya, I work in Payroll, and I used to be a tour guide and have walked the esteemed Milford Track 26 times, here's my [CV](https://gieoon.github.io/CV/)

I've also taken on the challenge of spreading knowledge about IT by creating an series of easy to follow lessons to get you guys engaged in creating your first (maybe) website.  

We're going to create a website that looks like this
![Final Website](https://github.com/gieoon/MakeMyWebsite/blob/master/FinalWebsite.png "Final Website")

In making this site, we're going to cover the basics of web development and get you the skills needed to make a basic webpage.

This course aims to:
- Make your Developers proud
- More intimately understand the business you are involved in
- Be able to manage project constraints.

This course is aimed at absolute beginners, as such it will progress slowly for people who are tech savvy, but feel free to stick around and help your colleagues make their websites.

What technology we'll be using
- HTML
- CSS
- Javascript
- Making API calls

## Setup

There's barely any installations!

To make our website we will just need to be able to type text.
Download and use a text editor of your choice. These are simply used to edit text and are nothing fancy.
Below are the most common selections
- Sublime Text
- Notepad++
- Visual Studio Code

The reason we use text editors instead of plain Notepad or TextEditor, is so we get things like code indenting, and line numbers, which are both features that Developers can't live without.

## Introduction to HTML

XML based language to create an outline of the page.

Every single webpage is made of HTML, or [__Hyper Text Markup Language__](https://www.google.com/search?ei=nAptXcDHGbnTz7sPi4-sqAk&q=what+does+html+stand+for&oq=what+does+html+stand+for&gs_l=psy-ab.3..0j0i7i30l9.1723.2177..3487...0.2..0.363.554.0j1j0j1......0....1..gws-wiz.......0i71j0i10.KWPGF8WAYW4&ved=0ahUKEwjAhaW5kbLkAhW56XMBHYsHC5UQ4dUDCAo&uact=5)

You may have heard of Developers talking about __React__ or __Angular__, these are frameworks used to make web development easier, but they have their own build processes to eventually export the code into HTML to be rendered onto your browser.

Websites can be complex, for example this is what the HTML page source of a Google Search looks like.
![Page Source](https://github.com/gieoon/MakeMyWebsite/blob/master/PageSource.png "Page Source")

Below is the skeleton of a basic HTML page.
```
<!DOCTYPE html>
<html>
  <head>
  </head>
  <body>
    <p>Hello World</p>
  </body>
</html>
```
1. Copy & Paste this into your text editor
1. Save the file
1. Open the file using a browser (Chrome, Safari, Firefox, Internet Explorer, Edge) 
1. What do you see?

___

Instead of __Hello World__, change your page to display something else.

Now let's create the skeleton of our page to display the data we need.

## CSS

CSS stands for [Cascaded Style Sheets](https://www.google.com/search?ei=oAptXcrsNYXUz7sP3MmioA4&q=what+does+css+stand+for&oq=what+does+css+stand+for&gs_l=psy-ab.3..0i71l8.709049.709354..709468...0.3..0.180.343.0j2......0....1..gws-wiz.oWYX2ZDevY4&ved=0ahUKEwjKvLW7kbLkAhUF6nMBHdykCOQQ4dUDCAo&uact=5)

__HTML__ is used to display elements on a page. __CSS__ is used to make those elements look nice.

For example, here's a button with no CSS styling
```
<button>Click Me</button>
```
![Click Me](https://github.com/gieoon/MakeMyWebsite/blob/master/ClickMe.png "Click Me")


Here's the same button with CSS styling
```
<style>
	button {
    	background-color: red;
        border-radius: 16px;
        padding: 16px;
        border: none;
        color: white;
    }
</style>
<button>Click Me</button>
```
![Click Me (With CSS)](https://github.com/gieoon/MakeMyWebsite/blob/master/ClickMeCSS.png "Click Me (With CSS)")

CSS is also used to align items in the page after they have been written out by HTML.

## Javascript

Browsers run code written in Javascript, and websites run in browsers. That's why websites all end up running javascript.
However browsers are in the client side, meaning that the client interacts with them directly.
More complex web apps also have a server component, which can run in a variety of other languages, such as __C#, .NET, NodeJS, Java, Python__, etc. 

Javascript is code whereas HTML and CSS are not, because javascript is logic based, this is where we first start to see programming concepts like `if(){` or `while(){` 
or
```javascript
var b = true;
if(b){
  alert('Hello World');
}
``` 

We're going to put the above code into out HTML page, but before we put it in, we need to let the html website know that it is javascript code and not any other type of code.
This is done by prepending and postpending `<script>` and `</script>` tags around the javascript code.

___

Now when you run the page you should see an alert that appears at the top of the page.

## API calls

Sometimes other website owners let you call their content, but instead of going to their website and clicking on the content directly, they expose an API endpoint for you to call.
This means that you tell your javascript code to go to a certain address, `https://graph.facebook.com/friends/`, so instead of getting the data through your browser, you can get it through code.

## Your Completed Website


