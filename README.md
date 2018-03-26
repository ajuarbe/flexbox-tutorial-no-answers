# Let's learn some flexbox!

https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Basic_Concepts_of_Flexbox

## 1

Here we have a container div with a black border and a beige background color.
It contains three divs, each with the same height and width and a different
background color so we can see how flexbox CSS properties affect the layout.

## 2

Now we want to apply some flexbox properties to the container div and the inner
box divs so the boxes are all in the same row and fill the entire width of the
container.

Hints:
- Use the `display` and `flex` CSS properties.
- `flex-direction` defaults to `row`

## 3

Now we want the red box to take up half of the container's width, and the red
and green boxes to each take up a quarter of the container's width.

Hints:
- Use the `flex` or `flex-grow` property to make the red box grow twice as much
  as the other boxes

## 4

Now we want to vertically center all of the boxes within the container.

Hints:
- Use `align-items` to center the boxes vertically (the opposite axis of the flex
  direction)
