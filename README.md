# CSS Grids and Flexbox for Responsive Web Design

This repo hosts code/notes taken from the course https://frontendmasters.com/courses/css-grids-flexbox/

## Intro

<details>
  <summary>Reading Resources</summary>

### FLEXBOX

---

Chris Coyer's Complete Guide to Flexbox  
https://css-tricks.com/snippets/css/a-guide-to-flexbox/

Smashing Magazine: Harnessing Flexbox for Today's Web Apps http://www.smashingmagazine.com/2015/03/02/harnessing-flexbox-for-todays-web-apps/

Solved by Flexbox
https://philipwalton.github.io/solved-by-flexbox/

Flexy Boxes playground and code generator
http://the-echoplex.net/flexyboxes/

Getting started with Flexbox grid systems
http://www.webdesignerdepot.com/2016/02/getting-started-with-flexbox-grid-systems/

Flexbox Froggy
http://flexboxfroggy.com/

Flexbox Defense
http://www.flexboxdefense.com/

Flexbox Grid
http://flexboxgrid.com/

Bootstrap 4's Flexbox-based grid
https://getbootstrap.com/docs/4.0/layout/grid/

Zurb Foundation's XY Grid
http://foundation.zurb.com/sites/docs/xy-grid.html

RESPONSIVE IMAGES
Picturefill source
http://scottjehl.github.io/picturefill/

About the <picture> tag
https://www.html5rocks.com/en/tutorials/responsive/picture-element/

Tim Kadlec: Media query asset downloading results
http://timkadlec.com/2012/04/media-query-asset-downloading-results/

### CSS GRID

---

CSS Tricks: A Complete Guide to Grid
https://css-tricks.com/snippets/css/complete-guide-grid/

Grid by Example
http://gridbyexample.com/

Practical CSS Grid: Adding Grid to an Existing Design
https://alistapart.com/article/practical-grid

Basic concepts of grid layout
https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout/Basic_Concepts_of_Grid_Layout

CSS Grid Inspector (in Firefox):
https://developer.mozilla.org/en-US/docs/Tools/Page_Inspector/How_to/Examine_grid_layouts

Grid "fallbacks" and overrides
https://rachelandrew.co.uk/css/cheatsheets/grid-fallbacks

Things I’ve Learned About CSS Grid Layout
https://css-tricks.com/things-ive-learned-css-grid-layout/

GRID PILE: Stacking CSS Grids for Impossible Layouts
https://www.linkedin.com/pulse/grid-pile-stacking-css-grids-impossible-layouts-rand-hendriksen/

Breaking Down a CSS Grid Layout
http://csskarma.com/blog/css-grid-layout/

A Collection of Interesting Facts about CSS Grid Layout
https://css-tricks.com/collection-interesting-facts-css-grid-layout/

Is it really safe to start using CSS Grid Layout?
https://rachelandrew.co.uk/archives/2017/07/04/is-it-really-safe-to-start-using-css-grid-layout/

Bootstrap to CSS Grid
https://medium.com/@tallys/bootstrap-to-css-grid-87b3f5f830e4

Firefox Developer version -- Grid tools
https://mozilladevelopers.github.io/playground/03-firefox-devtools

</details>

<details>
  <summary>Responsive Images</summary>

- Images should change size, based on screen resolution.
- Do not load a big image and let it scale.
- Do not load several images and display the one right for the resolution (display: none based on screensize not good!)
- Protip: use picture tag
- Protip for loading background images based on screen: Don't have overlapping media queries. use min-width and max-width accordingly to prevent double download.
</details>

<details>
  <summary>CSS Grid</summary>

- When you define size of your cells in the grid, the rows/columns follow a numbering system between the gaps.

```
.col-1 {
  grid-column: 1/2; // y-axis, first y-gap to second y-gap
  grid-row: 1/3; // x-axis, first x-gap to third x-gap
}
.col-2 {
  grid-column: 2/3;
  grid-row: 1/3;
}
```

- fr unit reading: https://css-tricks.com/introduction-fr-css-unit/
- You can name your grid areas in your css based on how you defined your layouts. See property `grid-template-areas`
- Firefox devtool for grid : https://mozilladevelopers.github.io/playground/css-grid/

  </details>
