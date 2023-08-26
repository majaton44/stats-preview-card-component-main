# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![screenshot of my solution](screenshot.png)

### Links

- [Solution](https://your-solution-url.com)
- [Live version](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

```css
/* Image Overlay */
.card-img-box {
  content: "";
  position: relative;
  width: 100%;
  height: 100%;
  background-color: var(--clr-primary-400);
}

.card-img-box::before {
  content: "";
  background-image: url(images/image-header-desktop.jpg);
  background-size: cover;
  background-position: top right;
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  mix-blend-mode: multiply;
  opacity: 0.75;
}
```
