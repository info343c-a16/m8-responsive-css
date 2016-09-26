# Module 8: Responsive CSS

## Overview
Given the prominence of mobile devices and tablets for internet usage, it's crucial that the websites that we build are engineered to look beautiful and work well on small devices. This module covers the skills necessary to begin implementing a **mobile-first** approach to web development. This approach assumes an initial build towards a mobile device, which is **progressively enhanced** on larger screens.

<!-- START doctoc -->
<!-- END doctoc -->

## Resources
- [w3schools Media Queries](http://www.w3schools.com/css/css_rwd_mediaqueries.asp)
- [Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [Media "screen" interpretation](http://stackoverflow.com/questions/8549529/what-is-the-difference-between-screen-and-only-screen-in-media-queries)

## Media Queries
In order to build websites that work well across devices, you need to be able to conditionally change the content given on the size of the screen. Depending on the type and volume of content of your webpage, you may want to change the size, color, layout, or any other visual properties. To accomplish this, we use **media queries** to determine the size of the screen, and apply specific styles. In your CSS, you can use the `@media` syntax to assign styles under certain conditions:


```css
@media screen and (min-width:992px) {
  /* Assign multiple styles in here for screens larger than 991px */
  #element-1 {
    font-size:10px;
  }

  .klass-1 {
    font-size:20px;
  }
}
```

The above media query reads: _on a device with a **screen** whose width is greater than or equal to 992px, assign the following styles_. Because our primary styles will target a **small device**, we will most often use the `min-width` rule to conditionally assign styles to **larger devices**.  screen size.

As you can see, you can make **multiple selections** to assign styles to different elements given a set of media rules. You can also write a variety of media rules to target varying device sizes:

```css
/* These rules are applied by default */

@media screen and (min-width:768px) {
  /* These rules are applied for devices greater than or equal to 768 */
}

@media screen and (min-width:992px) {
  /* These rules are applied for devices greater than or equal to 992 */
}
```
Obviously, if a device width is greater than 992px, it is _also_ greater than 768px. Luckily, your browser is intelligent enough to apply the styles to the more specific CSS selector (992px), which is what you want to happen.

To practice writing media queries, see [exercise-1](exercise-1).

## Flexbox

## CSS Frameworks

### The Grid
