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
  - [Useful resources](#useful-resources)
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)

## Overview

### Screenshot

![](./Screenshot.png)

### Links

- Solution URL: [https://github.com/Lueslin/qr-code-component]
- Live Site URL: [https://lueslin.github.io/qr-code-component/]

## My process

### Built with

- Semantic HTML5 markup
- CSS3 custom properties
- Flexbox
- [Google Fonts](https://fonts.google.com/) - Outfit font family

### What I learned

In this first challenge, I focused on translating a clean UI design into semantic HTML and well-structured CSS. My main takeaways were:

- Structuring the page cleanly using semantic tags like `<main>` and `<footer>` with descriptive `alt` text for accessibility.
- Centering the card vertically and horizontally on the screen using Flexbox combined with `min-height: 100vh` (and removing fixed heights so the card grows naturally with its content).
- Applying concentric `border-radius` values (`19px` on the outer card and `13px` on the inner QR code image) to maintain visual harmony and consistent padding.

```css
body {
  font-family: "Outfit", sans-serif;
  background-color: #d5e1ef;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  min-height: 100vh;
}
```

### Continued development

Moving forward, I plan to complete daily Frontend Mentor challenges to build strong muscle memory in responsive layouts, deepen my understanding of CSS spacing (`margin` vs. `padding`) and CSS Grid, and gradually introduce JavaScript interactivity into upcoming projects.

### Useful resources

- [A Complete Guide to Flexbox (CSS-Tricks)](https://css-tricks.com/snippets/css/a-complete-guide-to-flexbox/) - Helped me understand how `justify-content`, `align-items`, and `flex-direction` work together to center the card both vertically and horizontally.
- [Google Fonts](https://fonts.google.com/) - Used to import and apply the Outfit font family with the exact weights specified in the style guide.

### AI Collaboration

I used **Gemini** as a step-by-step coding mentor throughout this project. Instead of generating ready-made code, I wrote the entire HTML and CSS myself and relied on AI guidance to review my layout decisions, troubleshoot vertical centering with `min-height: 100vh`, refine typographic hierarchy, and set up my first deployment workflow on GitHub Pages.

## Author

- Website - [Lueslin Camacho](www.behance.net/logicbylueslin)
- Frontend Mentor - [@Lueslin](https://www.frontendmentor.io/profile/Lueslin)

