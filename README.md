## Website Performance Optimization portfolio project

#### Part 1: Optimize PageSpeed Insights score for index.html

Changes I made to optimize index.html:

- Inline CSS.
- Moved scripts to the end of the page.
- Added media query 'print' to print.css <link>.
- Optimized pizzeria.jpg.
- Internal perfmatters script.

PageSpeed Insights score:

- Desktop: 94/100
- Mobile: 99/100

#### Part 2: Optimize Frames per Second in pizza.html

Changes I made to optimize fps:

- Changed the number of pizza images to create from 200 to 32.
- Replaced querySelectorAll and querySelector with getElementsByClassName and getElementByID.
- Moved the scrollTop declaration out of the loop.

Changes I made to reduce the time for resizing pizzas:

Changed the changePizzaSizes function by adding switch cases to determine the new width of the pizza and defining an array that store all the elements 
with the class name 'randomPizzaContainer'. Then, I reduced the for loop to only changing the width of the element.




