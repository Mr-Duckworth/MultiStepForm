# Frontend Mentor - Multi-step form solution

This is a solution to the [Multi-step form challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/multistep-form-YVAnSdqQBJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- Complete each step of the sequence
- Go back to a previous step to update their selections
- See a summary of their selections on the final step and confirm their order
- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page
- Receive form validation messages if:
  - A field has been missed
  - The email address is not formatted correctly
  - A step is submitted, but no selection has been made


### Links

- Solution URL:(https://github.com/Mr-Duckworth/MultiStepForm.git)
- Desktop Live Site URL: (https://mr-duckworth.github.io/desktop/)
- Mobile Live Site URL: (https://mr-duckworth.github.io/mobile/)

## My process
I could have completed it sooner if i had made use of frameworks like react and next js but i choose to use the html + bootstrap + css + js which made it a tard bit harder but i was able to figure it out at every step i was stuck with the help of google and stackoverflow 

I started off with the desktop interface with html creeating navbar first and form for each step and breaking parts into sections and divs while making of bootstrap framework then i went ahead to create a css file with styleing for each elements of the html with live updating of each styles during the whole process and then come the functionality with javascript, this part took me the longest and consuming most of my brain power but i was able to figure it out with the help of youtube and google after which i decide to head to the mobile interface which was more simpler using thw same step like the desktop but with few changes

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Bootstrap 


### What I learned

The most new thing i learned was about how one is able to call a javascript function in a html element

like below:

```html
<input class="form-check-input" type="checkbox" role="switch" name="" id="stepTwoSwitch" onchange="getChecked()">
```
```
```
```js
function getChecked() {
    const check = toggle.checked;
    if (check === true ){
        $(".monthly").removeClass("active");
        $(".yearly").addClass("active");
        $(".add-ons-monthly").removeClass("active");
        $(".add-ons-yearly").addClass("active")
        total.innerHTML = "Total (per year)"
    } else {
        $(".monthly").addClass("active");
        $(".yearly").removeClass("active");
        $(".add-ons-monthly").addClass("active");
        $(".add-ons-yearly").removeClass("active")
    }
}

```


### Continued development
I plan on continue development on the form validation process 

### Useful resources

- Google and Youtube and Stackflow - This helped me when i was stuck on some parts 

## Author

- Website - [Aloba Tobiloba](under construction)
- Frontend Mentor - [@Mr-Duckworth](https://www.frontendmentor.io/profile/Mr-Duckworth)
- Twitter - [@aLife_ofArt](https://twitter.com/aLife_ofArt)


