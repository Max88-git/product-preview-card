# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [Solution](https://github.com/Max88-git/product-preview-card)
- Live Site URL: [Live](https://max88-git.github.io/product-preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS variables
- Flexbox

### What I learnt

1. I learnt about a new tag called `<del>` tag. Which defines text that has been deleted from a document. Browsers will usually strike a line through deleted text. This was ideal for use in the preview card's price section.

2. Another simple one, but making sure the flex container was properly configured to position the card in the centre of the page.

3. I was pleased with the small detail of aligning the cart logo with the text in the button. Vertical alignment of an inline, inline-block, or table-cell box is controlled by the vertical-align CSS property.

Here are some code snippets from my project, see below:

```html
<div class="price">
  <h4>$149.99</h4>
  <del>$169.99</del>
</div>
```

```css
.flex-container {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
}
```

```css
.btn > img {
  padding: 0 10px;
  vertical-align: middle;
}
```

### Continued development

The `<img>` in the mobile layout is one section of this project that could be revisited. It's not quite where it should be in the design files. I'd love to hear how others approached this challenge.

### Useful resources

- [flex-direction | MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/flex-direction) - This article helped me in making the .card into one column, with the preview image stacked on top of the description.

- [CSS The object-fit Property - W3Schools](https://www.w3schools.com/css/css3_object-fit.asp) - This is an amazing article which helped me finally understand how to specify how an `<img>` should be resized to fit its container. I'd recommend it to anyone still learning this concept.

## Author

- Website - [Max Lockwood](https://www.maxlockwood.uk/)
- Frontend Mentor - [@Max88-git](https://www.frontendmentor.io/profile/Max88-git)
- Twitter - [@maxlockwood88](https://twitter.com/maxlockwood88)
