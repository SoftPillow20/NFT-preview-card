# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](/NFT-preview-card-screenshot.png)

### Links

- Live Site URL: [NFT Preview card component](https://github.com/SoftPillow20/NFT-preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I was having a hard time creating the overlay for designing the image's hover state. I took 30 minutes trying to do different things to see what works and what doesn't. I'm not very familiar in creating overlay in images so I had to google it to reduce the time of solving it.

I got some of the code below from W3S schools website.

```css
.nft-img-box {
  position: relative;
  cursor: pointer;
}

.nft-img {
  display: block;
  width: 100%;
  height: auto;
  border-radius: 0.9rem;
}

.overlay {
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  width: 100%;
  height: auto;
  opacity: 0;
  transition: 0.5s ease;
  border-radius: 0.9rem;
  background-color: rgba(0, 255, 247, 0.45);
}

.nft-img-box:hover .overlay {
  opacity: 1;
}

.overlay-icon {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}
```

### Continued development

I want to keep practicing my HTML and CSS skills before I write my own website portfolio. Some components that interests me are accordion, hero section, header component, footer, CTA and featured-in sections, and how-to sections. I'm also interested in making an email-like structured layout just like in gmail.

## Author

- Frontend Mentor - [@SoftPillow20](https://www.frontendmentor.io/profile/SoftPillow20)
