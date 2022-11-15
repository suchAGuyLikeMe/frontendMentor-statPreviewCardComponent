# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

-   [Overview](#overview)
    -   [The challenge](#the-challenge)
    -   [Screenshot](#screenshot)
    -   [Links](#links)
-   [My process](#my-process)
    -   [Built with](#built-with)
    -   [What I learned](#what-i-learned)
    -   [Continued development](#continued-development)
    -   [Useful resources](#useful-resources)
-   [Author](#author)

## Overview

### The challenge

Users should be able to:

-   View the optimal layout depending on their device's screen size

### Screenshot

![desktop-design](./screenshots/desktop.PNG)
![mobile Iphone XR](./screenshots/mobile-iphone-xr.PNG)
![mobile Iphone 12 Pro](./screenshots/mobile-iphone-12-pro.PNG)

### Links

-   Solution URL: (https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62/hub/stat-preview-card-component-47NOUpN_sC)
-   Live Site URL: (https://suchaguylikeme-statpreviewcardcomponent.pages.dev)

## My process

### Built with

-   Semantic HTML5 markup
-   CSS custom properties
-   Flexbox
-   CSS Grid
-   Mobile-first workflow

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
<section class="picture-section">
    <picture>
        <source
            media="(min-width: 821px)"
            srcset="img/image-header-desktop.jpg" />
        <img src="img/image-header-mobile.jpg" alt="picture of business team" />
    </picture>
</section>
```

```css
picture {
    position: relative;
}

picture::after {
    content: "";
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-image: linear-gradient(
        to bottom right,
        var(--primary-soft-violet),
        var(--primary-soft-violet)
    );
    opacity: 0.4;
}

img {
    display: block;
    width: 100%;
    height: 100%;
}
```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

### Continued development

The use of flexbox, grid, sementic markup and best practices.

### Useful resources

-   (https://www.w3schools.com) - This helped with learning both html and css, but there's various other sites that you could learn it too.

-   (https://www.freecodecamp.org) - This helped searching for specific solutions to my problem at hand. Used freecodecamp in conjunction with w3schools.

## Author

-   Frontend Mentor - [@suchAGuyLikeMe](https://www.frontendmentor.io/profile/suchAGuyLikeMe)
