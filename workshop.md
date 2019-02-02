# Pseudo elements
With one div in the HTML, I actually have three elements to work with because of CSS pseudo classes. 
So with div, div:before, and div:after, we can get something like this:

## pseudo elements

  `div { background: red; }`  
  `div:before { background: yellow; }`  
  `div:after { background: blue; }`  
  
  
It helps to think about these three elements as things that can come in sequence and as three stackable layers. 
So in my mind, it would usually look more like this:

With CSS and one element, we are afforded three basic shape types. We can use width and height properties to create squares/rectangles, border-radius to create circles/ellipses, and border to create triangles/trapezoids.

## css shapes

There are others we can create with CSS, but most things can be simplified to some combination of these shapes. And these are the easiest to create and manipulate.

## Multiples of the same shape
With multiple box-shadows, we can create many versions of the same shape in varying size, color, and blur. Offsetting them on the x- and y-axes gives us almost endless multiples.

multiple box-shadows

`div {  
    box-shadow: 170px 0 10px yellow,  
                330px 0 0 -20px blue,  
                330px 5px 5px -20px black;  
}`

We can even give our box-shadows box-shadows. Pay attention to the order they are declared. 
Again, It’s helpful to think of them as layers.

## Gradients

Gradients can be used to add shading and depth by implying a light source. This makes the simple, flat shapes feel more realistic. 
Combining multiple background-images allows us to use many, layered gradients to achieve more complex shading and even more shapes.



## Dev Tool

https://chrome.google.com/webstore/detail/css-gradient-inspector/blklpjonlhpakchaahdnkcjkfmccmdik

## Resources

Tutorial from Lynne Fisher: [https://hacks.mozilla.org/2014/09/single-div-drawings-with-css/](https://hacks.mozilla.org/2014/09/single-div-drawings-with-css/)
