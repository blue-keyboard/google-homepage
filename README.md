# Recreating Google Homepage

In this project ill try to recreate the only the visual elements of the google homepage, without the functionality.
I couldn't resist to try to mimic the page as much as possible though.


## Mini-header at top-left

I tried to recreate it with pure css, made a 3x3 grid for the google apps icon and a rounded div for the profile icon, i realized in this part that sometimes is really tricky to center things, especially vertically, so I had to use some padding in pixels in some parts to align the items manually.

Also added the hover efects to the links and the 3x3 icon.


## Footer nav-bar

Seemed simple, tried to match the exact grey tones just for fun, discovered that line-height comes in handy for spacing top and bottom when only text.


## Main content

For this part I experimented with a simple div-wrapper that has text-align to center its items, so i made its childs inline-block elements and to put one below the other i just used the <code>&lt;br&gt;</code> tag.

The most interesting part was doing the search box, for this I made a div flexbox with rounded corners, then the "search icon" and the input-text as its childs, i learned how to style the input-text removing some of the properties that has as default.

