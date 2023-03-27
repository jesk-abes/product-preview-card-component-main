# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  <!-- - [Continued development](#continued-development) -->
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](design/desktop-design.jpg)

### Links

- Solution URL: [my solution](https://641c8b67ee28a311330f307c--meek-florentine-236e92.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

```html
<picture class="product_img">
  <source srcset="images/image-product-desktop.jpg" media="(min-width: 600px)">
  <img src="/images/image-product-mobile.jpg" alt="Gabrielle Essence Eau De Parfum">
</picture>
```

```css
  body {
    display: grid;
    place-content: center;
    margin: 1rem;
}
```

<!-- ### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect. -->

### Useful resources

- A Complete Guide to CSS Grid  - [Example resource 1](https://css-tricks.com/snippets/css/complete-guide-grid/) 

## Author

- Frontend Mentor - [@Jesk-ABES](https://www.frontendmentor.io/profile/Jesk-ABES)

