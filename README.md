# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). 

## Table of contents


- [The challenge](#the-challenge)
- [Screenshot](#screenshot)
- [Built with](#Built-with)





## The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./design/desktop-design.jpg)



### Built with

- Semantic HTML5 markup
- CSS variable
- Flexbox
- CSS Grid
- Mobile and Desktop Responsive Design




### What I learned
#### Defineing CSS Variable
```css
  :root{
--Dark-cyan: hsl(158, 36%, 37%);
--More-Dark-cyan: hsl(158, 36%, 28%);
--Cream: hsl(30, 38%, 92%);
}
```
#### Import Google Font Text
```css
@import url('https://fonts.googleapis.com/css2?family=DM+Sans:ital,opsz,wght@0,9..40,400;0,9..40,700;1,9..40,400;1,9..40,700&display=swap');
```

#### Responsive design for Desktop Version (Media Queries)  
```css
@media(min-width:620px){
  article{grid-template-columns: 1fr 1fr;
    min-width: 600px;
    max-width: 600px;
    
    position: absolute;
    top: 10%;
  } 
  }
```



