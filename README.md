# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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
- See hover states for interactive elements

### Screenshot

![](/images/nft-screenshot.png)

### Links

- Solution URL: [NFT Preview Card Solution](https://scintillating-kitten-11a80f.netlify.app/)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Grid
- Bootstrap

### What I learned

One new concept that I learned is this project was the CSS property border-width, which was very helpful in creating the desired effect. This was a property I have never used or heard of before this project.

```css
hr {
  color: hsl(215, 51%, 70%);
  font-weight: 600;
  border-width: 3px;
  border-radius: 100px;
}
```

Additionally, I learned how to override responsive grids. I used this concept on a content that was text-aligned differently, but needed to display inline for mobile viewing. See code below:

```css
@media (max-width: 768px) {
  .col-md-6 {
    max-width: 50%;
  }
}
```

### Useful resources

- [MDN web docs\_](https://developer.mozilla.org/en-US/docs/Web/CSS/border-width) - This helped me with achieving the desire look for the horizontal line.

## Author

- Frontend Mentor - [@L-itslocked](https://www.frontendmentor.io/profile/L-itslocked)
- CodePen - [@Itslocked](https://codepen.io/Itslocked)
- LinkedIn - [doyonlaura] (https://www.linkedin.com/in/doyonlaura)
