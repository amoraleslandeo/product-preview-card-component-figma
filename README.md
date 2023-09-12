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
- [Author](#author)
- [Acknowledgments](#acknowledgments)



## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot
Desktop preview:
![Desktop_preview](./design/chanel_desktop.png)

Desktop preview (with hover button):
![Desktop_with_hover](./design/chanel_hover.png)

Responsive:
![Responsive_preview](./design/chanel_mobile.png)

### Links

- Solution URL: [Repository](https://github.com/amoraleslandeo/product-preview-card-component-figma)
- Live Site URL: [Web page](https://amoraleslandeo.github.io/product-preview-card-component-figma.github.io/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I learned to put an image as a background
```html
<div class="image">
  &nbsp;
</div>
```

Also learned this sequence of attributes to adapted an image inside a background 
```css
.image {
    width: 300px;
    height: 450px;
    background-image: url('../images/image-product-desktop.jpg');
    background-size: contain;
    background-repeat: no-repeat;
}
```

I learned to use the 'overflow' attribute to adapt the images to a specific measurement of a background
```css
overflow: hidden;
```

And i learned this attribute to calc any math operation
```css
width: calc(300px - 31.5px - 31.5px);
```

## Author

- Website - [Alejandro Morales Landeo](https://amoraleslandeo.github.io/personal-page.github.io/)
- Frontend Mentor - [@amoraleslandeo](https://www.frontendmentor.io/profile/amoraleslandeo)


## Acknowledgments

I wanna say thanks to my daily support [Roberto](https://github.com/RobertoSilvaZ) 🙌😉 who has become my developer Mentor and guide through this process that is just beggining.

