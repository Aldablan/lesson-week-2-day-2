# Flexbox

Block elements, as a rule, always stack vertically - never side by side. Each
block element effectively has a 'new-line' built into it, forcing the next piece
of content down.

This can be circumvented using a system called Flexbox. Officially called the
"Flexible Box Model", Flexbox is a relatively recent addition to CSS that makes
creating rich, responsive layouts much easier. Flexbox allows us to specify
whether the children of a given element should be arranged horizontally or
vertically, how they should be positioned along that axis, and how much space
they should take up.

A Flexbox layout therefore consists of two layers: the container element, which
we give the CSS properties `display: flex;` and `flex-direction: <direction>;`,
and the child elements, which will be arranged in that direction.

The most common choices for that `<direction>` will either be `row` or `column`.

If we choose, `flex-direction: row;` on the container element, its children will
be layed out like this:

![Flex Row](https://git.generalassemb.ly/ga-wdi-boston/html-css-layout/blob/master/public/images/flex-row.png?raw=true)

If we choose `flex-direction: column;` we'll get this instead:

![Flex Column](https://git.generalassemb.ly/ga-wdi-boston/html-css-layout/blob/master/public/images/flex-column.png?raw=true)

There's also a concept of a "cross axis", which is the axis perpendicular to
the one chosen by `flex-direction`:

![Flex Cross Axis](https://git.generalassemb.ly/ga-wdi-boston/html-css-layout/blob/master/public/images/flex-row-cross-axis.png?raw=true)

We can use various other Flexbox properties to determine how elements are
positioned along both axes.

## Lab: Build a Layout

We've definitely got some work to do. Here's what we want our site to look
like:

![image](https://media.git.generalassemb.ly/user/6926/files/d923a280-febf-11e8-9a66-a2b6cd3397b4)

To get there, we'll need to use some of the flex properties we just saw in the
demo, as well as our knowledge of the box model. Once we've achieved the desired
layout, lets commit our changes.

Add your markup between the `<body>` tags in [flexbox-lab/index.html](flexbox-lab/index.html), and your styling in
[flexbox-lab/main.css](flexbox-lab/main.css).

## Lab: Flexbox Froggy

Help the frogs reach the correct lilly pads using flexbox properties
- http://flexboxfroggy.com/

Finish early?  Try these other flexbox games!
- http://www.flexboxdefense.com/
- https://mastery.games/p/flexbox-zombies (must sign up)

## Additional Resources
- [Visual Guide to Flexbox](https://scotch.io/tutorials/a-visual-guide-to-css3-flexbox-properties)
- [Flexplorer](http://bennettfeely.com/flexplorer/)
- [Flexbox Demos](https://demos.scotch.io/visual-guide-to-css3-flexbox-flexbox-playground/demos/)
