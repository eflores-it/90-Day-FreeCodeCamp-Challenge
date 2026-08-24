# Day 3 — Debug a Pet Adoption Page

## Project Overview

For Day 3 of my 90-Day FreeCodeCamp Challenge, I completed the **Debug a Pet Adoption Page** challenge.

The goal of this project was to identify and fix several errors in the HTML code so that the pet adoption page would display correctly and the links would work properly.

## What I Fixed

* Changed the incorrect `href` attribute on the `<img>` element to `src`.
* Changed the incorrect `att` attribute to `alt` for the image description.
* Removed the unnecessary closing `</img>` tag because `<img>` is a void element.
* Changed the `src` attributes on the `<a>` elements to the correct `href` attribute.
* Fixed the missing `>` at the end of the `<img>` element.

## Corrected Code

```html
<h1>Welcome to XYZ Pet Adoption!</h1>
<p>Consider adopting a pet today. We have cats, dogs, rabbits and more.</p>

<h2>See our cats!</h2>
<img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" alt="Two tabby kittens sleeping together on a couch.">

<h2>Adopt a cat!</h2>
<a href="/cats">Visit cats page</a>

<h2>Adopt a dog!</h2>
<a href="/dogs">Visit dogs page</a>
```

## What I Learned

This project helped me practice identifying common HTML syntax and attribute errors. I learned the difference between `src` and `href`, how the `alt` attribute is used for images, and that `<img>` does not require a closing tag.

## Day 3 Progress

**Time spent:** 5 minutes
**Topic:** HTML Debugging
**Project:** Debug a Pet Adoption Page
**Skills practiced:** HTML elements, attributes, images, hyperlinks, debugging
