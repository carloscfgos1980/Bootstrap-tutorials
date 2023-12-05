## Lesson 5. Utility classes
https://www.youtube.com/watch?v=nCeHeA7IsvU&list=PL4cUxeGkcC9joIM91nLzd_qaH_AimmdAR&index=5

# Location in Mac:
/Users/carlosinfante/Desktop/coding-projects/winc-academy/frontend-course/MODULE9 - DEBUGGING and DOMAIN MODELING/REVIEW/Bootstrap/bootstrap-The_Net_Ninja
* There are a bunch of lessons. This is the root file

# Location in GitHub:
https://github.com/carloscfgos1980/Bootstrap-JavaScript-NetNinja-tutorial

# Goals:
- Classes: margin, padding, borders, box shadow, font weight

5.1 <!-- margin & padding -->
  <div class="my-3 px-5 bg-primary">margin in y dir, padding in x dir</div>
  N: "my" means marging top and button. Y axis
        "px" means padding to the left and right. X Axis
  <div class="mt-3 mb-4 ps-5 pt-4 pe-2 pb-1 bg-primary">m & p for each direction</div>
  N: t => top. Ex "mt" means margin top
    b => botton. Ex: "mb" means margin botton
    s => start (left). Ex: "ps" means padding left
    e => end (right). Ex: "pe" means padding right

5.2 <!-- borders -->
  <div class="m-3 p-3 border-start border-danger border-5">thicker border</div>
  N: In the above example we apply margin, padding, color (danger) and a thick border to the left. If one to apply border everywhere we simply do "border" instead of "border-start". 
  <div class="m-3 p-3 rounded border border-5">rounded corners</div>
  <div class="m-3 p-3 rounded-pill border border-5">rounded corners</div>
  N: this is is very cool!

5.3 <!-- box shadow -->
<div class="m-3 p-3 shadow-sm">element with small shadow</div>
N: "sm" stands for small shadow

5.4<!-- font weight -->
  <p class="fst-italic fw-light">italic light text</p>
  N: "fst" - type of letter.
  "fw"- thickness of the letter
