# The Boot Flex Grid
Minimalistic flexbox grid in a few lines of scss. The grid syntax is familiar to developers who have used the bootstrap grid system (but doesn't require any bootstrap dependencies).


# Getting Started

Install the grid by doing

```
npm install boot-flex-grid
```

Then in your existing Sass project, just import the grid

```
@import grid.scss
```

## Breakpoints
The default breakpoint widths are like this:

```
$breakpoints: (
  'xs':   320px,
  'sm':   544px,
  'md':   768px,
  'lg':   1140px
);
```

## Grid Syntax

Default row
`<div class="row"></div>`

### Columns
Columns can take up anywhere from 1/12 to 12/12 of the screen width. The column widths can also be applied at different screen breakpoints. The syntax is `col-[breakpoint name]-[column width]`. For example, `col-md-12` for a full width row when screen size is 544px and up.

### Horizontal alignment
Row with spaces between
`<div class="row row-xs-between"></div>`

Row with Spaces Around
`<div class="row row-xs-around"></div>`

Row aligned left
`<div class="row row-xs-start"></div>`

Row aligned center
`<div class="row row-xs-center"></div>`

Row aligned end
`<div class="row row-xs-end"></div>`

### Vertical alignment
Top Aligned Row
`<div class="row row--xs-top row--xs-center vertical-alignment-demo"></div>`

Middle Aligned Row
`<div class="row row--xs-middle row--xs-center vertical-alignment-demo"></div>`

Bottom Aligned Row
`<div class="row row--xs-bottom row--xs-center vertical-alignment-demo"></div>`



