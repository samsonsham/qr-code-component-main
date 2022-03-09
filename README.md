# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### Screenshot

![](https://ik.imagekit.io/c5xc1x6srka/screenshot/screen-qr-code2_jhh0JsDuo.png)

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

### Useful Resources

These 2 articles give me the ideas of structure my scss files in my project:

- [Structuring your Sass Projects](https://itnext.io/structuring-your-sass-projects-c8d41fa55ed4)
- [2 SMARTEST WAYS TO STRUCTURE SASS](https://www.webdesignerdepot.com/2020/12/2-smartest-ways-to-structure-sass/)

I learnt the concept of BEM from this article which guide me to build a well structured DOM:

- [BEM Document](https://en.bem.info/methodology/quick-start/#block)

I learnt to use main tag from this article:

- [What is the purpose of the <main> tag in HTML?](https://dev.to/srijan1709/what-is-the-purpose-of-the-main-tag-in-html-3hno)

This article answered my question of using classes without any CSS style behind.

- [Can I use non existing CSS classes?](https://stackoverflow.com/questions/18701670/can-i-use-non-existing-css-classes)

## Author

- Website - [Samson Sham](https://samson-sham-portfolio.vercel.app)
- Frontend Mentor - [@samsonsham](https://www.frontendmentor.io/profile/samsonsham)
- Twitter - [@samson_sham](https://www.twitter.com/samson_sham)

### Acknowledgments

I would like to thank [@CyrusKabir](https://www.frontendmentor.io/profile/CyrusKabir) for valuable comments and has given me useful articles for my reference. They are helpful for not only improving my code base structure and code readability, but also understand the concept.
