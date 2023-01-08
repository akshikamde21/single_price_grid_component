# Frontend Mentor - Single price grid component solution

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Links

- Live Site URL: (https://akshikamde21.github.io/single_price_grid_component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow

### What I learned

I learnt how to fetch a google font from web.

```html
<link href="https://fonts.googleapis.com/css2?family=Karla&display=swap" rel="stylesheet">
```
```css
body{
  font-family: 'Karla', sans-serif;
  font-size: 16px;
}
```
I also learnt how CSS grid works.

```css
.grid-container{
  display: grid;
  grid-template-columns: 1fr 1fr;
  grid-template-rows: 1fr 1fr;
  grid-template-areas: 
  'header header' 
  'subscribe whyus';
  align-content: center;
  padding: 5%;
}
```

### Useful resources

I referred this video for CSS grid (https://youtu.be/68O6eOGAGqA)
w3schools is an awesome website to learn CSS. (https://www.w3schools.com/css/default.asp)

