# Frontend Mentor - Social proof section solution

This is a solution to the [Social proof section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-proof-section-6e0qTv_bA). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the section depending on their device's screen size


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
-Absolute and relative positioning
- [Visual Studio Code](https://visualstudiocode.com/) - IDE



### What I learned

I improved my knowledge of how to use relative vs absolute positioning in order to set the background of the page.

First i created a container for the images: 
```html
<div class="bg-box">
        <div class="bg-top"><img src="images/bg-pattern-top-desktop.svg"></div>
        <div class="bg-bottom"><img src="images/bg-pattern-bottom-desktop.svg"></div>
      </div>
```
Then apply the positioning. 
```css
.bg-box, .bg-top, .bg-bottom{
    position: absolute;
}
```
Then set the sizing:
```css
.bg-bottom{
    top: 110px;
    left: 400px;
}
```

### Continued development

Would to continue learning grid becaause despite achieving the end result i know there is an easier and more conventional way of doing this project. Flexbox skills need polishing too.

### Useful resources

- [Resource 1](https://www.w3schools.com/) - W3 schools always explained any css attributes or html components. This way i learnt best which to use.
- [Resource 2](https://devdocs.io/) - Gives the documentation of properties/arguments some attributes hold such as background for example. Lists all the examples as well. 

## Author

- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@aab_sanii](https://www.twitter.com/aab_sanii)
