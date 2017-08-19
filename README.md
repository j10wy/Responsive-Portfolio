# Basic Portfolio assignment

### Links
View on [Github Pages](https://jeffreylowy.github.io/Responsive-Portfolio/)

#### Converting from fixed/static layout to a responsive layout

- I used [RQRWD](http://rqrwd.com/) to help me calculate the ratios for each section of the page. 

- I grouped the media queries with each section of the layout. I am not sure if its best to only write 1 media query for each size we're targeting, but it helped me better understand what is happening with each section. To view examples of this, see lines [68](https://github.com/jeffreylowy/Responsive-Portfolio/blob/master/assets/css/style.css#L68) and [106](https://github.com/jeffreylowy/Responsive-Portfolio/blob/master/assets/css/style.css#L106) of my style.css.

- There is an issue on the gallery page between widths 805px and 959px, where the margin-right on each portfolio item is causing the images to stack, though the site works at all of required sizes listed in the HW instructions.