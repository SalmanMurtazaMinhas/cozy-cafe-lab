<h1>
  <span class="headline">Cozy Cafe Lab</span>
  <span class="subhead">Exercise</span>
</h1>

## Introduction

Before diving into the exercise, take a moment to inspect the provided starter code. You'll find that the HTML has already been provided for you. Your primary focus will be on using JavaScript in the `app.js` file to make modifications to the cafe web page. 

Before you start coding, open the `index.html` file in your browser to familiarize yourself with the web page you'll be working with.

## Requirements

- Complete Parts 1 - 7.

## Accessing DOM Elements (Querying)

Let's start with some basic query selection tasks.

### Part 1

The cafe's title is a bit too long. Select the `#main-title` id element and change the text to “Welcome to the Cozy Cafe”.  Let's also improve our page's appearance by changing the `text-align` to `center` on the title as well.


### Part 2

Select the provided `button` with the text "Change Background Color" using JavaScript.
When the button is clicked, change the background color of the `body` to a soothing pastel shade of your choice. (If you can't think of a color, `bisque`, `lightsteelblue`, and `pink` are good choices.)  

### Part 3

Select the `<p>` element which is meant to hold the quote of the day.  Update it's content so that it displays a quote of your choice (or use this classic: "Life happens, coffee helps.").

### Part 4

Select _all_ elements with the class `highlight-title` and change their `font-style` to `italic`. Remember, you might need to iterate through a collection of elements.

## Creating New DOM Elements

### Part 5

Let's add a new item to the **Past Menu Items** list. Create a new `<li>` element, set the text to “Rose Cake”, and append it to the list.

### Part 6

Select the list of **Cafe Specialties** and add a list item.  Be sure to add content to your newly created `<li></li>` tags (maybe Karak Tea is on offer now?).

### Part 7

Create a new blog post for a recent cafe event. You will need to create a new `<div>` element with the class `.blog-post`, a new `<h3>` with a relevant event title (e.g., “Karak Tea Tasting Event”), and a new `<p>` with some text describing the event. Make sure the new post matches the style and structure of the other blog posts. Think carefully about the order of element creation and appending.

### Part 8 - 🚀 Level Up

It turns out the cafe never served the item “Fish Tacos”. Select the **Past Menu Items** list and remove “Fish Tacos” from it. _Hint: You'll have to cache both the "Fish Tacos" list item element as well as it's parent, then use the [`removeChild()`](https://developer.mozilla.org/en-US/docs/Web/API/Node/removeChild) method on the parent to remove the cached `<li>` element._
