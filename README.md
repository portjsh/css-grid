# css-grid
CSS Grid with graceful fallback using grid-polyfill by https://github.com/FremyCompany/css-grid-polyfill

## Why Use this?
The purpose of this project is to be able to code website layouts in CSS Grid and have them work with javascript until the native browser supports CSS Grid. There is no need for additional coding just add classes to the html elements and you are all set.
### Example
```html
<div class="gc-span-3 gr-span-3">3</div>
```
`.gc-span-3` stands for "`grid-column: auto / span 3;`" and `.gr-span-3` stands for "`grid-row: auto / span 3;`"
