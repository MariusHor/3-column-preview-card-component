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

![](./images/Screenshot%202022-04-30%20at%2000-22-38%20Frontend%20Mentor%203-column%20preview%20card%20component.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: (https://mariushor.github.io/3-column-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- BEM

### What I learned

In this project I have learned how to make a transparent background as well as text inside a button/link:

```css
.section__link {
  font-size: 1.4rem;
  font-weight: var(--fw-700);
  text-decoration: none;
  color: #000;
  mix-blend-mode: screen;
  background: var(--clr-very-light-gray);
  border: solid var(--clr-very-light-gray) 0.2rem;
  border-radius: 2.5rem;
  padding: 1.1rem 3rem;
  margin-top: 3rem;
  width: fit-content;
}

.section__link:hover {
  color: #fff;
  border: solid #fff 0.2rem;
  background-color: transparent;
  transition: 0.3s ease-in-out;
}
```
## Author

- Frontend Mentor - (https://www.frontendmentor.io/profile/MariusHor)