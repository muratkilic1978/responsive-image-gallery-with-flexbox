# CSS Flexbox Layout Module
Before the Flexbox Layout module, there were four layout modes:

* Block, for sections in a webpage
* Inline, for text
* Table, for two-dimensional table data
* Positioned, for explicit position of an element

The Flexible Box Layout Module, makes it easier to design flexible responsive layout structure without using float or positioning.

## A Complete Guide to Flexbox
For more infor about Flexbox settings open this website [CSS-Tricks:](https://css-tricks.com/snippets/css/a-guide-to-flexbox/). This is a guide that explains everything about flexbox, focusing on all the different possible properties for the parent element (the flex container) and the child elements (the flex items). 

# Exercise

In this video-exercise - you will learn how to create a responsive image gallery using flexbox using the CSS property **display: flex** container with images.

## Step - 1
## Download/clone this [repo](https://github.com/muratkilic1978/responsive-image-gallery-with-flexbox) to your machine

## Step - 2
Open the project folder that you downloaded above with your code-editor and click on the **index.html** file. Next open the **index.html** file in your browser (Chrome) to see how the webpage looks like.

## Step - 3
Scroll to the top of the **index.html** and enter all CSS-code in this exercise internally.
Go and create a selector that fetch the image-grid class.

## Step - 4
Inside the **image-grid** class do following things:
* Set the **display** property to **flex**
* Set the **width** of the container to **90%**
* Set the **margin-top** and **margin-bottom** to **0** and **margin-left** and **margin-right** to **auto**
* Next create a selector that fetch the **grid-image** class and do following things:
* Set the **display** property to **block**
* Finally open the index.html in your browser and notice the changes you see.

## Step - 5
Inside the **image-grid** class do following things:
* Set the **flex-wrap** property to **wrap**
* Finally open the index.html in your browser and notice the changes you see

## Step - 6
Inside the **grid-image** class do following things:
* Set the **flex-basis** property to **100%**
* Finally open the index.html in your browser and notice the changes you see

## Step - 7
Next place the cursor after the latest css-selector and after the ending curly-bracket `}`. Next create 4 media queries for following screen sizes with following properties and values:
* If screen size is more than **640px** wide - fetch the **image-grid** class and set the **flex-basis** to **50%**
* If screen size is more than **960px** wide fetch the **image-grid** class and set the **flex-basis** to **33.333%**
* If screen size is more than **1024px** wide fetch the **image-grid** class and set the **flex-basis** to **25%**
* If screen size is more than **1280px** wide fetch the **image-grid** class and set the **flex-basis** to **12.5%**

### Here is an example of a Media Query for screen size more than 600px wide

`@media only screen and (min-width: 640px) {` <br>
  `body {` <br>
    `background-color: lightblue;` <br>
  `}` <br>
`}`

* Finally open the index.html in your browser and notice the changes you see

## Step - 8
Inside the **grid-image** class do following things:
* Set the **padding** property to **10px**
* Finally open the index.html in your browser and notice the changes you see

## Step - 9
Inside the **image-grid** class do following things:
* Set the **justify-content** property to **center**
* Finally open the index.html in your browser and notice the changes you see
