## What is specificity? 🎯

*“If there are two or more conflicting CSS rules that point to the same element, the browser follows some rules to determine which one is most specific and therefore wins out.”*


### Inline styles 
- An inline style is attached directly to the element to be styled. Example: `<h1 style="color: #ffffff;">`  

### IDs 
- An ID is a unique identifier for the page elements, such as `#navbar` 

### Classes, attributes and pseudo-classes 
- This category includes .classes, attributes and pseudo-classes such as `:hover`, `:focus` etc.  

### Elements and pseudo-elements 
- This category includes element names and pseudo-elements, such as `h1`, `div`, `:before` and `:after`.

### Children Vs Decendants
- `ul li` selects any list items that are anywhere underneath an unordered list in the markup structure. The list item could be buried three levels deep within other nested lists, and this selector will still match it. 
- `ul > li` will only select list items that are direct children of an unordered list. In otherwords, it only looks one level down the markup structure, no deeper. 
  
---

## Calculating specificity 🔢

<img src="/imgs/specificitycalc.png" alt="Specificity calculator" height="200" />  

###### Borrowed from http://www.anieto2k.com  

Start at 0, add 1000 for style attribute, add 100 for each ID, add 10 for each attribute, class or pseudo-class, add 1 for each element name or pseudo-element.

* A: `h1`
* B: `#content h1`
* C: `<div id="content"><h1 style="color: #ffffff">Heading</h1></div>`

The specificity of A is 1 (one element)  
The specificity of B is 101 (one ID reference and one element)  
The specificity of C is 1000 (inline styling)  

Since 1 < 101 < 1000, the third rule (C) has a greater level of specificity, and therefore will be applied.
###### *Equal specificity? ~The latest rule counts*

<img src="/imgs/your_turn.jpg" alt="Your Turn" height="200" /> 
Given the following HTML which CSS rule A, B, C applies the style?

`<div class="parent">`  
  `<div style="color: blue">`  
    `<div id="child">COLOUR ME</div>`  
  `</div>`  
`</div>`  

A.  
`.parent div {
  color: red  
  }`  
  
B.  
`.parent > #child {  
  color: green  
}`  

C.  
`div #child {
  color: pink  
  }`
  
Open this pen to check your answer :) https://codepen.io/sleepypioneer/pen/bzyPem

---

## Resources 📚

http://cssspecificity.com/  
https://www.w3schools.com/css/css_specificity.asp  
https://specificity.keegan.st/  

  
|⏭️ [next up pseudo elements](/pseudo_elements.md) | 🏠 [back to main page](/README.md) |
|:-----------------------------------------------: | :--------------------------------: |
