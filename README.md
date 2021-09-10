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
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

1. Desktop Design
![FEM-order-summary(1)](https://user-images.githubusercontent.com/84383548/132903701-831b00dd-4cfa-46f3-9712-3a632a6099d4.png)

1. Mobile Design <br>
![FEM-order-summary(2)](https://user-images.githubusercontent.com/84383548/132903721-a292ab78-479f-425a-b4be-1d3797f6ce0f.png)

### Links

- Solution URL: [My Frontend Mentor Solution](https://www.frontendmentor.io/solutions/order-summary-with-pure-html-and-css-S2R555cjZ)
- Live Site URL: [Netlify Live Site](https://blissful-mccarthy-de1053.netlify.app/)

## My Process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

- CSS flexbox
- CSS grid
- CSS absolute and relative positioning
- CSS before and after Pseudo elements
- HTML5 Markup

Some HTML code from the project

```html
<main id="main">
  <div class="main__img">
    <img src="./images/illustration-hero.svg" alt="streamer illustration" />
  </div>

  <div class="main__description">
    <h1>Order Summary</h1>

    <p>
      You can now listen to millions of songs, audiobooks, and podcasts on any
      device anywhere you like!
    </p>

    <div class="pricing">
      <div class="pricing__img">
        <img src="./images/icon-music.svg" alt="" />
      </div>

      <p>
        Annual Plan <br />
        <span>$59.99/year</span>
      </p>

      <a href="#">Change</a>
    </div>

    <a href="#proceed">Proceed to Payment</a>
    <a href="#cancel">Cancel Order</a>
  </div>
</main>
```

Some CSS code from the project

```css
#main {
    width: min(20rem, 85%);
    background-color: var(--neutral-pale-blue);
    border-radius: 1rem;
}

#main .main__img {
    width: 100%;
}

#main .main__img > img {
    width: 100%;
    border-top-left-radius: 1rem;
    border-top-right-radius: 1rem;
}

#main .main__description {
    padding: 2rem 2rem;
    width: 100%;
    display: grid;
    justify-content: center;
    text-align: center;
}

#main .main__description > h1 {
    font-size: 1.5rem;
    font-weight: 900;
    color: var(--neutral-dark-blue);
    margin-bottom: 2rem;
}

#main .main__description > p {
    color: var(--neutral-desatured-blue);
    line-height: 1.5;
    margin-bottom: 2rem;
}
}
```

## Author

- Twitter - [@abanicaisse](https://www.twitter.com/abanicaisse)
- Frontend Mentor - [@abanicaisse](https://www.frontendmentor.io/profile/abanicaisse)
- CodePen - [My codepen](https://www.codepen.io/Nicaisse)
