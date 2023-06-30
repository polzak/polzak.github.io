# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](./images/screenshot.jpg)


### Links

- Solution URL: [My solution](#)
- Live Site URL: [My design](https://polzak.github.io/portfolio/fem/12-four-card-feature-section/index.html)

## My process

### Built with

- Flexbox
- Mobile-first workflow

### What I learned

Use `background-image`, `background-size`, `width` and `height` to modify an image on pseudo elements. 

```css
.card::after {
  background-image: url('/images/pdf.png');
  background-size: 10px 20px; /* can change the size of the bg image */
  display: inline-block; /* or block or flex or inline-flex */
  width: 10px; /* the size of the pseudo element itself */
  height: 20px; /* the size of the pseudo element itself */
  content:"";
}
```

### Useful resources

- [Change the size of pseudo elements](https://stackoverflow.com/questions/8977957/can-i-change-the-height-of-an-image-in-css-before-after-pseudo-elements)

## Author

- Website - [Seungwan Kim's Portfolio](https://polzak.github.io)
- Frontend Mentor - [@polzak](https://www.frontendmentor.io/profile/polzak)
