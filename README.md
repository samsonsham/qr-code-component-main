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

![](https://ik.imagekit.io/c5xc1x6srka/screenshot/screen-qr-code_iQK_yRd8AxK.png?ik-sdk-version=javascript-1.4.3&updatedAt=1646671016571)

### Links

- Solution URL: [https://github.com/samsonsham/qr-code-component-main](https://github.com/samsonsham/qr-code-component-main)
- Live Site URL: [https://samsonsham.github.io/qr-code-component-main/](https://samsonsham.github.io/qr-code-component-main/)

## My process

- Define all the styles given by style guide, including colours and font into SCSS file.
- Setup DOM structure in HTML file (container, heading, paragraph).
- Paint the elements in SCSS
- Adjust size and alignment of elements

### Built with

- Semantic HTML5 markup
- SCSS
- Flexbox

### What I learned

Every time I do vertical alignment, CSS won't make me disappointed by not working at first 🙃. This challenge has reminded me that after applying 'align-items' property to flex container, it won't work unless I define its height. Another thing is that when I added 'height: 100vh' to the container, there would be an unwanted vertical scroll. I have to reset the margin and padding in order to get rid of it.

```css
body {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  margin: 0;
  padding: 0;
}
```

## Author

- Website - [Samson Sham](https://samson-sham-portfolio.vercel.app)
- Frontend Mentor - [@samsonsham](https://www.frontendmentor.io/profile/samsonsham)
- Twitter - [@samson_sham](https://www.twitter.com/samson_sham)
