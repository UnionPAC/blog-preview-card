# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS)
Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

### 🫡 The challenge

Your challenge is to build out this blog preview card and get it looking as close to the design as possible.

Users should be able to:

- See hover and focus states for all interactive elements on the page

### 📸 Screenshot

![Design preview for the Blog preview card coding challenge](./screenshot.png)


### Links

- Live Site URL: [Blog Preview Card](https://unionpac.github.io/blog-preview-card/)

## My process

### Built with

- HTML5
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

One of the ways that this challenge encouraged you to test yourself was:

>The font sizes in this project are slightly smaller in the mobile layout. Find a way to reduce font size for smaller screens without using media queries.

My solution to this was to use the `clamp()` function in my CSS. This was my actually my first experience with it but I found it very useful!

**Basic Syntax**

```
clamp(min, val, max)
```

**Example from my code**
```css
h2 {
  color: var(--black);
  font-size: clamp(1.25rem, 2vw, 1.5rem);
  font-style: normal;
  line-height: 150%; /* 36px */
}
```

### Useful resources

- [Simple solutions to responsive typography](https://www.youtube.com/watch?v=wARbgs5Fmuw) - This video helped me learn best practices for creating responsive typography.


## Author

- Website - [Geoff Jamieson](https://www.geoffjamieson.com/)
- Frontend Mentor - [@UnionPAC](https://www.frontendmentor.io/profile/@UnionPAC)
- LinkedIn - [linkedin/geoffjamieson](https://www.linkedin.com/in/geoffjamieson/)
