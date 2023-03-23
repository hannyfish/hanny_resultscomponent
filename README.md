# Frontend Mentor - Results summary component solution

This is a solution to the [Results summary component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

![Desktop1](https://img.nickpic.host/QRvoFQ.png)
![Desktop2](https://img.nickpic.host/QRvIL2.png)
![Mobile](https://img.nickpic.host/QRvG4s.jpg)

### Links

- Solution URL: (https://codepen.io/hanny/pen/vYzVjdx)
- Live Site URL: (https://hannyfish.github.io/hanny_resultscomponent/)

## My process

### Built with

- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

I had a very interesting time figuring out how to use :before relative to the code class itself, and how to make things align in line with the brief/style guide. Since it's my second time working with HSL as a colour definition, I also learned how to balance the knowledge I already have of hex, var and rgba and consolidating that into using hsl.

I also learned the best way to structure code for @media and mobile vs desktop view in terms of accessibility. I had a difficult time making it respond to mobile view - unsure as to why, unless it's just because my mobile phone is particularly large, but it works perfectly fine on CodePen and not so much on GitHub. It turned out that it was a viewport issue as well as a browser issue relating to a fairly older phone, so thankfully it didn't seem to be a huge issue with the code.

A bit of CSS I was happy with - I originally wrote them all out separately with a lot of different settings, but eventually consolidated them into something more concise.

```css
.results-reaction span,
.results-memory span,
.results-visual span,
.results-verbal span {
  color: hsla(224, 30%, 27%, 50%);
  display: block;
  text-align: right;
  width: 100%;
  padding-right: 15px;
}
.results-reaction b,
.results-memory b,
.results-visual b,
.results-verbal b {
  color: var(--dg-blue);
}
```

### Continued development

I want to continue focusing on consolidating my knowledge of flexbox and grid, and using this to a more concise degree when creating projects. As well as this, I want to continue at doing better at making my code concise and easy to parse, as I have always had an issue of overdoing code, so there is often properties that are not needed or have no effect/clash with other parts left in the code. 

## Author

- Codepen - [hanny](https://codepen.io/hanny)
- Frontend Mentor - [@hannyfish](https://www.frontendmentor.io/profile/hannyfish)

## Acknowledgments

Shout out to one of my best friends (who is not on FE-M) who helped me out in figuring the best way to display the results section instead of using positioning (which I am often falling back on and need to break out of the habit). 

Thank you also to @atif-dev who commented on my first QR code solution and gave me a further solution to make things easily center on the page, as well as advising me on writing this README!
