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
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot
#### MOBILE LAYOUT:
![](./screenshots/MOBILE.jpg)

#### TABLET LAYOUT:
![](./screenshots/TABLET.jpg)

#### DESKTOP LAYOUT:
![](./screenshots/DESKTOP.jpg)

### Links

- Solution URL: [https://www.frontendmentor.io/solutions/testimonials-grid-section-3-layouts-made-with-help-of-sass-mEmztyvcH]
- Live Site URL: [https://frontendmentor-testimonialsgridsection.netlify.app/]

## My process

### Built with

- Semantic HTML5 markup
- CSS
- CSS Grid
- Mobile-first workflow
- SASS
- GULP

### What I learned
This challenge was more difficult than I was expected, because I had doubts about the display grid behaviour, however could fix the mistakes.
En another way, I decided to make three layouts, with breakpoints in 768px, and 1300px.
To work with CSS used SASS, in this point was hard because I didn't know a lot about SASS and I don't have a standar to write CSS.

In this project I learned a little bit about Gulp, too, I used to compiled the SASS files. To make this I have to used the following code in the gulpfile:

```js
const {series, src, dest, watch} = require('gulp'); 
const sass = require('gulp-sass');

function css(done){
    return src('sass/app.scss')
        .pipe(sass())
        .pipe( dest('./css'))
}

exports.css = css;
```

### Continued development

How to apply correctly GRID, for moments I fell with doubts about its behaviour.
Continue learning how to use SASS and GULP
Learn more about standars to declared CSS

## Author
<h4>Gabo Pereyra</h4>

- GitHub - [@gabopereyra](https://github.com/gabopereyra)
- Frontend Mentor - [@gabopereyra](https://www.frontendmentor.io/profile/gabopereyra)
- Twitter - [@gabs_pereyra](https://github.com/gabopereyra)
