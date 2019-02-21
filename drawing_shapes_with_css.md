# Drawing Shapes with CSS ⭐

<img src="/imgs/shapes1.png" alt="Shapes in CSS" height="200" />

"There are others we can create with CSS, but most things can be simplified to some combination of these shapes. And these are the easiest to create and manipulate." *@lynnandtonic*


#### Square
`<div id="square"></div>`  
 ` #square {`  
      `width: 100px;`  
      `height: 100px;`  
      `background: red;`  
    `}`  

#### Rectangle
`<div id="rectangle"></div>`  
`#rectangle {`  
  `width: 200px;`  
  `height: 100px;`  
  `background: red;`  
`}`  

#### Circle
`<div id="circle"></div>`  
`#circle {`  
  `width: 100px;`  
  `height: 100px;`  
  `background: red;`  
  `border-radius: 50%`  
`}`  


#### Oval
`<div id="oval"></div>`  
`#oval {`  
  `width: 200px;`  
  `height: 100px;`  
  `background: red;`  
  `border-radius: 100px / 50px;`  
`}`  

#### Triangle
`<div id="triangle"></div>`  
`#triangle {`  
  `width: 0;`  
  `height: 0;`  
  `border-left: 50px solid transparent;`  
  `border-right: 50px solid transparent;`  
  `border-bottom: 100px solid red;`  
`}`  


#### Trapezoid
`<div id="trapezoid"></div>`  
`#trapezoid {`  
  `border-bottom: 100px solid red;`  
  `border-left: 25px solid transparent;`  
  `border-right: 25px solid transparent;`  
  `height: 0;`  
  `width: 100px;`  
`}`  

You can see these all here: https://codepen.io/sleepypioneer/pen/OdYeva

And find many more here: https://css-tricks.com/the-shapes-of-css/

## Multiples of the same shape using box-shadows
With multiple box-shadows, we can create many versions of the same shape in varying size, color, and blur. Offsetting them on the x- and y-axes gives us almost endless multiples.

<img src="/imgs/multiplyshape.png" alt="Multipy shapes from one" height="200" />

`div {  
    box-shadow: 170px 0 10px yellow,  
                330px 0 0 -20px blue,  
                330px 5px 5px -20px black;  
}`

We can even give our box-shadows box-shadows. <b>Pay attention to the order they are declared.</b> 
Again, It’s helpful to think of them as layers.

---

#### Resources 📚

* https://css-tricks.com/the-shapes-of-css/
* https://spyrestudios.com/draw-with-css-using-css-to-draw-elements/


|⏭️ [Adding shading with gradients](/gradients.md) | 🏠 [back to main page](/README.md)|
|:-----------------------------------------------: |:-----------------------------------------------: |    
