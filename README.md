# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges helped me improve my coding skills by building realistic projects. 

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Screenshot

![](./design/desktop-design.jpg)

### Links

- Challenge URL: [Click here](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H)
- Live Site URL: [Click here](https://thedefiantone17.github.io/QR-Code_challenge_FrontEndMentor/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

the html structure included  Div(s) :
- box (container)
- a div for bar-code
- a title
- a paragraph

Snippets:

```html
<div class="box">
    <div class="bar-code">
      <img src="./images/image-qr-code.png" alt="">
    </div>
    <div class="title">
      <p>Improve your front-end skills by building projects</p>
    </div>
    <div class="QR-text">
      <p>Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
    </div>
  </div>
```
```css
.box{
    /* margin-top: 80px; */
    margin-top: 10%;
    margin-right: auto;
    margin-left: auto;
    margin-bottom: 0 ;
    width: 200px;
    height: 310px;
    border-radius: 10px;    
    justify-content: center;
    background-color: hsl(0, 0%, 100%);
    box-shadow: -5px 13px 13px -8px rgba(0,0,0,0.43);
}
.bar-code img{
    margin:10px 10px 10px 10px;
    width: 180px;
    border-radius: 10px;
    height: auto;
}

.title{
    font-weight: 700;
    font-size: 13px;
    text-align: center;
    width: 170px;
    margin:10px 10px 10px 10px;
}

.QR-text{
    font-weight: 400;
    font-size: 10px;
    text-align: center; 
    width: 170px;
    margin:10px 10px 10px 10px;
}

```

## Author

- Frontend Mentor - [@thedefiantone17](https://www.frontendmentor.io/profile/thedefiantone17)
- Twitter - [@aniketsharma_17](https://twitter.com/aniketsharma_17)

## Acknowledgments

I was inspired by my supportive friends [@Aaryan-kapur](https://github.com/Aaryan-kapur), [@aniketbiprojit](https://github.com/aniketbiprojit) and [@AbhinavRobinson](https://github.com/AbhinavRobinson), wherever i faced any difficulty they were there to help me out.

I would also like to thank [frontend Mentor](https://twitter.com/frontendmentor) for giving such opportunity to do such interesting challenges, and would also like to thanks [GreatLearning]() for guiding me with an educative journey towards IT industry.
