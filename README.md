# CSS-portraits
Workshop for WWC about building cute cartoon portraits with CSS &amp; HTML

## Inspiration

[https://a.singlediv.com/](https://a.singlediv.com/)
[http://diana-adrianne.com/](http://diana-adrianne.com/)



## Why not make portraits in CSS?

* SVGs
* Time consuming
* SVGs

## Why make portraits in CSS?

* It’s fun
* It helps you understand specificity better
* It helps you get to grips with alternative uses for some CSS properties
* It’s fun :)

## What is specificity?

*“If there are two or more conflicting CSS rules that point to the same element, the browser follows some rules to determine which one is most specific and therefore wins out.”*

rank/ score

### Inline styles 
- An inline style is attached directly to the element to be styled. Example: `<h1 style="color: #ffffff;">`
### IDs 
- An ID is a unique identifier for the page elements, such as #navbar.
### Classes, attributes and pseudo-classes 
- This category includes .classes, attributes and pseudo-classes such as `:hover`, `:focus` etc.
### Elements and pseudo-elements 
- This category includes element names and pseudo-elements, such as h1, div, :before and :after.
  

## Calculating specificity

Start at 0, add 1000 for style attribute, add 100 for each ID, add 10 for each attribute, class or pseudo-class, add 1 for each element name or pseudo-element.

* A: `h1`
* B: `#content h1`
* C: `<div id="content"><h1 style="color: #ffffff">Heading</h1></div>`

The specificity of A is 1 (one element)
The specificity of B is 101 (one ID reference and one element)
The specificity of C is 1000 (inline styling)

Since 1 < 101 < 1000, the third rule (C) has a greater level of specificity, and therefore will be applied.

### *Equal specificity: the latest rule counts*


## Resources:
http://cssspecificity.com/
https://www.w3schools.com/css/css_specificity.asp
https://specificity.keegan.st/


## Setting up for the workshop
You will need an free account from [https://codepen.io/](https://codepen.io/)
