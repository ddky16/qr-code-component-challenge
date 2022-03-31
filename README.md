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

![Desktop View](/QR%20Code%20Snapshot%20desktop%20view.png)
![Mobile View](/QR%20Code%20Snapshot%20mobile%20view.png)

### Links

- Solution URL: [Solution site](https://github.com/ddky16/qr-code-component-challenge)
- Live Site URL: [Live site](https://jocular-tiramisu-0fb33b.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I'm implementing about the semantic component of HTML card with :

```html
<!-- creating card section for container of the element -->
<div id="main-section">
  <!-- creating the content wrapper, then put all element into this container -->
  <div id="content">
    <img src="/images/image-qr-code.png" alt="QR code image" />
    <!-- this container should be positioning the box model of the card description -->
    <div id="description">
      <h1>Improve your front-end skills by building projects</h1>
      <p>
        Scan the QR code to visit Frontend Mentor and take your coding skills to
        the next level
      </p>
    </div>
  </div>
</div>
```

```css
/* creating the variable component for the color property */
html {
  --color-white: hsl(0, 0%, 100%);
  --color-light-gray: hsl(212, 45%, 89%);
  --color-grayish-blue: hsl(220, 15%, 55%);
  --color-dark-blue: hsl(218, 44%, 22%);
}
```

## Author

- Frontend Mentor - [@ddky16](https://www.frontendmentor.io/profile/ddky16)
- Twitter - [@code_ddky](https://twitter.com/code_ddky)
