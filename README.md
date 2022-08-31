# Manage landing page solution

This is a solution to the [Manage landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/manage-landing-page-SLXqC6P5). . 

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

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page
- See all testimonials in a horizontal slider
- Receive an error message when the newsletter sign up `form` is submitted if:
  - The `input` field is empty
  - The email address is not formatted correctly

### Screenshot

## Desktop Screenshot
![](./images/Screenshot%20desktop-view.png)

## Mobile Screenshot
![](./images/Screenshot%20mobile.png)

## Mobile Nav
![](./images/Screenshot%20mobile-nav.png)


### Links

- Solution URL: [Manage Landing Page](https://your-solution-url.com)
- Live Site URL: [Manage Landing Page](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [Tailwindcss Docs](https://tailwindcss.com) - CSS framework


### What I learned

This is my first project using TailwindCss. Learnt how to use classes to style my page without having to leave my HTML file.
Also learnt how to toggle the hamburger menu with JS.


```html 
<button class="py-3 px-8 bg-brightRed rounded-full text-white shadow-xl hover:bg-brightRedLight focus:outline-none border-none">
  A button with tailwind classes
</button>
``` 

```js
btn.addEventListener('click', () => {
  btn.classList.toggle('open')
  nav.classList.toggle('flex')
  nav.classList.toggle('hidden')
})
```

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.



### Useful resources

- [Tailwindcss Docs](https://tailwindcss.com) - This is my first time using tailwindcss, so i sourced out for the official documentation. Was really helpful.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.


## Author

- Website - [Cybprom](https://www.your-site.com)
- Frontend Mentor - [@cybprom](https://www.frontendmentor.io/profile/cybprom)
- Twitter - [@cybprom](https://www.twitter.com/cybprom)


## Acknowledgments



