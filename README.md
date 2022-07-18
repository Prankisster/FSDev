
# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). 
Frontend Mentor challenges help you improve your coding skills by building realistic projects.


## Table of contents

- [Overview](#overview)
    - [Screenshot](#screenshot)
    - [Links](#links)

- [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Continued development](#continued-development)


## Overview


### Screenshot

![](https://user-images.githubusercontent.com/92308896/179468204-dc1783eb-21db-4f91-8718-e3a9b021b16b.png)

### Links

- Solution URL: [Add solution URL here](https://github.com/Prankisster/FSDev/blob/main/Index.html)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process


### Built with

- Semantic HTML5 markup
- CSS custom properties
- [Styled Components](https://fonts.google.com/specimen/Outfit) - For styles


### What I learned

Using this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas I want to highlight

```html

/*Realised that div can be used to group certain elements and to divide them from the rest*/

<div class="bgw center">
    
    
    <div class="bgb">
      
        <img class="bgb" src=".\image-qr-code.png" alt="QR Code">
    
    </div>

  
    <div class="writtenHead">
   
        <h3 class="head"><b>Improve your front-end skills by building projects</b></h3>
    
    </div>

    
  <div class="writtenPara">
      
        <p class="para">Scan the QR code to visit Frontend Mentor and take your coding skills to  the next level</p>
    
    </div>
</div>

```

```css
/*This is how you position an element to the center(of page)*/
  .center 
        {
            position: absolute;
            left: 50%;
            top: 50%;
            transform: translate(-50%, -50%);
            padding: 10px;
        }```
 
 /*-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x--x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-*/

/*This is how you insert a favicon (A favicon is a kind of display image/picture that is displayed on the browser-tab beside the title of the page)*/
<head>
  <link rel="icon" type="image/x-icon" href=".\favicon-32x32.png">
</head>
```
This also made me put the theory into use and distinguish among the usage of borders, padding & margins.


### Continued development

I would take this opportunity to state that I would like to further focus on minute details that are often overlooked and to practice more on the distinct usage of padding, borders & margins.

