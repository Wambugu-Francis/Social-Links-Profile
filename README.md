# Social-Links-Profile
 Asite for the social links profile
# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Author](#author)


**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](images/Screenshot%202024-10-23%20103755.jpg)

### Links

- Solution URL: (https://wambugu-francis.github.io/Social-Links-Profile/)
- Live Site URL:(https://wambugu-francis.github.io/Social-Links-Profile/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties

### What I learned

Basic button styling together with incorporating the hoover effects.
```css
button {
    background-color: hsl(0, 0%, 20%); /* Original background color */
    color:  hsl(0, 0%, 100%);              /* Text color */
    height: 42px;
    width: 300px;
    text-align: center;        /* Centered text */
    text-decoration: none;     /* No underline */
    display: inline-block;     /* Inline block display */
    font-size: medium;          /* Font size */
    font-weight: bold;
    cursor: pointer;           /* Pointer cursor on hover */
    border: 1px solid  hsl(0, 0%, 20%);              /* No border */
    border-radius: 10px;       /* Rounded corners */
    a{
        color: hsl(0, 0%, 100%);
        text-decoration: none;
    }
    
}

/* Change background color on hover */
button:hover {
    background-color: hsl(75, 94%, 57%); /* New background color on hover */
}


## Author
- Frontend Mentor - [@Wambugu-Francis](https://www.frontendmentor.io/profile/Wambugu-Francis)
