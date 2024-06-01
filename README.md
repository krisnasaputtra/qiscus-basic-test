# Qiscus Basic Test

This is a simple HTML/CSS project that demonstrates interactive box elements with stylish background images. The project showcases the use of CSS selectors and properties to create dynamic visual effects based on user interactions.

## CSS Interactivity Details

The CSS within the project includes interactive elements that respond to user actions. Here's a breakdown of the CSS classes and their functionalities:

1. `.box:hover > .box_inside:not(:hover)`:

   - When hover over the box (as a parent box_inside), a left-facing arrow image will be appear in direct child of the box (in this case box_inside) is not hovered

2. `.box_inside:hover ~ .box_inside:not(:hover)`:

   - When hover over one of the box_inside elements, a right-facing arrow image will be appear in another box_inside is not hovered next
   - :not(:hover) is needed since the latter selector using that specificity

Pseudo-class and Combinator that i use:

1. `:not`:

   - This pseudo-class is represents elements that do not match a list of selectors

2. `>`:

   - This is child combinator that represent elements matched by the second selector that are direct children of the first selector

3. `~`:

   - This tilde is subsequent-sibling combinator that represent elements matched by the secon selector that follow the first element, not directed children and share the same parent element

These CSS properties and selectors create a dynamic and visually appealing interaction within the project.
