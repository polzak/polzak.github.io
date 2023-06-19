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
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./images/screenshot.jpg)

### Links

- Solution URL: [My solution](https://www.frontendmentor.io/solutions/product-preview-card-responsive-oxWSHqbV_H)
- Live Site URL: [What I created](https://polzak.github.io/portfolio/fem/04-product-preview-card/index.html)

## My process

### Built with

- Pure HTML and CSS
- Mobile-first workflow

### What I learned

You can switch between different images using HTML picture tag.

```html
 <picture>
  <source media="(min-width:650px)" srcset="img_pink_flowers.jpg">
  <source media="(min-width:465px)" srcset="img_white_flower.jpg">
  <img src="img_orange_flowers.jpg" alt="Flowers">
</picture> 
```

There is an extra gap just below an image: an image sits on baseline by default, it makes the extra gap.
You can make its vertical-align middle or bottom (instead of baseline), or make its display block.

```css
img {
  vertical-align: bottom;  /* display: block; */
}
```

I learned about css filter drop-shadow() function. Browsers support it around 96%, so you can use it as you want.

```css
img {
  filter: drop-shadow(0px 4px 4px rgba(0, 0, 0, 0.25));
}
```

You don't need to use HTML semantic elements when you just need some styling.

### Useful resources

- [extra gap below an image problem](https://stackoverflow.com/questions/5804256/image-inside-div-has-extra-space-below-the-image)
- [flexbox half-half layout](https://stackoverflow.com/questions/33393544/how-can-i-make-a-half-half-layout-with-some-text-using-display-flex) It is important to specify the flex-basis property.
- [css filter drop-shadow() function](https://developer.mozilla.org/en-US/docs/Web/CSS/filter-function/drop-shadow) - This function is somewhat similar to the box-shadow property. The box-shadow property creates a rectangular shadow behind an element's entire box, while the drop-shadow() filter function creates a shadow that conforms to the shape (alpha channel) of the image itself.

## Author

- Website - [Seungwan Kim's Portfolio](https://polzak.github.io)
- Frontend Mentor - [@polzak](https://www.frontendmentor.io/profile/polzak)
