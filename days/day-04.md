# Day 4 — Link Element, External CSS & Favicons

## Topics

* The `<link>` Element in HTML
* Linking to External Stylesheets
* Favicons

## What I Learned

Today I learned about the HTML `<link>` element and how it is used to connect an HTML document to external resources.

One of the most common uses of the `<link>` element is connecting an HTML page to an external CSS stylesheet. This allows the HTML and CSS to be kept in separate files, making the code easier to organize and maintain.

A typical example is:

```html
<link rel="stylesheet" href="styles.css">
```

### Key Concepts

* The `<link>` element is placed inside the `<head>` section of an HTML document.
* The `rel` attribute describes the relationship between the current document and the linked resource.
* `rel="stylesheet"` tells the browser that the linked file is a CSS stylesheet.
* The `href` attribute specifies the location of the external resource.
* External stylesheets allow CSS to be separated from HTML.

## Favicons

I also learned about **favicons**, which was one of the more interesting things I learned today.

A favicon, short for **favorite icon**, is a small icon typically displayed in the browser tab next to the website title. Many websites use a favicon to display their brand or logo.

A favicon can also be added using the `<link>` element:

```html
<link rel="icon" href="favicon.ico">
```

This showed me that the `<link>` element is not only useful for connecting CSS files but can also be used to connect other resources to a webpage.

## Practice

I read the FreeCodeCamp lessons about the role of the `<link>` element in HTML, external stylesheets, and favicons.

I completed the accompanying quiz to test my understanding of the material.

## Takeaway

Today I learned how the `<link>` element connects HTML documents to external resources such as CSS stylesheets and favicons.

The favicon section was especially interesting because I had seen these small icons in browser tabs before but didn't know what they were called or how websites added them.

## Progress

**Day 4 completed.**

Continuing the 90-day challenge and building consistency with HTML and web development fundamentals.
