# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- See hover states for interactive elements

### Screenshot

![](./images/screenshot.jpg)

### Links

- Solution URL: [FEM My Solution](https://www.frontendmentor.io/solutions/3column-preview-card-using-normal-html-and-css-aXRP4x-ycY)
- Live Site URL: [You can see my design here.](https://polzak.github.io/portfolio/fem/03-three-column-preview-card/index.html)

## My process

### Built with
- Normal HTML and CSS
- Mobile-first workflow

### What I learned

I was not sure if it would make sense to give some px to a transparent border, and I found [some information](https://stackoverflow.com/questions/17751093/how-to-make-a-transparent-border-using-css) that says it does.

```css
.cta {
  border: 2px solid transparent;
}
```

Form elements do not inherit font by default. If I want them to, [I need to set them to at the beginning of my style sheet.](https://stackoverflow.com/questions/6080413/input-doesnt-inherit-the-font-from-body)

```css
input, select, textarea, button {
  font-family: inherit;
}
```

## Author

- Website - [Sengwan Kim's Portfolio](https://polzak.github.io)
- Frontend Mentor - [@polzak](https://www.frontendmentor.io/profile/polzak)
