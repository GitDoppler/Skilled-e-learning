# Frontend Mentor - Skilled e-learning landing page solution

This is a solution to the [Skilled e-learning landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/skilled-elearning-landing-page-S1ObDrZ8q). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./screenshot.png)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

The main things which I have learned from this project are :

  - The importance of code organization and structure ( Messy code can very quickly destroy a project )

  - The usefulness of utility classes ( An initial investment which pays off later in the project )

  - Flexbox vs Grid ( Initially I didnt think grid was very useful but this project proved me wrong. Although I didn't use grid, a lot of pain could have been released if I did. )

  - Overflow and the combination of position relative ( on parent ) and position aboslute ( on children ).

In-depth explanation of 4) :
  The combination of relative and absolute was used to position the hero image in its right spot. This was the only idea I had in my mind at that time so I did what any would do, follow its own instincts. Initially I was a bit skeptic as position absolute is considered by many a thing which you should not use but this skepticisim was quickly aleviated by how good the positioning of the image looked.

  Afterwards, another problem arose. The hero-image ( which now was in the right place) was overflowing ( duuuh, I was pushing out of the page using top:-...%, should've expected this ) so I quickly realised that if there was a way to hide the overflow, my problem would be solved. And there was a way : " overflow-x: hidden ".

  In the end, this question still lingers inside my mind :
    Was this the right approach ? Is there another way to position the image without causing overflow while making it look exactly like the figma design ?
  
### Continued development

What I wish to do in my upcoming projects is : 
  - Structure my code and create a mental code-map before I delve into the actual writing.
  - Focus a lot more on writing clean, easy-to-read code ( make my containers easier to understand ).
  - Familiazrize myself with utility classes.

## Author

- Frontend Mentor - [@GitDoppler](https://www.frontendmentor.io/profile/GitDoppler)

## Acknowledgments

- Ahmed Bayoumi
- Kevin Powell
