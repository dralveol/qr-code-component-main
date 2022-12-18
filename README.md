# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)


## Overview

### Screenshot

![Desktop view](./screenshots/Desktop-view.png)
![Mobile view](./screenshots/Mobile-view.png)


### Links

- Solution URL: [Git hub repo](https://github.com/dralveol/qr-code-component-main
- Live Site URL: [Live site](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned
Thinking about responsiveness. I made the QR code also a link so that it can also be clickable.

```html
<a href="https://www.frontendmentor.io" target="_blank" class="qr-code-link">
        <img src="./images/image-qr-code.png" 
        alt="QR code to visit www.frontendmentor.io, link is clickable" 
        class="qr-code-img">
      </a>
```
```css
.qr-code-link {
  display: block;
  width: 288px;
}
```

### Continued development
What do you think about the HTML was it appropriately semantic ?
Is the use of px for width of the card acceptable ?


## Author

- Frontend Mentor - [@dralveol](https://www.frontendmentor.io/profile/dralveol)

