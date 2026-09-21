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
    - [Continued development](#continued-development)

## Overview
### This challenge
Users should be able to:
- See hover and focus states for all interactive elements on the page
### Screenshot
Mobile Version:
![](./images%20for%20README/mobile.png)
Tablet/Desktop Version:
![](./images%20for%20README/tablet%20and%20pc.png)
The hover and focus state: 
![](./images%20for%20README/hover%20state.png)
### Links 
- Solution URL: [GitHub Page for Solution](https://github.com/yarnileach2005-code/social-links-profile)
- Live Site URL: [Live Web page](https://yarnileach2005-code.github.io/social-links-profile/)

## My Process
### Built with
- Semantic HTML5 markup
- CSS custom properties 
- Flexbox
- Mobile-first workflow
- imported font-family
### What I learned 
I learned how to use imported files from a typeface locally saved on the computer.
```css
@font-face {
    font-family: "Inter Bold";
    src: url("assets/fonts/Inter-VariableFont_slnt,wght.ttf");
    font-weight: bold;
}
@font-face {
    font-family: "Inter";
    src: url("assets/fonts/Inter-VariableFont_slnt,wght.ttf");

}
```
I improved on how to structure code in a effective and easy to modify way:
```css
button{
    padding: 0.85rem;
    border-radius: 0.57rem;
    width: 100%;

    background-color: var(--grey-700);
    border: none;
    transition: color 1s , background-color 1s;
}

@media (min-width: 768px){
    article{
        width: 27.43rem;
        padding: 2.86rem ;
    }
    
}

button:hover{
    background-color: var(--green);
    color: var(--grey-700);

    transition: all 0.15s;

}
button:focus{
    background-color: var(--green);
    color: var(--grey-700);

    transition: all 0.15s;

}
.bio{
    font-family: Inter, sans-serif;
}
```
I better incorporated border box and used padding for proper formating. This helped me make a more dynamic code and made modifying the code easier. This is a lesson which has helped me incorporate these aspects into future projects.
```css
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

article{
    background-color: var(--grey-800);

    display: flex;
    flex-direction: column;
    gap: 1.71rem ;


    padding: 1.71rem;
    border-radius: 12px;

    width: 23.36rem;

}
```
I used an aria-label to improve accessibility:
``` HTML
    <nav aria-label="Social Media Links">
      <ul>
        <li><button>GitHub</button>  </li>
        <li><button>Frontend Mentor</button></li>
        <li><button>LinkedIn</button></li>
        <li><button>Twitter</button></li>
        <li><button>Instagram</button></li>
      </ul>
    </nav>
```
### Continued development
In future projects I would like to implement more responsive elements into the css for a more fluid wep page. Furthermore,   I would like to focus on the more semantic features of HTML like ARIA labels.
