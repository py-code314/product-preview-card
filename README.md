# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - Product preview card component solution](#frontend-mentor---product-preview-card-component-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [Screenshots](#screenshots)
      - [Mobile view:](#mobile-view)
      - [Desktop view:](#desktop-view)
    - [Links](#links)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)


## Overview

A small project to build a product preview card component for a perfume bottle. The card has an image, a title, a description, a price and an 'Add to cart' button. The button is interactive and has a hover and focus states. Card is designed in the way that when seen on a mobile device, it is displayed in column layout and when seen on a desktop device, the card is displayed in row layout.


### Screenshots

#### Mobile view:
![](./images/screenshot-mobile.png)

#### Desktop view:
![](./images/screenshot-desktop.png)


### Links

- Live Site URL: [https://py-code314.github.io/product-preview-card/](https://py-code314.github.io/product-preview-card/)
 

### Built with

- Semantic HTML5 markup
- Sass
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned

- I learned Sass basics and how to use it in CSS.
- Found out that it takes less code to place two equal width containers on the same row using CSS Grid.
- Did some research on how to make an image occupy the full width and height of its container:
  ```
  img-container {
    display: grid;
    place-items: center;
  }
  img {
    width: 100%;
    height: 100%;
    object-fit: cover;
  }
  ```


