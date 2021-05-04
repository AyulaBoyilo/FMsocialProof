# Frontend Mentor - Social proof section solution

This is a solution to the [Social proof section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-proof-section-6e0qTv_bA). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [How I did it](#how-i-did-it)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](./design/desktop-design.jpg)

### Links

- Solution URL: [GitHub repository](https://github.com/AyulaBoyilo/FMsocialProof/)
- Live Site URL: [GitHub Pages](https://ayulaboyilo.github.io/FMsocialProof/)

## My process

### Built with

- Semantic HTML5 markup
- SCSS
- Flexbox
- Mobile-first workflow

### How I did it

I used pseudo selectors and transform to stagger the cards and ratings left and right from the central alignment. That way the elements retained more responsiveness relative to page width.

```scss
.rating,
.card {
  &:first-child {
    transform: translateX(-50px);
  }
  &:last-child {
    transform: translateX(50px);
  }
}
```

## Author

- Ayula Boyilo
