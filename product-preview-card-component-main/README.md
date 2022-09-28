# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

## My process

### Built with

- HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- [Bootstrap 5](https://getbootstrap.com/) - CSS framework

### What I learned

By working with this project i've learn how to build card component using bootstrap 5 and make it responsive

code snippets, see below:

```html
<div class="container d-flex justify-content-center vh-100 align-items-center my-3">
    <div class="card" style="width: 600px;">
      <div class="row no-gutters">
        <div class="col-sm-12 col-lg-6">
          <img src="images/image-product-desktop.jpg" alt="image product" class="card-img d-none d-lg-inline img-fluid image">
          <img src="images/image-product-mobile.jpg" alt="image product" class="card-img d-inline d-lg-none img-fluid image" style="max-width: 100vw;">
        </div>
        <div class="col-sm-12 col-lg-6 pe-4 pt-4">
          <div class="card-body">
            <p class="card-subtitle subtitle text-uppercase">Preview</p>
            <h1 class="card-title title my-3 fs-1">Gabrielle Essence Eau De Parfum</h1>
            <p class="card-text text">A floral, solar and voluptuous interpretation composed by Olivier Polge,
            Perfumer-Creator for the House of CHANEL.</p>

            <div class="d-flex align-items-center">
              <span class="new-price fs-2">$149.99</span>
              <span class="old-price ms-4"><small><s>$169.99</s></small></span>
            </div>

            <button class="btn btn-primary d-block my-3 w-100 py-2 button" style="font-family: var(--family-Montserrat);">Add to Cart</button>
          </div>
        </div>
      </div>
    </div>
  </div>
```

### Useful resources

- [Boostrap Documents](https://getbootstrap.com/docs/4.3/components/card/) - This helped me to build card component.
