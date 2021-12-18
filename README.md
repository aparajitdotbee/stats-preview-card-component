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
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

<br>
<h2 >Mobile Preview</h2>
<p align="center"><br>
  <img src="https://github.com/aparajitdotbee/stats-preview-card-component/blob/main/final-design-screenshots/mobile-preview.jpeg?raw=true" alt="Mobile Preview" height=500px/>
</p>
<br>
<h2 >Desktop Preview</h2>
<p align="center">
  <img src="https://github.com/aparajitdotbee/stats-preview-card-component/blob/main/final-design-screenshots/desktop-preview.jpeg?raw=true" alt="Desktop Preview"/>
</p>

### Links

- Solution URL: [GitHub](https://github.com/aparajitdotbee/stats-preview-card-component)
- Live Site URL: [Netlify](https://stat-card-preview.netlify.app/)

## My process

### Built with

- HTML5
- CSS3

### What I learned

```html
<img srcset = "images\image-header-mobile.jpg 654w,
                   images\image-header-desktop.jpg 540w"
         sizes = "(max-width: 768px) 654px, 
                  540px"
         src = "images/image-header-desktop.jpg"
         alt = "Header Image">
```
```css
.container {
    color: hsl(0, 0%, 95%);
    width: auto;
    max-width: 920px;
    margin: 170px 250px;
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    grid-column-gap: 0;
    align-items: center;
}
```

### Continued development

- Hover animations
- Spacing and indentations
- Margin and Padding
- Display and Position styles
- Responsive Images

### Useful resources

- [Kevin Powell YouTube Channel](https://www.youtube.com/channel/UCJZv4d5rbIKd4QHMPkcABCw)
- [Web Dev Simplified YouTube Channel](https://www.youtube.com/c/WebDevSimplified)

## Author

- Frontend Mentor - [@aparajitdotbee](https://www.frontendmentor.io/profile/aparajitdotbee)
- GitHub - [@aparajitdotbee](https://github.com/aparajitdotbee)
