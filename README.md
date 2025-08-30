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
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

This is a small website showcasing an image of a QR code with some stylized text underneath it, all inside a white rectangle in the middle of the screen. All using only HTML and CSS.


### Screenshot

![](images/screenshot.jpg)


### Links

- Solution URL: [Repository](https://github.com/winceh7/QR-Code)
- Live Site URL: [QR Code Web Page](https://winceh7.github.io/QR-Code/)


## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned

The challenge being recreating the design, having to center elements made me learn how to use Flexbox and CSS Grids with the display property along with combining it with other properties in order to align the elements inside the box and the contents of each. A key, in my case when researching, was the transform property as it gave me the missing piece to center the design.

```css
.card {
    width: 100%;
    max-width: 340px;
    height: 60%;
    background-color: white;
    border-radius: 20px;
    transform: translate(0, 50%);
}
```
As there was only going to be one central element, I decided to work without margins setting the box-size to the border of the box.
```css
div {
    box-sizing: border-box;
}
```

 A key point for the development was the responsiveness of the web page as I wanted it to be visible for small and big screens.

```css
.container{
    min-width: 300px;
    width: 100%;
    display: flex;
    justify-content: center;
}
```

As a beginner Front-end Developer I have a long way to go with a lot to learn and develop my skillset. This project helped me put into a broader perspective how well each element must interact with each other through correct syntax and use of tags in order for a web page to work and look as intended. The importance of the communication between the HTML code and CSS for stylization as the project was developed using only these languages.


### Continued development

For future projects I plan on practicing with the layout systems as well as trying to see ways to customize and stylize the projects combining different libraries to develop websites, web pages and web apps with a more complex design.


### Useful resources

- [Why you should always set responsive mode to 320px when checking "mobile layout" on your web pages](https://dev.to/lebbe/why-you-should-always-set-responsive-mode-to-320px-when-checking-mobile-layout-on-your-web-pages-3gd9) - This helped me understand and gave me some insight on the requirement for testing on mobile layouts.
- [Why you should choose HTML5 article over section](https://www.smashingmagazine.com/2020/01/html5-article-section/) - This is an amazing article which helped me finally understand the differences between div, section and article.
- [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS) - This helped me explore any properties, selectors and elements that might be unknown to me as well as layout and guide systems like Flexbox and CSS Grids.


## Author

- GitHub - [winceh7](https://github.com/winceh7)
- Frontend Mentor - [@winceh7](https://www.frontendmentor.io/profile/winceh7)


## Acknowledgments

Thankful with Frontend Mentor for having this challenge for free and letting me practice my skills and help me grow as a beginner Front-End Developer.
