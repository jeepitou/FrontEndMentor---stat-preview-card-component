# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- View the optimal layout depending on their device's screen size

### Screenshot

![](./images/printscreen.png)

### Links

- Solution URL: [Add solution URL here](https://github.com/jeepitou/FrontEndMentor---stat-preview-card-component)
- Live Site URL: [Add live site URL here](https://jeepitou.github.io/FrontEndMentor---stat-preview-card-component/)

## My process
I started with the desktop layout. I quickly managed to get a very similar layout, the biggest challenge was to add a color filter to the image (which I'm still not really satistied with...). I finally tweaked all the margin and font size to try to recreate as best as possible.
The real challenge for me was working on the mobile layout since I never worked on that before. I quickly ran into problems because of class attributes that were from the desktop layout.
I decided to have general CSS classes for font and color, and do separate one for mobile/desktop to manage the sizing/margin/etc. Don't know if that is usual practice but I think my solution works pretty well.
### Built with

- Semantic HTML5 markup
- CSS custom properties

### What I learned

- I learned how to do separate layout for mobile and desktop. Didn't know we could have separate CSS classes for mobile/desktop.
- I also learned about border box, which helped me deal with padding making my element bigger than their parents.

### Continued development

I'm currently doing a bootcamp on Udemy, and doing this exercice really made me work hard. I need to work on layout. There are some things I don't understand yet (like why can't 3 elements with width of 33% fit on one line).

### Useful resources

- [Media Queries](https://www.w3schools.com/css/css_rwd_mediaqueries.asp) - This helped me to understand how to manage the CSS on different platform.
- [Border box](https://stackoverflow.com/questions/5175268/keep-padding-from-making-the-element-bigger) - I learned about border box on Stack Overflow.

## Author

- Frontend Mentor - [@jeepitou](https://www.frontendmentor.io/profile/jeepitou)
