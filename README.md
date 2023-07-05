# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![Mobile view](https://i.imgur.com/lb8yTGj.png)
![Desktop view](https://i.imgur.com/vzNsVsl.png)

### Links

- [GitHub Repo](https://github.com/rjcrowderschaefer/fm-product-preview-card-component)
- [Live Site URL](https://rjcrowderschaefer.github.io/fm-product-preview-card-component/)

## My process

I continued to practice the mobile-first development workflow with this project, focusing on building the mobile layout first and then moving to the desktop layout using the specific breakpoints provided. I also focused on using semantic HTML and avoided using div tags where possible. I worked with CSS to align with the design mock ups as closely as possible and implemented some new CSS rules such as letter-spacing and line-height.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

This project allowed me to further develop my approach to semantic HTML and how the code is organized to be as efficient and DRY as possible. I spent the main part of this project learning how to best implement CSS Grid for the desktop view to ensure the content is positioned correctly and responsive. I'm now more familiar with how CSS Grid can be used in the building process and I look forward to implementing this layout system for future and more complex projects.

```html
<h1>Some code snipets that I'm proud of:</h1>
```
```css
.grid-wrapper {
        display: grid;
        grid-template-columns: 1fr 1fr;
        grid-template-rows: repeat(4fr);
        grid-column-gap: 0px;
        grid-row-gap: 0px;
        grid-template-areas:
            "grid-div-1 grid-div-2"
            "grid-div-3 grid-div-3"
            ". ."
    }

    .grid-div-1 {
        grid-area: grid-div-1;
    }

    .grid-div-2 {
        grid-area: grid-div-2;
    }

    .grid-div-3 {
        grid-area: grid-div-3;
    }
```
```css
.eyebrow {
    font-family: 'Montserrat';
    font-weight: 400;
    font-size: .7rem;
    margin: 30px 0 10px 25px;
    text-transform: uppercase;
    letter-spacing: .35rem;
    color: #71747d;
}
```
### Continued development

Further exploration of CSS Grid and how to best organize and display HTML efficiently while ensuring the best possible user experience.

## Author

- LinkedIn - [RJ Crowder-Schaefer](https://www.linkedin.com/in/rjcrowderschaefer/)
- Frontend Mentor - [@rjcrowderschaefer](https://www.frontendmentor.io/profile/rjcrowderschaefer)
- GitHub - [@rjcrowderschaefer](https://github.com/rjcrowderschaefer)
