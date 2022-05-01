## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)

## Overview

### Screenshot

![](./Screenshot%20cart.png)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

- It was complicated for me when placing the hover for the eye image and for it to change color, but researching I found a solution, I don't know if it is the best way to do it, but it worked for me.

```css
.container .img .cube {
    position: absolute;
    width: 236px;
    height: 236px;
    object-fit: cover;
    border-radius: 10px;
    z-index: 0;
}

.container .img .eye-cube{
    position: relative;
    display: flex;
    justify-content: center;
    align-items: center;
    width: 236px;
    height: 236px;
    object-fit: cover;
    border-radius: 10px;
    background-color: hsl(178, 100%, 50%, 0.5);
    opacity: 0;
    transition: 0.3s;
    cursor: pointer;
}
```

### Continued development

- Me gustaria enfocarme en las propiedades que nos puede ofrecer hover.

### Useful resources

- [resource 1](https://www.youtube.com/watch?v=Z5MoBm99w1Q) - This video helped me understand about the hover effect.
