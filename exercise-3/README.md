# Exercise-3
In this exercise, you'll practice using the Materialize framework to create a different layout for different screen sizes. We'll also experiment with using [Font Awesome](http://fontawesome.io/) icons. You'll implement different layouts for [small](imgs/small-screens.png), [medium](imgs/medium-screens.png), and [large](imgs/large-screens.png) screen sizes.

As described in [module-4](https://github.com/info343c-a16/m4-git-intro), start by forking and cloning this repository. Then, in your `index.html` file:
- Add an empty `<nav>` element to the top of your page
- Create a `<div>` element with class `container` in which to put your elements
- Create a `<div>` element with class `row` to create a responsive row with 12 columns

For each of the four sections sections (anchor, bell, asterisk, gear), you will need to create the following elements:
- A `div` with class `col`, set to take up 12 columns on small screens, 6 columns on medium screens, and 3 columns on large screens
- A top level header with the name of the element
- An `<i>` element in which to render your font-awesome _icon_. Inside the `<i>` element, you'll need to assign the proper class to determine which icon you wish to use, and its size. For example, `class="fa fa-email large"` would render a large email icon. You may want to put a line break after your icon, or manipulate it's CSS style
- A button with class `btn`

In your `css/main.css` file, apply the following styles:
- Elements with class `col` should center text inside of them
- Reduce the font-weight of top-level headers to `300`
- Set the margin-bottom of `icon` elements to 10px
- Set a color to the text and icon for each segment. How you do this is up to you (you may want to assign additional classes in your HTML to make this easier). I'm using these colors:
  - anchor:`#b388ff`
  - bell: `#8c9eff`
  - gears: `#82b1ff`
  - asterisk: `#80d8ff`

See `complete` branch for answers.
