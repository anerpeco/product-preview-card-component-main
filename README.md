# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./screenshot/screenshotDesktop.jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

This time I learned how to use the <picture> HTML element.

```html
<picture>
  <source
    media="(min-width: 550px)"
    srcset="images/image-product-desktop.jpg"
  />
  <img
    src="images/image-product-mobile.jpg"
    alt="Pictur of Gabrielle Essence Eau De Parfum"
    width="100%"
    height="100%"
  />
</picture>
```

## Author

- Frontend Mentor - [@anerpeco](https://www.frontendmentor.io/profile/anerpeco)
