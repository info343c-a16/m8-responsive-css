# Exercise-2
In this exercise, you'll practice using the flex-box layout to manipulate the distribution of elements on your page. You'll implement different layouts for [small](imgs/small-screens.png), [medium](imgs/medium-screens.png), and [large](imgs/large-screens.png) screen sizes.

As described in [module-4](https://github.com/info343c-a16/m4-git-intro), start by forking and cloning this repository. Then, do the following in your `css/main.css` file:

**Flexbox Container**
Your flexbox container should have the following CSS properties:

- Set some initial properties by assigning it a minimum height of `200px`, and a border that is `1px solid black`
- Set the `display` to `flex` to initiate the flexbox layout
- Set the `align-items` property such that it _centers_ elements **vertically** (I suggest you also experiment with properties like `stretch`, `flex-end`, and `flex-start` to see what they do)
- Set the `justify-content` property such that it _centers_ content **horizontally** (also try out `flex-start`, `flex-end`, `space-around`, `space-between`)

**Flexbox Items**
The items (immediate children) in your flexbox container should have the following styles:
- Set the padding to `20px`
- Have the items take up `100%` of the width (but _don't_ use the `width` property)

**Item Content**
Set the items with the class `content` to have the following styles. Also, think about what advantages are provided by wrapping this content with the `flex-column` divs.
- Set the background color to `tomato`
- Align text in the center
- Set the font-size to `4rem`
- Set the height to `100%`

**Media Queries**
Write the media queries that impose the following styles:
- On medium screens (>=768px), have the flexbox items each take up 50% of the flexbox
- On large screens (>=992px) have the flexbox items take up 25% of the flexbox

See `complete` branch for answers.
