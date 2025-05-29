# Social links profile

## Table of contents

- [Overview](#overview)
  - [Screenshot and live site URL](#screenshot-and-live-site-url)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Inspired by](#acknowledgments)

## Overview

### Screenshot and live site URL

| Desktop                                     | Tablet                                    | Mobile                                    |
| ------------------------------------------- | ----------------------------------------- | ----------------------------------------- | 
| ![desktop](/assets/desktop-screenshot.jpeg) | ![Tablet](/assets/tablet-screenshot.jpeg) | ![Mobile](/assets/mobile-screenshot.jpeg) |

[Live Site URL](https://noonpanirsabzi.github.io/social-links-profile/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- CSS media queries

### What I learned

#### Small tricks:  
1. If you want to use html `button` element and style it the way you like, first you have to **unset** all it's default styles like this:  
```css
.button {
  all: unset;
  /* now you write any styles you want here */
```
2. when you want to make a perfect circle from a block element, you set it's `border-radius` to 50%:
```css
.profile__picture {
  border-radius: 50%;
  overflow: hidden; /* so whatever is in the box, dosn't overflow it from the edges and the effect actually work */
```
### Useful resources

- [Media query fundamentals](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/CSS_layout/Media_queries)


## Author

- Github - [@AminForouzan](https://github.com/AminForouzan)
- Frontend Mentor - [@AminForouzan](https://www.frontendmentor.io/profile/AminForouzan)

## Inspired by

- [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ).
