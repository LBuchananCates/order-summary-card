# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

![order-summary-card-screenshot](https://github.com/LBuchananCates/order-summary-card/assets/100169368/b5d10f43-78d3-414b-ac5a-d3dc986e612f)


### Links

- Live Site URL: https://62855a2cd918513a731724dc--warm-zuccutto-0476b2.netlify.app/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow


### What I learned

Basic organization for layouts in mobile and desktop views

To see how you can add code snippets, see below:

Proud of this entire container and nesting everything in it correctly. It took some recoding as my approach to HTML was still new and took longer than usual, but I managed to layout everything correctly and label the classes clearly enough for easy styling
```html
 <main class="container">
    <img class="header-image" src="./images/illustration-hero.svg" alt="Girl dancing with headphones">
    <section class="content">
      <h1 class="content-header">Order Summary</h1>
      <p class="content-text">You can now listen to millions of songs, audiobooks, and podcasts on any
        device anywhere you like!</p>
      <div class="plan">
        <img src="./images/icon-music.svg" alt="Musicial note" class="music-note">
        <div class="plan-and-price">
          <p>Annual Plan <span>$59.99/year</span></p>
        </div>
        <a href="" class="change-plan">Change</a>
      </div>
      <div class="order-buttons">
        <button class="payment">Proceed to Payment</button>
        <a href class="cancel">Cancel Order</a>
      </div>
    </section>
  </main>
```

### Useful resources

- MDN
- stack overflow

## Author

- Website - https://62855a2cd918513a731724dc--warm-zuccutto-0476b2.netlify.app/
- Frontend Mentor - https://github.com/LBuchananCates
