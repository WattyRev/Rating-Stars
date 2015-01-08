# Rating-Stars
A method of displaying a rating out of 5 stars. 

View a <a href="http://wattydev.com/projects/rating-stars/">Live Demo here</a>

## Support
Rating Stars is tested in Chrome, FireFox, Safari, and IE7+. Include fallback.css to support IE7 and IE8.

## Methodology
Rating Stars uses an svg or image overlay with a white background and transparent stars. A div is placed beneath it with a set width to fill a number of stars. This is a more effeciant, and more maintainable methodolgy than using sprite sheets.

## Installation

### Markup
Use index.html as an example of how the html markup should be. Include the css from style.css for the basic functional styling. The css shown inline in index.html should be included in your stylesheet. This css should be altered to fit your sizing and color preferences.

Because the svg for the stars works by making the stars transparent, the path in the svg should have its fill color match the background color of the site.

### Fallback
If supporting IE8 and/or IE7, include the stars.png file. Depending on what size you want the stars to be, you may want to use stars.ai to export your desired size as a .png image using Adobe Illustrator.

Include fallback.css in a conditional html tag to be used for IE8 and IE7 users.