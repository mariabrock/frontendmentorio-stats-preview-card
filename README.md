# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - Stats preview card component solution](#frontend-mentor---stats-preview-card-component-solution)
  - [Table of contents](#table-of-contents)
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
  - [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](./assets/desktop-view.png)
![](./assets/mobile-view.png)

### Links

- Solution URL: [Github](https://github.com/mariabrock/frontendmentorio-stats-preview-card)
- Live Site URL: [Github Pages](https://mariabrock.github.io/frontendmentorio-stats-preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

Fun code:

```html
<div class="image">
  <div class="overlay"></div>
</div>
```
```css
.overlay {
  grid-area: image;
  align-self: stretch;
  width: 100%;
  height: 100%;
  background-color: hsl(277, 64%, 61%);
  opacity: 0.5;
  border-top-right-radius: 10px;
  border-bottom-right-radius: 10px;
}

.image {
  grid-area: image;
  align-self: stretch;
  height: 450px;
  background-image: url('./assets/image-header-desktop.jpg');
  background-position: center;
  background-size: cover;
  background-repeat: no-repeat;
  border-top-right-radius: 10px;
  border-bottom-right-radius: 10px;
}
```

### Continued development


### Useful resources

- [A Complete Guide to CSS Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)

## Author

- Github - [@mariabrock](https://github.com/mariabrock)
- Frontend Mentor - [@mariabrock](https://www.frontendmentor.io/profile/mariabrock)
- LinkedIn - [@mariabrock](https://www.linkedin.com/in/maria-brock/)

## Acknowledgments
