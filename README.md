# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
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

### Links

- Live Site URL: [Add live site URL here](https://kyle4real.github.io/3-column-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Desktop-first workflow
- Google Fonts

### What I learned

The most valuable takeaway from this project was learning how to use github pages. All it takes is a new or existing repository, along with a click-or-two in the settings of that repo, and anytime I would push changes, the live website would update. Brilliant. Though not necessary, hosting this project online was quite helpful; for I felt as if I could've reached out for help at anytime.

This project also helped to reinforce my git and github workflow skills. I would commit changes when deemed important, and I also played around with the git commands for testing purposes.

Using flexbox made this project super simple. I only ran into a couple situations where I was at a lack of knowledge; for instance, I couldn't understand why I couldn't just justify-self:bottom the buttons within the 'child' elements so that the buttons would be (for lack of a better term) glued to the bottom of the child elements. With a bit of googling, I found a way:

```css
button {
  margin-top: auto;
}
```

Another issue I had with flexbox had to do with the width of the child elements inside the 'container' flex element. If I made each childs width 1/3rd of 100% of the parent width, then when I used flex-wrap:wrap, the children would only shrink instead of maintaining a good width and wrapping. So, I used min-width instead, and that seemed to solve the issue though I'm still a bit confused on the subject.

To use media queries, I needed a refresher on the syntax.

### Continued development

I want to refine techniques to do with flexbox like: aligning specific children of elements, and better configuring the width related properties of child elements.

I also want to keep refining my knowledge and "keep a keen-eye" for styling metas (like line-height, word-spacing, font-size, etc.) so that my projects look professional.

I want to also learn more about flex grid so that I feel confident using it; like how I feel with flexbox.

### Useful resources

- [aligning items](https://stackoverflow.com/questions/31000885/align-an-element-to-bottom-with-flexbox) - This helped me with aligning the buttons correctly. This method was useful and I hope to remember this for future projects.
- [github pages](https://pages.github.com/) - The video on this webpage helped me tremendously to fully understand github pages, and how to use it to host this project.

## Author

- Frontend Mentor - [@kyle4real](https://www.frontendmentor.io/profile/kyle4real)
