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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![Preview for the Product preview card component coding challenge](./project-screenshot.png)

### Links

- Solution URL: [https://www.frontendmentor.io/solutions/responsive-product-card-component-using-css-grid-and-flexbox-zFWNvEtM36](https://www.frontendmentor.io/solutions/responsive-product-card-component-using-css-grid-and-flexbox-zFWNvEtM36)
- Live Site URL: [https://nesc11.github.io/product-preview-card-component/](https://nesc11.github.io/product-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- Media queries

### What I learned

The project helped me review basics concepts of responsive layout, some of the techniques I used:

- Media queries for larger screens starting from 768px to change the layout from single-column to two-column.

```css
@media screen and (min-width: 48em) {
  .card {
    display: grid;
    grid-template-columns: 1fr 1fr;
  }
}
```

- Custom properties to easily reference the project's base styles.

```css
:root {
  /* Font family */
  --ff-sans: "Montserrat", sans-serif;
  --ff-serif: "Fraunces", serif;

  /* Font sizes */
  --fs-xs: 0.75rem;
}
```

Particularly I didn't learn anything new since I have applied this in other projects.

## Author

- Website - [Nestor](https://nestorr.netlify.app/)
- Frontend Mentor - [@nesc11](https://www.frontendmentor.io/profile/nesc11)
