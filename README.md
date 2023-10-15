# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](./design/desktop-design.jpg)


### Links

- Solution URL: [Solution URL here](https://your-solution-url.com)
- Live Site URL: [Live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- CSS variables
- Mobile-first workflow


**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

In this project i learnt more on CSS Grid property also getting little bit familiar with css variables. 

```html
<section>
          <article>
            <h2>10k+</h2>
            <p>companies</p>
          </article>

          <article>
            <h2>314</h2>
            <p>templates</p> 
          </article>

          <article>
            <h2>12M+</h2> 
            <p>queries</p>
          </article>
        </section>
```
```css
.hero-section{
        width: 90%;
        order: 1;
        padding: 2rem 2rem 2rem 2.5rem;
        text-align: left;
        display: grid;
        grid-template-areas: 
                        "h h h"
                        "p p p"
                        ". . ."
                        "f f f";
    }
```

### Continued development
Want to learn more about Grid property and get familiar with it.
## Author

- Website - Definetely
- Frontend Mentor - [@MjafarsadiqD](https://www.frontendmentor.io/profile/Ashraful-Fuqha)