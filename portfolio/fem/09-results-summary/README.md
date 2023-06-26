# Frontend Mentor - Results summary component solution

This is a solution to the [Results summary component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

![](./screenshot.jpg)

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
- [React](https://reactjs.org/) - JS library
- [Next.js](https://nextjs.org/) - React framework
- [Styled Components](https://styled-components.com/) - For styles

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

- At first, the upper results box's box-shadow was overlapped by the lower summary box. When I applied `position: relative;` to the upper box, the box-shadow was not overlapped any more and appeared over the lower box. I think the `position: relative;` made another context for the upper box and the box shadow was able to be displayed. `z-index` also could work on a box once you applied `position: relative` to it.

- how to read a JSON file in JavaScript with import statement:

```html
<html lang="en">
    // ...
    <body>
        <script type="module" src="./index.js"></script>
    </body>
</html>
```
```js
import data from './data.json' assert { type: 'json' };
console.log(data);
```

Note: if we run this locally – then we would get the CORS error. (Instead, use local server to open the index.html file.)

- It's good to avoid setting fixed `padding-left` or `padding-right` values in an element that belongs to a box: you will not be able to set your box width using percentage values due to their fixed width.


### Useful resources

- [position](https://developer.mozilla.org/en-US/docs/Web/CSS/position)
- [textContent property](https://developer.mozilla.org/en-US/docs/Web/API/Node/textContent)
- [How to Read a JSON file in JavaScript with the Import Statement](https://www.freecodecamp.org/news/how-to-read-json-file-in-javascript/)


## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)




## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**
