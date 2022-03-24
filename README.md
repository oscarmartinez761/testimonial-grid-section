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
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [Solution](https://www.frontendmentor.io/solutions/testimonial-section-using-css-grid-rJGSBrKG5)
- Live Site URL: [Live Site](https://oscarmartinez761.github.io/testimonial-grid-section/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

In this project I learned a little bit about CSS Grid layout using grid templates areas. I'm still new to this and I found this method very useful:

```css
.testimonials-wrapper {
        grid-template-columns: repeat(4, 1fr);
       grid-template-areas: 
       "item-1 item-1 item-2 item-5"
       "item-3 item-4 item-4 item-5 ";
    }
```


### Useful resources

- [MDN - Grid Template Areas](https://developer.mozilla.org/es/docs/Web/CSS/grid-template-areas) - This article helped me to understand how to set up grid areas and how they work. 
- [Learn CSS Grid the easy way by Kevin Powell](https://www.youtube.com/watch?v=rg7Fvvl3taU&ab_channel=KevinPowell) 

## Author


- Frontend Mentor - [@oscarmartinez761](https://www.frontendmentor.io/profile/oscarmartinez761)
- Twitter - [@OscarOGMG](https://twitter.com/OscarOGMG)


