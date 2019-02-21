# Pseudo elements
With one div in the HTML, we actually have three elements to work with because of CSS pseudo classes. 
So with div, div:before, and div:after, we can get something like this:


 <img src="/imgs/pseudo1.png" alt="Pseudo Elements" height="200" />

  `div { background: red; }`  
  `div:before { background: yellow; }`  
  `div:after { background: blue; }`  
  
  
It helps to think about these three elements as things that can come in sequence and as three stackable layers. 
So you can imagine it more like this:

 <img src="/imgs/pseudo2.png" alt="Pseudo Elements envisioned" height="200" />
 
For each of these pseudo elements we can add styling, including radius and shadows which allows us to create even more shapes from a single `<div>` 🖤


### Resources 📚


Tutorial from Lynne Fisher: [https://hacks.mozilla.org/2014/09/single-div-drawings-with-css/](https://hacks.mozilla.org/2014/09/single-div-drawings-with-css/)

||⏭️ [next up drawing shapes with CSS](/drawing_shapes_with_css.md)|🏠 [back to main page](/README.md)|
|:-----------------------------------------------: |:-----------------------------------------------: |   
