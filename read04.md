
# Grids in CSS:
The CSS Grid Layout Module offers a grid-based layout system, with rows and columns, making it easier to design web pages without having to use floats and positioning. A grid layout consists of a parent element, with one or more child elements. An HTML element becomes a grid container when its display property is set to grid or inline-grid.

- Example:
```
.grid-container {
  display: grid;
}
```
<img src='https://i.morioh.com/200607/2d5743ae.jpg' width=800 height= 450>

- All direct children of the grid container automatically become grid items. The vertical lines of grid items are called columns. The horizontal lines of grid items are called rows. The spaces between each column/row are called gaps.

## Grid Container
- display : defines element as grid
- grid-template-columns / grid-template-rows : defines the columns/rows of the grid
- grid-template-areas: defines a grid template by referencing the names of the grid areas which are specified with the grid-area property
- grid-template: shorthand for setting grid-template-rows, grid-template-columns, and grid-template-areas
- column-gap / row-gap / grid-column-gap / grid-row-gap: used to set the width of the gutters between the columns/rows
- gap / grid-gap: shorthand for row-gap and column-gap
- justify-items: aligns grid items along the inline (row) axis
- align-items: aligns grid items along the block (column) axis
- place-items: sets both the align-items and justify-items properties in a single declaration
- justify-content: set the alignment of the grid within the grid container
- align-content: set the alignment of the grid within the grid container
- place-content: sets both the align-content and justify-content properties in a single declaration
- grid-auto-columns / grid-auto-rows: specifies the size of any auto-generated grid track
- grid-auto-flow: places grid items that you don’t explicitly place on the grid
- grid: shorthand for grid-template-rows, grid-template-columns, grid-template-areas, grid-auto-rows, grid-auto-columns.

## RegEx:
- A regular expression is an object that describes a pattern of characters. Regular expressions are used to perform pattern-matching and "search-and-replace" functions on text.

## Responsice Web Design (RWD):
- Responsive web design is the practice of building a website suitable to work on every device and every screen size, no matter how large or small, mobile or desktop. Responsive generally means to react quickly and positively to any change, while adaptive means to be easily modified for a new purpose or situation, such as change. Currently the most popular technique lies within responsive web design, favoring design that dynamically adapts to different browser and device viewports, changing layout and content along the way. This solution has the benefits of being all three, responsive, adaptive, and mobile.

<img src='https://i.ytimg.com/vi/68O6eOGAGqA/maxresdefault.jpg' width=800 height= 450>

The smaller images (in a grid!) are in the perfect layout to get you started with CSS grid. Grid gives us control over how wide or narrow each of the ‘grid cells’ get. This allows us to maintain a sensible aspect ratio to their height. In this example I’ve used:
```
grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
```

---------------------------------------------------



[Table Of Content](https://omarxzain.github.io/301-reading-notes)
