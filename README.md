# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### Screenshot

![](./screenshot.jpg)


## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

On this challenge, I learned many things, how to create a button with a drop shadow, how to contain content with a flexbox and use a grid element within that to lay content vertically within a horizontal container.

Here's some code for context:

```html
<div class="summary__content">
<div class="flex-group">
  <img src="./images/icon-music.svg" class="music__icon">
  
  <div class="price__plan">
  <p class="plan__type">Annual Plan</p>
  <p class="price">$59.99/year</p>
  </div>

  <p class="change">Change</p>
  </div>
  <!-- Button defined here -->
  <button class="button"> Proceed to Payment </button>
  <p class="cancel">Cancel Order</p>
  </div>
  </div>


```
```css

.summary__content{
display: grid;
text-align: center;
gap: var(--content-spacing);
padding: var(--content-padding);
}

.price__plan{
display: grid;
justify-content: center;
 }

```


### Continued development

I'm starting to get the hang of having a plan of attack and having a thought process on both how to layout and contain my content within html and best practices for designing within css.
I did use some references to help me along with this challenge that focused on best practices as I'd like to create good habits early on, and I feel I'm on to a good start.


### Useful resources

- (https://www.youtube.com/watch?v=B2WL6KkqhLQ&list=PPSV) - I came across Kevin powell and love his approach and workflow for working in html and css (especially creating custom variables which allow for quick global changes), I initially watched this resource through before doubling back and tackling this challenge.


## Author

- Website - https://www.boyc3e.com
- Frontend Mentor - https://www.frontendmentor.io/profile/GrowingHermit44
- Twitter - https://www.twitter.com/boyc3e


