# Frontend Mentor - Product preview card component

I decided to work on the [product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa)

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

#### Desktop view

![](/screenshots/desktop-screenshot.png)

#### Mobile view

![](/screenshots/mobile-screenshot.jpg)

### Links

- Live Site URL: [Live Site](https://noneofurbuzz.github.io/product-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS
- Flexbox
- Mobile-first workflow

### What I learned

#### Always start with mobile-first workflow

I could have saved so much time if I had just started with the mobile view first rather than the desktop view.

#### I learnt about pointer CSS media feature 

I used this to test if the user has a pointing device (such as a mouse) for the hover effects for the buttons on desktop view.

```css
@media (pointer:fine){
    button:hover{
        cursor: pointer;
        background-color: hsl(158, 36%, 15%) ;
    }
    button:active{
        background-color: hsl(158, 36%, 37%);
    }
}
```
### Continued development

I think the most important thing this project has taught me is to continue working on responsive projects because I need a lot of practice in that area.

### Useful resources

- [mdn web docs](https://developer.mozilla.org/en-US/docs/Web/CSS/@media/pointer) - This helped me with the pointer CSS media feature.

## Author

- Github - [Ugochi Ike](https://github.com/noneofurbuzz)
- Linkedin - [my linkedin](https://www.linkedin.com/in/ugochi-ike-0647aa244/)

