# Frontend Mentor - FAQ accordion card solution

This is a solution to the [FAQ accordion card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/faq-accordion-card-XlyjD0Oam). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See hover states for all interactive elements on the page
- Hide/Show the answer to a question when the question is clicked

### Screenshot

![](./images/FAQ%20Accordion%20Card.png)


### Links

- [Github](https://github.com/ikennarichard/faq-accordion-card)
- [Live](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned

I enjoyed the time spent on this project, it was worth it. For this project i decided to use html and css throughout, i could easily understand how to manipulate the card with js but I need to study more to grasp the concepts.

```html
 <div class="fifth">
      <input type="checkbox" name="accordion" id="fifth">
      <div class="question">
        <label for="fifth">
          Do you provide additional support?
        </label>
        <span class="icon">
          <img src="./images/icon-arrow-down.svg" alt="">
        </span>
      </div>
```
```css
input[type='checkbox']:checked + .question span {
    transform: rotate(180deg);
    transition: transform 0.4s ease-out;
}
```


### Continued development

CSS Position
CSS Transform
HTML Mark up
CSS Responsiveness


## Author

- [ikennarichard](https://github.com/ikennarichard)
- [@ikennarichard](https://www.frontendmentor.io/profile/ikennarichard)



## Acknowledgments

Ill like to thank all my mentors on Frontend Mentor for their inputs, i see myself getting better and its because of the time they took to go through my code and point areas i can improve on. Thank You guys so MUCH!