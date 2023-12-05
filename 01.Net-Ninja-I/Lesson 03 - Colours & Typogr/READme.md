# Lesson 3. Color and Typography
https://www.youtube.com/watch?v=iUCyU_U0J2E&list=PL4cUxeGkcC9joIM91nLzd_qaH_AimmdAR&index=3
Location in Mac:
/Users/carlosinfante/Desktop/coding-projects/winc-academy/frontend-course/MODULE9 - DEBUGGING and DOMAIN MODELING/REVIEW/Bootstrap

Location in GitHub:
https://github.com/carloscfgos1980/Bootstrap-JavaScript-NetNinja-tutorial/

# Goals:
- Text style: headings, display, lead & alignment, text decorarion & font weight, colors, background colors
  
# Steps
3.1 <!--  heading tags -->
* We can give am especific class to the header. Ex
     <h2 class="h3">this is an 2 with an h3 class</h2>
   It is a bit of boiler plate coz we can simple write like this:
     <h3>this is an h3</h3>

3.2 <!-- display headings -->
* Give the style of heading to an element. It doesnt have to be a heading <h1>. Ex:
   <h1 class="display-1">display 1 heading</h1>
   <p class="display-1">paragraph with display-1 class</p>

3.3 <!-- lead text & alignment -->
* is a little bit bigger than a paraph
   Ex:
  <p class="lead text-center">hello ninjas</p>
  <p class="lead text-end">hello ninjas</p>
  <p class="lead text-start">hello ninjas</p> // This one we do not need to apply text-start becasue it is like that by default

3.4 <!-- text decoration & font weight -->
  <p class="text-decoration-underline">this is underlined text</p>
  <p class="text-decoration-line-through">this is line-through text</p>
  <p class="fw-bold">this bold text</p>
  <small>this is small text</small>

3.5 <!-- text colours -->
* Bootstrap has a set of determined colors (primary, secundary, etc) that we can change later on. EX
  <p class="text-primary">theme primary colour</p>
  <p class="text-secondary">theme secondary colour</p>
  <p class="text-info">theme info colour</p>
  <p class="text-warning">theme warning colour</p>
  <p class="text-success">theme warning colour</p>
  <p class="text-danger">theme danger colour</p>
  <p class="text-muted">theme danger colour</p>

3.6 <!-- bg colors -->
  <p class="text-white bg-primary">white text on primary bg</p>
  <p class="text-white bg-secondary">white text on secondary bg</p>
  <p class="text-light bg-danger">white text on secondary bg</p>
