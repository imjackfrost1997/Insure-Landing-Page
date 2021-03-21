# Frontend Mentor - Insure landing page solution

This is a solution to the [Insure landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/insure-landing-page-uTU68JV8). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## My process

### Built with

- Semantic HTML5 markup
- CSS3 custom properties
- Flex box
- CSS Grid
- Desktop-first workflow
- Vanilla JavaScript - For navigation functionality

### What I learned

I've finally understand on how to use CSS Grid property with the code below to make a perfect layout i just realized that building things can improve your CSS skills and problem solving overall just be persistent when times get rough just simply take a break and get a coffee you will make it eventually my final thoughts is buildings things will make you improve :)

To see how you can add code snippets, see below:

```html
<header>
  <nav>Top Navigation</nav>
</header>
<footer>
  <nav>Footer Navigation</nav>
</footer>
```

```css
    main {
    position: relative;
    background: hsl(256, 26%, 20%);
    height: 100vh;
    display: grid;
    grid-template-columns: 10% 1fr 10%;
    grid-template-rows: auto 1fr;
    grid-template-areas:
      'heading heading heading'
      '. section .';
    overflow: visible;
  }
}
```

```js
const menu = document.querySelector('.menu');
const nav = document.querySelector('.nav');
menu.addEventListener('click', () => {
  nav.classList.toggle('active');
  menu.classList.toggle('active');
});
```

## Author

- Twitter - [@Robert11340562](https://twitter.com/Robert11340562)
- Frontend Mentor - [@imjackfrost1997](https://www.frontendmentor.io/profile/imjackfrost1997)

## Acknowledgments

Just don't give up remember to pray every time you struggle open your heart and seek for his help and he will help you <3
