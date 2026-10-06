# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size


### Links

- Solution URL: (https://github.com/Krysmynta/Four-card-feature-section)
- Live Site URL: (https://krysmynta.github.io/Four-card-feature-section/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

Mainly, for me, this challenge was about practising how to use CSS Grid for layout. However, I doubt that I found the most clean and effective solutions.

```css
.container {
  max-height: 100%;
  margin-inline: 11rem;
  display: grid;
  grid-gap: 2rem;
  grid-template-columns: 1fr 1fr 1fr;
  grid-template-rows: repeat(autofit, minmax(1rem, 1fr));
}

.card-1 {
  grid-column: 1;
  grid-row: 4 / span 2;
  border-top: 2px solid var(--Cyan);
}
```

### Continued development

I need a lot more practise with CSS Grid. For example, I need to also use it together with the mobile-first approach, which I scipped this time (I wanted to make sure I managed to create the more "griddy" desktop layout first of all, before continuing with other coding parts.)

### AI Collaboration

I used ChatGPT and GitHub Copilot to get answer to general questions and getting guidance around specific problems that I encountered building the project. 

## Author

- Frontend Mentor - [@Krysmynta](https://www.frontendmentor.io/profile/Krysmynta)



