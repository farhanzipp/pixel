# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### Screenshot

![QR Code fullscreen result ](./fullscreen.png)

### Links

- Solution URL: [Add solution URL here](https://github.com/farhanzipp/FrontEndMentor-QR-Code-Component.git)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I use CSS var to simplify define the colors inside variable like this

```css
:root {
    --white: hsl(0, 0%, 100%);
    --light-gray: hsl(212, 45%, 89%);
    --gray-blue: hsl(220, 15%, 55%);
    --dark-blue: hsl(218, 44%, 22%);
}
```
And using them like this

```css
a {
    color: var(--light-gray);
    text-decoration: none;
}

a:hover {
    color: var(--white);
}
```
I don't use fancy technology like react and framworkes to maintain simplify and increase understanding of styling.

## Author

- Website - [Add your name here](https://farhanzip.netlify.app)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/farhanzipp)
