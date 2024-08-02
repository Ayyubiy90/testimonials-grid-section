# Frontend Mentor - Testimonials Grid Section Solution 🚀

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of Contents 📑

- [Overview](#overview)
  - [The Challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My Process](#my-process)
  - [Built With](#built-with)
  - [What I Learned](#what-i-learned)
  - [Continued Development](#continued-development)
  - [Useful Resources](#useful-resources)
- [Author](#author)

## Overview 👀

### The Challenge 💪

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot 📸

![Preview](./design/desktop-design.jpg)

*Add a screenshot of your solution here. You can use a tool like [FireShot](https://getfireshot.com/) to capture the full page.*

### Links 🔗

- Solution URL: [Solution](https://www.frontendmentor.io/solutions/responsive-layout-that-adapts-to-different-screen-sizes-vqtIb5UjwJ)
- Live Site URL: [Testimonial Preview](https://testimonials-grid-section-silk-theta.vercel.app/)

## My Process 🛠️

### Built With 🧱

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I Learned 🧠

During this project, I strengthened my skills in creating responsive layouts using CSS Grid. I also learned how to effectively use CSS custom properties to manage color themes and typography.

Here's an example of the CSS Grid layout I'm particularly proud of:

```css
.testimonial-grid {
    display: grid;
    gap: 24px;
    max-width: 1110px;
}

@media (min-width: 768px) {
    .testimonial-grid {
        grid-template-columns: repeat(4, 1fr);
    }

    .daniel {
        grid-column: span 2;
    }

    .patrick {
        grid-column: span 2;
    }

    .kira {
        grid-column: 4;
        grid-row: 1 / span 2;
    }
}
```

### Continued Development 🚀

In future projects, I want to focus on:

- Improving my CSS Grid skills for more complex layouts
- Enhancing accessibility features
- Implementing smooth animations for better user experience

### Useful Resources 📚

- [MDN Web Docs on CSS Grid](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout) - This helped me understand CSS Grid layout in depth.
- [CSS-Tricks Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - An excellent reference for Flexbox properties and use cases.

## Author 👨‍💻

- Website - [Abdullah](https://www.your-site.com)
- LinkedIn - [LinkedIn](https://www.linkedin.com/in/abdullah-a-2940b7260/)
- Frontend Mentor - [Abdullah](https://www.frontendmentor.io/profile/Ayyubiy90)
- Twitter - [Abdullah](https://www.twitter.com/ayyubiy10)
- Instagram - [Abdullah](https://www.instagram.com/ayyubiy_10)

## Acknowledgments 🙏

A special thank you to Frontend Mentor for providing this challenge. I also appreciate the community for their inspiration and support!