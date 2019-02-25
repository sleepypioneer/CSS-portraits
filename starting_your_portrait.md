# Walk through
### Part 1: setting up the positioning & adding first elements
* [Walk through pt. 1](https://codepen.io/sleepypioneer/pen/RvXyQq)

#### HTML:  

`<div id="frame">`  
  `<div id="head">`  
  `</div><!-- head -->`  
  `<div id="body"></div><!-- body -->`  
  `<div id="bodyextension"></div><!-- body -->`  
`</div>` 

#### CSS:  

`body {`  
  `background: #231E1E;`  
`}`  

`#frame {`  
    `position: absolute;`  
    `top: 20%;`  
    `left: 30%;`  
    `background: #B73E4A;`  
    `height: 15rem;`  
    `width: 15rem;`  
    `z-index: -10;`  
    `border: 0.2rem white solid;`  
    `border-radius: 100%;`  
    `overflow: hidden;`  
`}`  

`#head {`  
    `display: block;`  
    `position: relative;`  
    `top: 25%;`  
    `left: 35%;`  
    `height: 5rem;`  
    `width: 6rem;`  
    `background: #935D37;`  
    `border-top-right-radius: 5px;`  
    `border-top-left-radius: 5px;`  
    `border-bottom-right-radius: 50px;`  
    `border-bottom-left-radius: 50px;`  
`}`  

 `div#body {`  
    `position: relative;`  
    `top: 25%;`  
    `left: 26%;`  
    `border-radius: 100%;`  
    `background: #78B9C1;`  
    `height: 8rem;`  
    `width: 9rem;`  
    `border-top-right-radius: 3rem;`  
    `z-index: -3;`  
    `border-top-left-radius: 3rem;`  
    `box-shadow: inset 7px 20px 0 20px #78B9C1;`  
`}`  

`div#bodyextension {`  
    `height: 2em;`  
    `width: 3.3em;`  
    `position: relative;`  
    `background: #78B9C1;`  
    `border-left: dotted #78B9C1 1rem;`  
    `z-index: -2;`  
    `top: -22%;`  
    `left: 44.5%;`  
    `border-top-right-radius: 100%;`  
    `box-shadow: #78B9C1 20px -2px 0 10px;`  
`}` 

<img src="/imgs/pt1.JPG" alt="Walk through Pt 1" height="200" /> 

#### Part 2: Adding more shapes and building form
* [Walk through pt. 12](https://codepen.io/sleepypioneer/pen/LqwrEX)
#### HTML: 

`<div id="frame">`  
  `<div id="head">`  
    `<div id="neck"></div><!-- neck -->`  
    `<div id="fringe"></div><!-- fringe -->`  
    `<div class="hair"></div><!-- hair -->`  
    `<div class="hair hair2"></div><!-- hair2 -->`  
    `<div class="hair hair3"></div><!-- hair3 -->`  
  `</div><!-- head -->`  
  `<div id="body"></div><!-- body -->`  
  `<div id="bodyextension"></div><!-- body -->`  
`</div>`  

#### CSS:

`div #neck {`  
    `background: #78B9C1;`  
    `height: 2rem;`  
    `width: 3rem;`  
    `position: relative;`  
    `top: 60%;`  
    `z-index: -1;`  
    `left: 26%;`  
    `border-bottom-left-radius: 50%;`  
    `border-bottom-right-radius: 50%;`  
    `box-shadow: 0px 14px 0 2px #78B9C1;`  
`}`  

`#fringe{`  
    `display: block;`  
    `position: relative;`  
    `top: -90%;`  
    `left: -4%;`  
    `height: 3rem;`  
    `width: 6.5rem;`  
    `background: black;`  
    `border-bottom-right-radius: 5px;`  
    `border-bottom-left-radius: 5px;`  
    `border-top-right-radius: 50px;`  
    `border-top-left-radius: 50px;`  
`}`  

`.hair {`  
  `width: 50px;`  
  `height: 50px;`  
  `background: black;`  
  `border-radius: 50%;`  
  `position: relative;`  
  `z-index: -1;`  
  `left: -5px;`  
  `top: -50px;`  
`}`  

`.hair2 {`  
  `width: 40px;`  
  `height: 40px;`  
  `left: 0px;`  
`}`  

`.hair3 {`  
  `width: 30px;`  
  `height: 30px;`  
  `left: 5px;`  
`}`  

<img src="/imgs/pt2.JPG" alt="Walk through Pt 2" height="200" /> 

#### Part 3: Details
* [Walk through pt. 3](https://codepen.io/sleepypioneer/pen/NJKbNx)

#### HTML: 

`<div id="frame">`  
  `<div id="head">`  
    `<div id="neck"></div><!-- neck -->`  
    `<div id="fringe"></div><!-- fringe -->`  
    `<div class="hair"></div><!-- hair -->`  
    `<div class="hair hair2"></div><!-- hair2 -->`  
    `<div class="hair hair3"></div><!-- hair3 -->`  
    `<div class="hair hair4"></div><!-- hair4 -->`  
    `<div class="ears"></div><!-- ears -->`  
    `<div class="ears rightear"></div><!-- ears -->`  
    `<div class="eye">`  
    `</div><!--eyes -->`  
    `<div class="eye righteye">`  
    `<div><!--eyes right -->`  
    `<div id="mouth"></div><!-- mouth -->`  
    `<div class="nose"></div><!-- nose -->`  
  `</div><!-- head -->`  
  `<div id="body"></div><!-- body -->`  
  `<div id="bodyextension"></div><!-- body -->`  
`</div>`  

#### CSS:

`div.eye {`  
    `width: 10px;`  
    `height: 12px;`  
    `border-radius: 100%;`  
    `background: #040302;`  
    `position: relative;`  
    `top: -244px;`  
    `left: 20px;`  
    `z-index: 2;`  
`}`  

`div.eye.righteye {`  
    `top: -256px;`  
    `left: 68px;`  
`}`  

`div#mouth {`  
    `background: black;`  
    `height: 20px;`  
    `width: 40px;`  
    `border-bottom-left-radius: 40px;`  
    `border-bottom-right-radius: 40px;`  
    `position: relative;`  
    `top: -300%;`  
    `left: 31%;`   
`}`  

`div#mouth::before {`  
    `display: block;`  
    `background: #c68e66;`  
    `width: 25px;`  
    `height: 15px;`  
    `content: '';`  
    `border-bottom-left-radius: 20px;`  
    `border-bottom-right-radius: 60px;`  
    `position: relative;`  
    `top: 20%;`  
    `left: 34%;`  
    `border-top-left-radius: 40px;`  
`}`  

`.nose {`  
    `position: relative;`  
    `top: -348%;`  
    `left: 45%;`  
    `border-radius: 80%;`  
    `height: 8px;`  
    `width: 12px;`  
    `background-color: #935D37;`  
    `border-bottom: #21150c solid 2px;`  
`}`   

<img src="/imgs/pt3.JPG" alt="Walk through Pt 3" height="200" /> 

|⏭️ [next steps](/next_steps.md)|🏠 [back to main page](/README.md)|
|:-----------------------------------------------: |:-----------------------------------------------: |   
