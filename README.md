# Frontend Mentor - Single price grid component solution

This is a solution to the [Single price grid component challenge](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc) on Frontend Mentor

## Table of contents

-  [Overview](#overview)
   -  [The challenge](#the-challenge)
   -  [Screenshot](#screenshot)
   -  [Links](#links)
-  [My process](#my-process)
   -  [Built with](#built-with)
   -  [What I learned](#what-i-learned)
   -  [Continued development](#continued-development)
   -  [Useful resources](#useful-resources)
-  [Author](#author)

## Overview

### The challenge

Your users should be able to:

-  View the optimal layout for the component depending on their device's screen size
-  See a hover state on desktop for the Sign Up call-to-action

### Screenshot

![](./screenshot.png)

### Links

-  Live Site URL: https://single-price-grid-component-jjw.netlify.app/

## My process

### Built with

-  Semantic HTML5 markup
-  Flexbox
-  CSS Grid
-  Mobile-first workflow

### What I learned

This was the first challenge I attempted on the Front End Mentor without an official solution to reference. That whole concept was terrifying at first, but I quickly reaped the rewards by feeling more independant as a developer after successfully completing it.

```html
<p class="light-grey">
   <strong class="price">$29</strong><span class="opaque">per month</span>
</p>
```

I used this project to practice using different semantic elements where appropriate, providing additional context to screen readers for visually impaired users. It's important we consider accessibility when writing out our markup, as writing semantic HTML is one of the best ways we can adhere to the set guidlines for doing so.

```css
.join {
   grid-column: 1 / 3;
   background-color: white;
   border-top-left-radius: 5px;
   border-top-right-radius: 5px;
}
```

I had only recently learnt about the `grid-column` property when using CSS Grid, so this project provided a nice means at practicing it. For me, the most difficult challenge when using Grid is visualising the layout in terms of columns and rows, whilst figuring out where each item should stretch to. I realise this will come with more practice, and I'm aware of the Grid inspector tool that lives in the Developer Tools to help us out as well.

### Continued development

I look forward to experimenting more with the border-radius property since I find myself constantly having to change specific corner radiuses at different viewport sizes manually.

## Author

-  Website - [Joshua Jameson-Wallis](https://www.joshuajamesonwallis.com/)
-  Linkedin - [Joshua Jameson-Wallis](https://www.linkedin.com/in/joshua-jameson-wallis/)
