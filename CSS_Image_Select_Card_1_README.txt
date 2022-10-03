Image Selector Card ReadMe:

This is an easy to make image selector card using a checkbox input, a label and
an image.

The main gist of it is you make a div container, make a checkbox input with an ID,
and then make a label with the for="" matching the ID on that input. Then put the
image inside the label.

Position the container relative, then position the input absolute so you can place
it on top of the image using the top, left, bottom or right properties.

Give the container an onClick function to toggle a border class to give it a nice
border when it is clicked (checked or unchecked).

Use outline instead of border. Outline doesn't get factored into the image's size,
so using outline will not cause the image to shrink like border does.

The checkbox needs BOTH a width and height property to make the checkbox bigger.
Use a fixed width and height (px).

Use a fixed width for the image instead of a % so the checkbox will move with it
when the screen scales down.

To give the card a title or w/e else you want, all you have to do is put another
div after the label tag with the title in it. Adjust it's placing with padding.