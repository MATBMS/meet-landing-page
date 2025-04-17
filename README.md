# Frontend Mentor - Meet landing page solution

This is a solution to the [Meet landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/meet-landing-page-rbTDS6OUR). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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
- See hover states for interactive elements

### Screenshot

![Screenshot preview](./assets/preview.jpg)

### Links

- Solution URL: [Github Repo](https://github.com/MATBMS/meet-landing-page)
- Live Site URL: [Github Page](https://matbms.github.io/meet-landing-page/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid

### What I learned

One of the things I learned while working on this project is how to add a subtle hover effect to images. By using the `transform: scale(1.1)` property in combination with a `transition`, I was able to create a smooth zoom-in effect when the user hovers over an image. This small detail enhances the interactivity and visual appeal of the page.

```css
main img {
  width: 256px;
  height: 256px;
  border-radius: 8px;
  display: block;
  transition: all 0.4s;
}

.gallery-item {
  overflow: hidden;
}

main img:hover {
  transform: scale(1.1);
}
```
