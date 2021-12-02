# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - NFT preview card component solution](#frontend-mentor---nft-preview-card-component-solution)
  - [Table of contents](#table-of-contents)
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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![My version](desktop-design.png)

### Links

- Solution URL: [Frontend Mentor](https://www.frontendmentor.io/solutions/nfs-card-solution-H3fmSToGb)
- Repository URL: [GitHub](https://github.com/antoines21/frontendmentor/tree/main/nft-preview-card)
- Live Site URL: [GitHub Pages](https://antoines21.github.io/frontendmentor/nft-preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid

### What I learned

```css
.image::before {
    content: "";
    position: absolute;
    height: 100%;
    width: 100%;
    transition: all 0.5s;
    opacity: 0;
    background: url(images/icon-view.svg);
    background-repeat: no-repeat;
    background-position: center;

}
```

### Continued development

I would love to continue learning flexbox and pseudo-elements.

### Useful resources

- [How to make in CSS an overlay over an image? | Stack Overflow](https://stackoverflow.com/questions/21086385/how-to-make-in-css-an-overlay-over-an-image) - This site helped me with the CSS hover functions.

## Author

- Frontend Mentor - [@antoines21](https://www.frontendmentor.io/profile/antoines21)
- GitHub - [@antoines21](https://github.com/antoines21)