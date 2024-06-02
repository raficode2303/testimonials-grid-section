# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](./screenshot.jpg)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it.

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [github](https://github.com/raficode2303/testimonials-grid-section.git)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

how to use css grid for columns that are not even. to combine flex and grid together.

### Solution retrospective

1. What are you most proud of, and what would you do differently next time?

next time i will try solve it using flex only.
maybe to solve if it can solved without using `@media`

2. What challenges did you encounter, and how did you overcome them?

- how to create different width size of grids. i read about grid and learned how to span grids.

- i learned how to resize a svg `::before` pseudo-element content using `scale()`.
- how to make some of the cards 2.1fr and the other 1fr?

3. What specific areas of your project would you like help with?

- how to make the 1st and the 4th cards 2.1x than the other cards. is there `grid-column: sapn 2.1`?

- how to solve the challenge without using `@media`.

###### main code snippets:

```css
.card:nth-child(1):before {
  position: absolute;
  content: url(./images/bg-pattern-quotation.svg);
  z-index: -99;
  right: 15%;
  top: 2%;
  transform: scale(1.1);
}
```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

### Continued development

start to add js

### Useful resources

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

## Acknowledgments
