# Frontend Mentor - Article preview component solution

This is a solution to the [Article preview component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/article-preview-component-dYBN_pYFT). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
- [Author](#author)

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See the social media share links when they click the share icon

### Screenshot

![](https://raw.githubusercontent.com/seekinfox/Article-preview-cpmponent/main/Screenshot_2021-09-15%20Frontend%20Mentor%20Article%20preview%20component(1).png)
![](https://raw.githubusercontent.com/seekinfox/Article-preview-cpmponent/main/active-mobile.png)
![](https://raw.githubusercontent.com/seekinfox/Article-preview-cpmponent/main/Screenshot_2021-09-15%20Frontend%20Mentor%20Article%20preview%20component.png)
![](https://raw.githubusercontent.com/seekinfox/Article-preview-cpmponent/main/active-desktop.png)

### Links

- Solution URL: [https://github.com/seekinfox/Article-preview-cpmponent](https://github.com/seekinfox/Article-preview-cpmponent)
- Live Site URL: [https://seekinfox.github.io/Article-preview-cpmponent/](https://seekinfox.github.io/Article-preview-cpmponent/)



### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
-javaScript

### What I learned

applying little bit of javaScript to make a card more interactive is fun thing to learn.
In this exercise i learned how to add event triggers and toggle classes.
i used these two function to get the click event and the share-popup section. 
```js
function myFunction() {
    var popup = document.getElementById("myPopup");
    popup.classList.toggle("visible");
}

const color = document.querySelectorAll(".share");
color.forEach(color => {
    color.addEventListener("click", ()=>{
        color.classList.toggle("color");
    });   
});
}
```

### Continued development


 redoing javaScript basics.



## Author


- Frontend Mentor - [@seekinfox](https://www.frontendmentor.io/profile/seekinfox)


