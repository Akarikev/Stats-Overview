# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View designs

### Links

- Solution URL: [solution URL here]()
- Live Site URL: [ live site URL here](https://frontendmentorstatso.netlify.app/)

## My process

First, i drew out an overview of the project, to make sure am following the html and css rules. I layered down the html components and separated all components into their respectives.
I worked on, desktop first, to be sure with the margins and paddings of respective components, also, to see active hover states for elements. The responded correctly in their active states. I added the basic CSS properties first, before ensuring to add other complex properties.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Desktop-first workflow

### What I learned

Though this was a simple challenge, i sort of find it challenging especially with the Media Queries. I learnt that, All devices follow certain rules for HTML and CSS, and that i think should be respected, if one wants to create, a very responsive project.
Also, I learnt, the use of FlexBox is quite important for responsive designs and workflow.

To see how you can add code snippets, see below:

```html
<div class="stats">
  <div>
    <p class="h2">10k+</p>
    <p class="stats-sub">companies</p>
  </div>
  <div>
    <p class="h2">314</p>
    <p class="stats-sub">templates</p>
  </div>
  <div>
    <p class="h2">12M+</p>
    <p class="stats-sub">Queries</p>
  </div>
</div>
```

```css
.image-box::after {
  position: absolute;
  content: "";
  height: 100%;
  width: 100%;
  left: 0;
  top: 0;
  background-color: hsl(277, 64%, 61%);
  opacity: 0.4;
  border-top-right-radius: 11px;
  border-bottom-right-radius: 11px;
}
```

### Continued development

I want to continue focusing on the use of css flexbox and media queries, generally, focus on responsive designs. Though this is my first, i would like to learn more from anyone out there!

### Useful resources

- [resource 1](https://www.w3schools.com) - This helped me for writing media queries. I really liked this pattern and will use it going forward. This is an amazing article which helped me finally understand flexblox and, positioning. I'd recommend it to anyone still learning this concept.

## Author

- Frontend Mentor - [@Akarikev](https://www.frontendmentor.io/profile/Akarikev)
- Twitter - [@elorm_elom](https://www.twitter.com/elorm_elom)

## Acknowledgments

Thanks to the internet, for helping, me not cry out or loose hope!
