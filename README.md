# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Extra challenges](#extra-challenges)
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

- View the optimal layout for the site depending on their device's screen size.
- See hover states for all interactive elements on the page.

### Extra challenges

As a bonus I want to achieve the following extra challenges:

- The page must be accessible according to WCAG 2.1 standards, things like color contrast and clear element focus.
- I want to add minimal (hover) animations to the page.

### Screenshot



### Links

- [Solution URL](https://www.frontendmentor.io/solutions/astro-wcag-accessibility-css-flexbox-and-css-animations-OQei0e5Kj)
- [Live Site URL](https://markteekman.github.io/nft-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- WCAG 2.1 best practices
- CSS Animations
- [Astro](https://astro.build) - Astro Static Site Generator
- [Accessible Astro Starter](https://github.com/markteekman/accessible-astro-starter) - My own starter template for Astro

### What I learned

- I haven't used the `::before` pseudo element in a long time to create an overlay hover effect, so it was nice doing that one again:

```scss
&::before {
  content: '';
  display: block;
  opacity: 0;
  z-index: -1;
  width: 100%;
  height: 100%;
  background-color: hsl(178, 100%, 50%, 0.4);
  background-image: url('../assets/icon-view.svg');
  background-repeat: no-repeat;
  background-position: center;
  border-radius: 0.5rem;
  position: absolute;
  transition: all 0.3s ease-in-out;
}
```

### Continued development

- Nothing at the moment.

### Useful resources

- Nothing at the moment.

## Author

- [Personal Website](https://www.markteekman.nl)
- [Frontend Mentor Profile](https://www.frontendmentor.io/profile/markteekman)
- [LinkedIn Page](https://nl.linkedin.com/in/markteekman)
- [GitHub Projects](https://github.com/markteekman)
- [NPM Packages](https://www.npmjs.com/~markteekman)
- [CodePen Creations](https://codepen.io/markteekman)
