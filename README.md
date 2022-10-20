# Make It Real - Profile Card Component

This is a solution to the Profile Card Component project of the Make It Real course.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
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

- Build a team website based on a plain image design and include a favicon
- Adapt css styling to be responsive

### Screenshot

![screenshot of the proyect](./design/screenshot.png)

## My process

To begin with, we analized the image proposed as design to identify the structural elements for HTML file. Then we applied that structure to the HTML file, including favicon. Later, we applied styling with css for the mobile design. Finally we applied the required modifications for the desktop design.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I remembered and learned couple of handy css properties:

```css
#card-top {
  position: relative;
  background-image: url('../../assets/bg-pattern-card.svg');
  padding-top: 50%;
  border-radius: 1em 1em 0 0;
}

.img-container {
  position: absolute;
  top: 40%;
  left: 50%;
  transform: translateX(-50%) translateY(-50%);  
}
```

### Continued development

I need to keep working on relative and absolute positioning. Also, on the transform property.

### Useful resources

- [MDN on transform translate](https://developer.mozilla.org/es/docs/Web/CSS/transform-function/translate) - This helped me to adjust properly the avatar image.

## Author

- [LinkedIn](https://www.linkedin.com/in/juan-orjuela/)
- [Behance](https://www.behance.net/juan_o)

## Acknowledgments

Special aknowledgments to Daniela Quinche and Daniel Monsalve, coding partners on this task, and to [Cristian Moreno](https://github.com/khriztianmoreno), teacher and mentor for supervising our process.