## Part 1: Media Queries
In this exercise, you're going to convert a layout which was designed for mobile to also work on tablet and desktop browsers.

1.  For screens bigger than 480 pixels:
    *   allow items within an article to wrap
    *   force the sidebar to take up 100% of its parent's height
2.  For screens larger than 640 pixels:
    *   sections should also take up 100% of their parent's height

When done correctly, the tablet view (greater than 480 pixels) should have a full-height sidebar and one column of sections. Conversely, the desktop view (greater than 640 pixels) should have a sidebar and sections that fit on a single row.

## Part 2: Flexbox Layout 

In this exercise, you're going to update a profile page. You need to replace the use of floats with the more modern Flexbox by:

1.  Removing the `.row:after` rule
2.  Add a rule for `.row` elements that makes it a flex container
3.  Instruct `.column` elements to take up a proportionate amount of space using the `flex` property
4.  Remove explicit widths from `.column`
