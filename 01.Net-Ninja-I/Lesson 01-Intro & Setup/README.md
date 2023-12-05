## BOOTSTRAP TUTORIAL
* This is a HTML and plan Vanilla JavaScript project

# Lesson 1. Intro and Set up
https://www.youtube.com/watch?v=O_9u1P5YjVc&list=PL4cUxeGkcC9joIM91nLzd_qaH_AimmdAR

Location in Mac:
/Users/carlosinfante/Desktop/coding-projects/winc-academy/frontend-course/MODULE9 - DEBUGGING and DOMAIN MODELING/REVIEW/Bootstrap

Location in GitHub:
https://github.com/carloscfgos1980/Bootstrap-JavaScript-NetNinja-tutorial/

# Goals:
- Conceptual definition of bootstrap

# Definition:
A. <bootstrap> is fronted, CSS & Javascript for making mobile-first, responsive websites
B. Includes pre-mades components like navBars, modals, tabs, tooltips, buttons, accordions, etc
C. Comes with a fully backed with a responsive, 12 column, CSS grid system for layouts
D. Easy to customize and also ensure browser compatibility 

# STEPS:
1.1 Create index.html.
   1.1 Change the title
   1.2 Create <h1> inside the body

1.2 Isntall last version of bootstrap.
   2.1 - Copy the npm version form this website:
   https://getbootstrap.com/docs/5.2/getting-started/download/

1.3 Copy the CDN link

1.4 index.html: Past the link on the HEAD (lin 8 - 12):
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-Zenh87qX5JnK2Jl0vWa8Ck2rdkQ2Bzep5IDxbcnCeuOxjzrPF/et3URy9Bv1WTRi" crossorigin="anonymous">

1.5 index.html. Cut the script src and paste it in the body, just after the <h1>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-OERcA2EqjJCMA+/3y+gxIOqMEjwtxJY7qPCqsdltbNJuaOe923+mo//f6V8Qbsw3"
        crossorigin="anonymous"></script>

N: We could also install the package in the terminal:
npm install bootstrap@5.2.2

1.6. Create a "assets" folder to include some images later on.
   I can get the images from the gitHub for this lesson.
