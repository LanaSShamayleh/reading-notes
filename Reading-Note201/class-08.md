# CSS Layout

Each element in CSS is placed in its own box either block-level box or an inline box. To separate boxes, borders, margins, padding, and background colors are used. The positioning schemes in CSS allow controlling the page layout. Positioning schemes are specified using the ```position``` property with different values such as static, relative, absolute, and fixed.

>- In static or normal flow positioning, each block-level element is above the next one which is the default positioning.
>
>- Relative positioning moves the element relative to its original position in normal flow.
>
>- Absolute positioning takes the box out of normal flow, in which case the box acts like it is not on the >page. The offset properties specify where the element should appear relative to its containing element.
>
>- In fixed positioning, the element stays in the same place even if the user scrolls down the page.
>

To control which box stays on top in case of overlapping, the ```z-index``` property is used.

Elements can be placed side by side using ```float``` property. ```clear``` property is used for a particular element so that no other element in the same containing element touches the left or right sides of the box.

An element containing only floating elements might appear in some browsers as if it has zero height. The solution is to use ```overflow: auto;``` in the containing element.

The design of a webpage must adapt to different screen resolutions. Fixed width layouts do change size along with the browser window. In this layout the designer has more control over the appearance, but for users with different screen sizes the design will not work well. On the other hand, liquid layouts adapt to the browser size, but the page might not look as the designer intended.

Grids in CSS are used to position items on a page to create a professional looking design. A grid commonly used by designers is the 960 pixel grid. It consists of 12 equally sized columns. Each column is 60 pixel wide with 10 pixel margin.

Multiple style sheets can be added using ```@import``` rule in the one style sheet file linked to in the html file.

>```CSS
>@import url("fonts.css");
>@import url("colors.css");
>```

Another way to add multiple style sheets is to use multiple ```<link>``` elements in the html file. The style sheets that appear later take precedence over previous ones.