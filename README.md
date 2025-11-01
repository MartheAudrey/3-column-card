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
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

### Screenshot

![3 Columns card component](./3-column%20preview%20card%20component.png)

### Links

- Solution URL: [Git repository](https://github.com/MartheAudrey/3-column-card.git)
- Live Site URL: [Card component](https://3-column-card-smoky.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

I learned how to center a container in the body with place-content property. The key is to define give to html and body elements an height of 100%.

```css
html,
body{
    height: 100%;
}

body{
    background-color: var(--clr-gray100);
    font-family: "Lexend Deca", sans-serif;
    display: grid;
    place-content: center;
    padding: 1rem;
    gap: 2rem;
    color: var(--txt-clr);
    line-height: 1.5;
}
```

### Continued development

In future projects I would like to work on accessibility, grid and flexbox laayouts, svg icons and many more.

## Author

- Frontend Mentor - [MartheA_19](https://www.frontendmentor.io/profile/MartheAudrey)


