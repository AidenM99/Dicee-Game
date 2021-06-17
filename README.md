## Overview

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)

### The Project

- The aim of this project was to create a random number generator that displayed the generated numbers on two die on the screen followed by a text change to 
announce the winner. 

## Screenshot

![](./Dicee.png)

### Links

- Live Site URL: https://aidenm99.github.io/Dicee-Game/

### Built with

- HTML
- CSS
- JavaScript

### What I learned

- How Math.floor() and Math.random() work and using these to generate a random number

```js
let randomNumber1 = (Math.floor(Math.random()*6+1));
```

- Basic DOM Manipulation

```js
document.querySelector(".img1").setAttribute("src","images/dice"+randomNumber1+".png");
document.querySelector(".img2").setAttribute("src","images/dice"+randomNumber2+".png");
```

- How to use if statements

```js
if(randomNumber1>randomNumber2){
  document.querySelector("h1").innerHTML = ("🎆Player 1 Wins!");
}else if(randomNumber1<randomNumber2){
  document.querySelector("h1").innerHTML = ("🎇Player 2 Wins!");
}else{
  document.querySelector("h1").innerHTML = ("🎉It's a Draw!");
}
```

### Continued development

- I plan to dedicate the foreseeable future to learning and focussing on JavaScript and its many concepts which I will do by building more projects.
