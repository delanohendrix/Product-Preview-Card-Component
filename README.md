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

![Screenshot](/screenshot.png)

### Links

- Solution URL: [My Solution](https://your-solution-url.com)
- Live Site URL: [Github Pages](https://delanohendrix.github.io/Product-Preview-Card-Component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I learned how to write HTML in a BEM format, as well as actually focusing on a mobile-first workflow. This was actually my second attempt at the challenge; the first one I targeted completing the desktop version first which led to issues when I tried to design the mobile version. I scrapped that attempt and started over this time trying to make it as simple as possible.

The HTML I wrote in a BEM format:

```html
<div class="product">
  <picture class="product__image">
    <source media="(min-width:600px)" srcset="/images/image-product-desktop.jpg" />
    <img
      src="/images/image-product-mobile.jpg"
      alt="Picture of a Gabrielle Essence Eau De Parfum bottle laying on a table" />
  </picture>
  <div class="product__info">
    <p class="product__type">Perfume</p>
    <h1 class="product__name">Gabrielle Essence Eau De Parfum</h1>
    <p class="product__description">
      A floral, solar and voluptuous interpretation composed by Olivier Polge, Perfumer-Creator for
      the House of CHANEL.
    </p>
    <div class="product__price">
      <h2 class="product__current-price">$149.99</h2>
      <p class="product__original-price">$169.99</p>
    </div>
    <button type="submit" class="atc-button">
      <img src="/images/icon-cart.svg" alt="Shopping Cart Icon" class="icon" />
      Add to Cart
    </button>
  </div>
</div>
```

### Continued development

I would like to continue implementing BEM formats into my HTML and become more comfortable tackling mobile-first designs from the very beginning.

### Useful resources

- [CSS Reference](https://cssreference.io/) - This site helped me by refreshing me on the usage of various css attributes and properties.
- [Josh W Comeau's CSS Reset](https://www.joshwcomeau.com/css/custom-css-reset/)

## Author

- Frontend Mentor - [@delanohendrix](https://www.frontendmentor.io/profile/delanohendrix)
