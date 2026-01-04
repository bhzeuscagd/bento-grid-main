# Frontend Mentor - Bento grid solution

This is a solution to the [Bento grid challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/bento-grid-RMydElrlOj). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [Astro](https://astro.build/) - Web Framework
- [Tailwind CSS v4](https://tailwindcss.com/) - Utility-first CSS framework
- [DM Sans](https://fontsource.org/fonts/dm-sans) - Font

### What I learned

Creating a Bento Grid layout offered a great opportunity to practice advanced CSS Grid techniques. I focused on creating a reusable `GridCol` component in Astro to handle the various grid cells efficiently. This approach kept the main layout file clean while allowing for specific styling customization for each block via props.

Here is a snippet of how I structured the main grid using Tailwind CSS classes to handle responsiveness:

```astro
<div class="grid grid-cols-1 auto-rows-[10px] gap-4 min-w-0 lg:grid-cols-4 lg:auto-rows-[140px]">
    <!-- Grid items go here -->
</div>
```

I also explored the new configuration and features of Tailwind CSS v4, ensuring the project is up-to-date with the latest tooling.

### Continued development

In future projects, I aim to further explore Astro's islands architecture and deeper integrations with other UI frameworks if needed. I also want to continue refining my skills with complex grid layouts and animations to make the user experience even smoother.

### Useful resources

- [Astro Documentation](https://docs.astro.build/) - The official documentation is always the best place to start.
- [Tailwind CSS Documentation](https://tailwindcss.com/docs) - Essential for looking up utility classes and configuration.
- [CSS Grid Guide](https://css-tricks.com/snippets/css/complete-guide-grid/) - A comprehensive guide to CSS Grid that I reference often.

## Author

- Website - [Your Website](https://your-site.com)
- Frontend Mentor - [@bhzeuscagd](https://www.frontendmentor.io/profile/bhzeuscagd)
- GitHub - [bhzeuscagd](https://github.com/bhzeuscagd)

## Acknowledgments

Thanks to Frontend Mentor for providing this challenge. It was a fun layout to implement!
