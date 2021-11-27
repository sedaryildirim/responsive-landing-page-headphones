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

Code-along Challenge with Bedimcode for a Halloween website

- Beautiful headphone landing page using HTML, CSS and JAVASCRIPT.
- Dark interface.
- With animations when scrolling.
- Developed first with the Mobile First methodology, then for desktop.
- Compatible with all mobile devices and with a beautiful and pleasant user interface.

### Screenshot

![](/preview.png)

### Links

- Solution URL: [Github Repo](https://github.com/sedaryildirim/responsive-landing-page-headphones)
- Live Site URL: [Github Pages](https://sedaryildirim.github.io/responsive-landing-page-headphones/)

## My process

### Built with

- Semantic HTML5 markup
- Mobile-first workflow
- CSS custom properties
- Grid
- Flexbox
- JS

### What I learned

- learned how to use emmet correctly with class chaining
- fixed several errors with troubleshooting for display issues
- better understanding of developer tools whilst searching for bugs
- learned more css shorthand
- better understanding of bem naming structure

### Continued development

**- research how position: relative and absolute work more in depth**
**- does position absolute work in the current div**
*position:absolute works by positioning item relative to the last parent with a position: relative tag*

```html
<div class="parent">
  <div class="child">
    </div>
</div>
```

```css
.parent {
  position: relative;
}

.child {
  position: absolute;
  top: 0;
  left: 0;
}
```
*above would position the child in the parent, if parent had no position: relative, it would default to the next element with position:relative, and if no elements had position:relative, it would default to the body*

*it is removed from the document flow, where it will float above the current element/div, unless given a z-index:*

*z-index does not work unless item has a position: setting*

*relative position and static position are the same, but relative lets you use top: right: left: bottom*
- Source: https://www.youtube.com/watch?v=jx5jmI0UlXU
- Source: https://www.youtube.com/watch?v=P6UgYq3J3Qs

*position fixed ignores the parent elements even with position:relative, they always default to body flow and they also stay in same place when page is scrolled*

*sticky positioning works as position:relative and position:fixed together, eg if you give a element position: sticky, it defaults as relative, but once you start scrolling the page it becomes fixed:position*

- how do ::after and ::before work
- research :not
- research z-index
- difference between flex/inline flex and block/inline block

### Useful resources

- [Bedimcode](https://www.youtube.com/c/Bedimcode)
- [Scroll Reveal](https://scrollrevealjs.org/)

## Author

- Website - [Sedar Yildirim](https://github.com/sedaryildirim)
- Frontend Mentor - [@sedaryildirim](https://www.frontendmentor.io/profile/sedaryildirim)
- Twitter - [@Sdry85](https://www.twitter.com/sdry85)

## Acknowledgments

- [Bedimcode](https://www.youtube.com/c/Bedimcode)
- [Scroll Reveal](https://scrollrevealjs.org/)