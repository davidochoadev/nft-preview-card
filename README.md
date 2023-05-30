# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./design/desktop-design.jpg)

### Links

- Solution URL: [https://github.com/davidochoadev/nft-preview-card](https://github.com/davidochoadev/nft-preview-card)
- Live Site URL: [https://davidochoadev.github.io/nft-preview-card/](https://davidochoadev.github.io/nft-preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned

I have reviewed the main properties of flex and grid and encountered some issues with the hovering effect on the parent element. However, I managed to solve it by applying the background-image property to the parent element and adding a blur effect to the image.

During my learning process, I gained a deeper understanding of the flex and grid layout systems. These powerful CSS features have enabled me to create more flexible and responsive designs for web pages. With flexbox, I learned how to easily align and distribute elements within a container, allowing for dynamic and adaptive layouts. Grid layout, on the other hand, provided me with the ability to create complex two-dimensional layouts, defining both rows and columns for precise positioning of elements.

By applying the background-image property and adding a blur effect, I was able to enhance the visual appearance of the parent element. This technique allowed me to display an image as the background of the container and apply various effects to create a visually engaging hovering effect. The blur effect added a touch of elegance and depth to the overall design, enhancing the user experience.

This experience has solidified my understanding of CSS layout systems and expanded my skills in creating visually appealing and interactive web pages. By utilizing flexbox, grid, and advanced CSS properties like background-image and blur effects, I am now equipped to tackle more sophisticated design challenges and create stunning user interfaces.
```css
.img__container {
  margin-bottom: 15px;
  border-radius: 10px;
  min-width: 300px;
  height: 300px;
  background: url(../images/image-equilibrium.jpg);
  background-size: 100%;
  overflow: hidden;
}
```

### Continued development

I want to enhance my skills in grid layout as part of my ongoing development. Grid layout allows for precise control over element placement and alignment, resulting in visually appealing and adaptable designs. By further exploring grid features and techniques, I aim to create responsive and efficient layouts that deliver a seamless user experience. Mastery of grid layout will empower me to streamline the design process and ensure consistency across different devices. Continued development in this area reflects my commitment to staying up-to-date with modern web design practices.

## Author

- Website - [davidochoa.dev](https://davidochoa.fly.dev)
- Frontend Mentor - [@davidochoadev](https://www.frontendmentor.io/profile/davidochoadev)
