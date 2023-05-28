## About the project

* It is a basic Html and Css project.

## Tools used

* HTML
* CSS

## Learning

* header element - represented at the top of your HTML.
* blockquote element - specifies a section that is quoted from another source.
* hr element - defines a thematic break in an HTML page.It is most often displayed as a horizontal rule that is used to separate content (or define a change) in an HTML page.
* article element - specifies independent, self-contained content.
* grid-template-columns property - specifies the number (and the widths) of columns in a grid layout.
    * grid-template-columns: minmax(2rem, 1fr) minmax(min-content, 94rem) minmax(2rem, 1fr);
    * minmax function to make your columns responsive on any device.
    * The minmax function takes two arguments, the first being the minimum value and the second being the maximum
    * These values could be a length, percentage, fr, or even a keyword like max-content.
* row-gap property - defines the size of the gap between the rows in a grid layout.
    * row-gap: 3rem;
* grid-column property -  which is shorthand for grid-column-start and grid-column-end. 
    * syntax - grid-column: grid-column-start / grid-column-end;
    * grid-column-start - Specifies on which column to start displaying the item.
    * grid-column-end - Specifies on which column-line to stop displaying the item, or how many columns to span.
* repeat() function - The CSS repeat() function is used to repeat a value, rather than writing it out manually, and is helpful for grid layouts.
    * For example, grid-template-columns: repeat(20, 200px);
    * would create 20 columns each 200px wide.
* grid-auto-flow property - grid-auto-flow uses an auto-placement algorithm to adjust the grid layout.
    * grid-auto-flow: column;
    * column - Setting it to column will tell the algorithm to create new columns for content as needed.
* align-items - align-items will align child elements along the column axis.
* justify-items -justify-items will align child elements along the row axis.
* :: first-letter - The ::first-letter pseudo-selector allows you to target the first letter in the text content of an element.
* place-items - The place-items property is used in grid layout, and is a shorthand property for align-items and justify-items.