# CSS-GRID
CSS Grid with graceful fallback using grid-polyfill by https://github.com/FremyCompany/css-grid-polyfill. Mainly for IE11 and Edge. The Latest version of Firefox has CSS Grid supported already. The other moderen browsers are coming out with Grid support in their next releases. 

## Why Use this?
The purpose of this project is to be able to code website layouts in CSS Grid and have them work with javascript until the native browser supports CSS Grid. There is no need for additional coding just add classes to the html elements and you are all set.


## What is CSS Grid?
CSS Grid is a NEW two-demensional way to layout websites. CSS Grid doesn't replace `display: flex;`. It is meant to be use as a website layout tool.


### Example
```html
<div class="gc-span-3 gr-span-3">3</div>
```
`.gc-span-3` has the property of  `grid-column: auto / span 3;`" and `.gr-span-3` has the property of "`grid-row: auto / span 3;`
