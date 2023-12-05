## Bootstrap 5 Crash Course Tutorial #4 - Buttons & Button Groups
https://www.youtube.com/watch?v=ZZXGmoQ4PdI&list=PL4cUxeGkcC9joIM91nLzd_qaH_AimmdAR&index=4

Location in Mac:
/Users/carlosinfante/Desktop/coding-projects/winc-academy/frontend-course/MODULE9 - DEBUGGING and DOMAIN MODELING/REVIEW/Bootstrap

Location in GitHub:
https://github.com/carloscfgos1980/Bootstrap-JavaScript-NetNinja-tutorial/

# Goals:
- Buttons: basic, anchor tag, size, outline(hover)

<!-- basic buttons -->

Ex:
<button class="btn btn-primary">primary button</button> <!-- auto lightens text -->

<!-- anchor tags as buttons -->

Ex:
<a href="#" class="btn btn-success">success anchor tag</a>
N: The color of the letters will swith from white to black, depending the background color

<!-- button sizes -->

Ex:
<button class="btn btn-sm btn-warning">small warning button</button>

<!-- outlined styles -->

Ex:
<button class="btn btn-outline-primary">outlined button</button>
N: When we hover over the button it will change to the color we have chosen, in this case primary color which is blue.

<!-- button groups -->

N: When we use a div to group the buttons, they dont have space in-between

  <div class="btn-group">
    <a href="#" class="btn btn-primary">button 1</a>
    <a href="#" class="btn btn-warning">button 2</a>
    <a href="#" class="btn btn-success">button 3</a>
  </div>
