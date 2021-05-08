# Frontend Mentor - Stats preview card component Challenge

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

- [Desktop Screenshot](/images/desktop_preview.png)
- [Mobile Screenshot](/images/mobile.preview.png)

### Links

- Live Site URL: [here](https://arthurgc.github.io/stats-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I had to use a relative unit **ch** for customize width of some texts.

```css
.card_text_p{
  width: 40ch;
}
```
Besides, **SASS** simplifies the use of variables for fonts, font sizes and colors, 

### Useful resources

- [Resource 1](https://stackoverflow.com/questions/36679649/how-to-add-a-color-overlay-to-a-background-image/36679903) - This helped me for combinning a background image url and a background color:

```css
.card_img {
  background-image: linear-gradient(0deg, rgba(170, 92, 219, 0.8), rgba(170, 92, 219, 0.8)), url(/images/image-header-mobile.jpg);
  background-repeat: no-repeat;
  background-size: cover;
  background-blend-mode: multiply;
}
```

- [Resource 2](https://sass-lang.com/guide) - This is an amazing article which helped me finally understand the advantages of using sass.


## Author

- Github - [ArthurGC](https://github.com/ArthurGC)
