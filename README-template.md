# Frontend Mentor - Interactive rating component solution

This is a solution to the [Interactive rating component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/interactive-rating-component-koxpeBUmI). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the app depending on their device's screen size
- See hover states for all interactive elements on the page
- Select and submit a number rating
- See the "Thank you" card state after submitting a rating

### Screenshot
- Desktop:
  - [Rating Card](./screenshots/screenshot-rating-card-desktop.png)
  - [Thank Card](./screenshots/screenshot-thank-you-card-desktop.png)
- Mobile:
  - [Rating Card](./screenshots/screenshot-rating-card-mobile.png)
  - [Thank Card](./screenshots/screenshot-thank-you-card-mobile.png)
  

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I have learned a way to customize my own radio buttons!
Basically the code: 
```html
<label>
  <input type="radio" name="Name" value="Content">
  <span>Content</span>
</label>
```
```css
/* Remove the default button */
input {
  display: none;
}

/* Customized button */
span {
  /* Button design */
}

span:hover {
  /* Button design when hovered */
}

label input:checked ~ span {
  /* Button design after checked */
}
```

### Useful resources

- [How To - Custom Checkbox](https://www.w3schools.com/howto/howto_css_custom_checkbox.asp) - This helped me customize the radio buttons in the project.
