# CSS Flexbox

## Axis &amp; Directions

The Flexbox model relies on two axes: the main axis and the cross axis. The main axis is defined by flex-direction, which has four possible values:

- `row`
- `row-reverse`
- `column`
- `column-reverse`

The two row settings will create the main axis horizontally - or `inline` direction. The two column settings will create the main axis vertically - or `block` direction. `block` or `inline` here refer to the CSS display settings which we have covered previously.

The axis determines the flow of your content - you can think of this as being either rows or columns - and they will be determined when you start aligning and justifying content within a flex container.

## Ordering Elements

There are three ways to explicitly set the order in which items will appear in a grid.

1. Moving the HTML code for the elements themselves to reorder
2. Appending `-reverse` to `row` or `column` will reverse the order in the specified row or column
3. Using the `order` property of the individual items inside the grid

`flex-direction:row;` will lay elements out from left to right. But `flex-direction:row-reverse` will flip that order and display elements from right to left.

The row and columns settings for flex elements can be reversed by appending `-reverse` to either property value.

## Aligning &amp; Justifying Content

To align items on the cross axis use `align-items` with the possible values:

- stretch
- flex-start
- flex-end
- center

To justify content on the main axis use `justify-content`, which has the possible values:

- flex-start
- flex-end
- center
- space-around
- space-between
- space-evenly

## Links

- [Bulma](https://bulma.io) - Free, open source CSS framework based on Flexbox.
- [Yoga](https://github.com/facebook/yoga) - Cross-platform layout engine which implements Flexbox. ([Web](https://yogalayout.com/)) ([Docs](https://yogalayout.com/docs))
- [FlexView](https://github.com/buildo/react-flexview) - Powerful React component to abstract over flexbox and create any layout on any browser.
- [CSS masonry with flexbox, :nth-child(), and order](https://tobiasahlin.com/blog/masonry-with-css/)
- [Don't use flexbox for overall page layout (2014)](https://jakearchibald.com/2014/dont-use-flexbox-for-page-layout/)
- [The Thought Process Behind a Flexbox Layout (2019)](https://css-tricks.com/the-thought-process-behind-a-flexbox-layout/)
- [Flexbox Zombies](https://flexboxzombies.com/p/flexbox-zombies) - Learn Flexbox by playing a game.
- [Flex Cheat Sheet](https://yoksel.github.io/flex-cheatsheet/)
- [Coping with flexbox (2019)](https://kgrz.io/coping-with-flexbox.html)
- [Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [Flexbox Froggy](http://flexboxfroggy.com/)
- [FLEX](http://flexbox.malven.co/) - Simple visual cheat sheet on Flexbox.
- [Flexy Boxes](https://the-echoplex.net/flexyboxes/) - Flexbox playground and code generator.
- [PostCSS Flexbugs Fixes](https://github.com/luisrudge/postcss-flexbugs-fixes) - PostCSS plugin that tries to fix all of flexbug's issues.
- [Heydon Pickering | Flexbox Holy Albatross (2019)](https://www.youtube.com/watch?v=RUyNJaoJH_k)
