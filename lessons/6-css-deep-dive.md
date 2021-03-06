---
layout: post
title: CSS Deep Dive
lesson_num: 06
---

## Updated Starter HTML

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>PAGE TITLE</title> <!-- DON'T FORGET THE TITLE -->
    <link rel="stylesheet" href="style.css">
  </head>
  <body>
  <!-- PLACE ALL OF YOUR PAGE CONTENT BELOW HERE -->

  <h1>This is my heading</h1>

  <p>This is a paragraph</p>

  <!-- AND ABOVE HERE -->
  </body>
</html>
```

## In Class Demo

[Download these files](/lesson_files/ornette.zip) for today's demo.

### After Styling the Ornette Page Together

[Download this CSS file](/lesson_files/ornette2/style2.css) and place it in your Ornette directory. Delete the `<img>` file in the markup and change the reference in your HTML to point to the new CSS file. Notice how the (nearly) identical markup can be styled in a dramatically different way?

## Normalize.css

[Normalize.css](http://necolas.github.io/normalize.css/) is a file that "normalizes" the base appearance of your site across browsers. To use it:

1. [Download the file](http://necolas.github.io/normalize.css/3.0.0/normalize.css) into your project's directory
2. Link to the CSS file *before* your custom styles (shown below)

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>PAGE TITLE</title>
    <link rel="stylesheet" href="normalize.css"> <!-- normalize.css is loaded before our styles -->
    <link rel="stylesheet" href="style.css"> <!-- our custom style sheet -->
  </head>
  <body>
    .
    .
    .
  </body>
</html>
```

## In-Class Project

Add a stylesheet to your Discography project. Consider the color, type, and layout based on what we have learned about CSS so far.
