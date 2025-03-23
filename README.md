# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- See hover and focus states for all interactive elements on the page
- View the optimal layout depending on their device's screen size

### Screenshot

![Video](/assets/videos/Blog-Preview-Card.mp4)

### Links

- Solution URL: [Link](https://github.com/mardimanisha/Blog-preview-card)
- Live Site URL: [Link](https://blog-preview-card-two-phi.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned

During this challenge, I reinforced my knowledge of CSS properties such as box-shadow, hover effects, and responsive design using flexbox and grid. One key takeaway was implementing a smooth hover effect for the card:

```css
.card {
    background-color: white;
    border: 1px solid hsl(0, 0%, 7%);
    border-radius: 12px;
    padding: 20px;
    max-width: 375px;
    box-shadow: 8px 8px 0 hsl(0, 0%, 7%);
    transition: transform 0.3s ease-in-out, box-shadow 0.3s ease-in-out;
}

.card:hover {
    transform: scale(1.05);
    box-shadow: 12px 12px 0 hsl(0, 0%, 7%);
}
```

### Continued development

I aim to further refine my CSS skills, focusing on:

- Improving animations & transitions for a more engaging UI.
- Experimenting with CSS frameworks like Tailwind CSS.

### Useful resources

- [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/CSS) - Helped clarify CSS concepts.
- [CSS Tricks](https://css-tricks.com/) - Great resource for CSS techniques.

## Author

- Frontend Mentor - [@mardimanisha](https://www.frontendmentor.io/profile/mardimanisha)
- Github - [@mardimanisha](https://github.com/mardimanisha)


