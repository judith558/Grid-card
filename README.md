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
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

(./desktop-design.jpg.jpg)

### Links

- Solution URL: [solution URL here](https://github.com/judith558/Grid-card)
- Live Site URL: [live site URL here](https://grid-card-gold.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow

### What I learned

This project was a great opportunity to practice CSS Grid layout. I learned how to create complex grid layouts that adapt to different screen sizes using media queries.

One of the key learnings was using `grid-template-columns` and `grid-template-rows` to define the grid structure, and `grid-column` and `grid-row` properties to position individual grid items across multiple columns and rows.

```css
/* Desktop grid layout */
.box {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  grid-template-rows: auto auto;
}

.daniel {
  grid-column: span 2; /* Spans 2 columns */
}

.kira {
  grid-column: 4;
  grid-row: 1 / span 2; /* Spans 2 rows */
}
```

I also practiced using CSS custom properties (variables) for consistent theming and easier maintenance.

### Continued development

I want to continue improving my CSS Grid skills by working on more complex layouts. I'd also like to explore CSS Grid subgrid for even more advanced layouts. Additionally, I'm interested in learning more about CSS architecture and methodologies like BEM or CSS-in-JS for larger projects.

### Useful resources

- [CSS Grid Guide](https://css-tricks.com/snippets/css/complete-guide-grid/) - Comprehensive guide to CSS Grid by CSS-Tricks
- [Grid by Example](https://gridbyexample.com/) - Great resource for learning CSS Grid with practical examples
- [Frontend Mentor](https://www.frontendmentor.io/) - Excellent platform for practicing front-end development with real-world projects

## Author

- Website - [Your Name](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

## Acknowledgments

Thanks to Frontend Mentor for providing this challenging and educational project. The community and resources available through Frontend Mentor are invaluable for front-end developers looking to improve their skills.
