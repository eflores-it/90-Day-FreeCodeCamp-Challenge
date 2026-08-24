# Day 3 — Debug a Pet Adoption Page — Fixed Code

## Corrected Code

After identifying the errors in the original code, I corrected the HTML so the image and hyperlinks would work properly.

```html
<h1>Welcome to XYZ Pet Adoption!</h1>
<p>Consider adopting a pet today. We have cats, dogs, rabbits and more.</p>

<h2>See our cats!</h2>
<img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" alt="Two tabby kittens sleeping together on a couch.">

<h2>Adopt a cat!</h2>
<a href="/cats">Visit cats page</a>

<h2>Adopt a dog!</h2>
<a href="/dogs">Visit dogs page</a>
What I Fixed
1. Changed href to src

The <img> element uses the src attribute to specify the location of an image.

<img src="image-url">

The original code incorrectly used href.

2. Changed att to alt

The alt attribute provides a text description of an image. It is useful for accessibility and when an image cannot be displayed.

<img src="image-url" alt="Image description">

The original code incorrectly used att.

3. Fixed the <img> element

The original <img> element was missing the closing >.

Also, <img> is a void element, so it does not need a closing </img> tag.

4. Changed src to href on the links

Anchor (<a>) elements use href to specify where the link should take the user.

<a href="/cats">Visit cats page</a>

The original code incorrectly used src.

What I Learned

This challenge helped me practice identifying common HTML syntax and attribute errors.
I learned the difference between src and href,
how the alt attribute is used for images, and that <img> is a void element that does not require a closing tag.

Time spent: 5 minutes
Topic: HTML Debugging
Project: Debug a Pet Adoption Page
Skills practiced: HTML elements, attributes, images, hyperlinks, debugging

