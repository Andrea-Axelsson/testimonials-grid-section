# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![Project full size](fullsize-screenshot.png)
![max-width: 1000px](medium-screenshot.png)
![max-width: 600px](small-screenshot.png)

### Links

- Solution URL: [Netlify](https://voluble-cranachan-59cd24.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I recently took on the challenge of creating a testimonials grid using CSS as part of a Frontend Mentor project. This was a deliberate effort on my part to hone my skills in grid layout, especially since I've mostly been immersed in flexbox until now.

I used to view grid as a bit confusing and messy, favoring flexbox for its perceived ease and the sense of control it gave me over layouts. However, delving into this challenge completely shifted my perspective, making me appreciate grid more than ever. One significant realization was that it leads to cleaner HTML code, reducing the need for excessive containers.

I'm particularly proud of how I employed grid-template-areas in planning the layout visually, sidestepping the need to micromanage card widths and heights. This not only simplified the design process but also made handling media queries a breeze.

```css
.card-container {
  width: 90%;
  max-width: 1300px;
  display: grid;
  grid-gap: 24px;
  grid-template-columns: 1fr 1fr 1fr 1fr;
  grid-template-areas:
    "purple purple grey white1"
    "white2 blue blue white1";
}
```

### Continued development

In my attempt to achieve a responsive layout, I played around with grid-template-columns: repeat(auto-fill, minmax(200px, 1fr)); as an alternative to fixing the number of columns. Although I hoped to attain full responsiveness without relying on media queries using auto-fill, I encountered some challenges. I'm intrigued by the potential of auto-fill for responsive design and plan to explore it further in future projects.

### Useful resources

- [Scrimba Grid course](https://scrimba.com/learn/frontend) - I gained valuable insights from the responsive design course on Scrimba, where instructor Kevin Powell delves deep into the enchanting realm of grids.

## Author

- GitHub - [Andrea Axelsson](https://github.com/Andrea-Axelsson)
- LinkedIn - [Andrea Axelsson](https://www.linkedin.com/in/axelsson-andrea/)
