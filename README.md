# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements



### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

 Built with 

- HTML5
- CSS
- Flexbox
- Mobile-first workflow


What I learned

Well here I learned to work with the names of the classes in English, to use rem measures, to better understand how transition works, I also
learned to use media query and what I am proud of is the following code:
   -------------HTML-----------   
<div>
  <img src="/images/image-equilibrium.jpg" alt="Equilibrium" class="equilibrium-image">
  <div class="icon-container">
    <img src="/images/eye.png" class="eye-icon" alt="eye-icon">
  </div>
</div>
-------------css-----------   
.equilibrium-image{
  position: absolute;
  height: 280px; 
  width: 280px;
  border-radius: 0.5rem;  
}
.icon-container{
  position: relative;
  height: 280px;
  width: 280px;
  margin-bottom: 1.5rem;
  border-radius: 0.5rem;
  background-color: hsla(178, 100%, 50%, 0.527);
  opacity: 0;
  -webkit-transition: all 1s ease;
	-moz-transition: all 1s ease;
	-ms-transition: all 1s ease;
	-o-transition: all 1s ease;
	transition: all 1s ease;
}
.icon-container:hover{
  opacity: 0.9;
  cursor: pointer;
}
.eye-icon{
  position: absolute;
  top: 117px;
  left: 117px;
  -webkit-transition: all 1s ease;
	-moz-transition: all 1s ease;
	-ms-transition: all 1s ease;
	-o-transition: all 1s ease;
	transition: all 1s ease;
}

Which was the one that allowed me to make the effect that when hovering the mouse over the photo the translucent background appears with the icon in the middle.


### Continued development

What I want to continue focusing on for my next projects is responsive design and more complex transitions.
