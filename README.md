# Museum of Dessert

A simple, responsive webpage to practice the new edition of Bootstrap, Bootstrap version 4.3. San Francisco has a Museum of Ice Cream, an online class had a Museum of Candy assignment, so made a Museum of Dessert to utilize the new features in Bootstrap.

## Summary

This is just HTML, CSS, and some JS to practice Bootstrap. About 80-90% of Bootstrap is the same, but it's that 20% that throws an error. Read the docs, took a couple of online classes, and put together this webpage.

## What's different with Bootstrap v4?

For the complete list of changes, see [Bootstrap Migration](https://getbootstrap.com/docs/4.3/migration/) section on the Bootstrap website.

For the abbreviated version, here are some of the major changes:

1. Flexbox is enabled by default. Flexbox has two main axes: main and cross axis. The main axis goes (by default) from left to right, while the cross axis goes from (bottom to top).
2. rem is the primary unit of CSS measure. rem is "root em." The rem unit is relative to the root (the html) element. rem makes it easier to specify font size than ems. The issue with using ems, was font size compounds. Making a list within a list changes the ems when no change was intended. rem is based off a root element and does not change.
3. font size changed from 16px (from 14 px).
4. Five (5) screen sizes: xs (extra-small for < 576px), s (small for >= 576px), md (medium >=768px), lg (large >= 992px), and xl (extra-large >= 1200px). xs is enabled by default and does not need to be specified.
5. Need to include new JavaScript library: Popper.js in order to use Bootstrap JavaScript. Popper.js deals with an element that "pops out" of your screen: tooltips, drop-downs, and popovers. Popper.js is a positioning engine, that makes it possible to position an element.
6. Cards are/is the new base component. Panels, thumbnails, and wells are depreciated.
7. Various class names are changed for readability/writeability. Many classes are now handled by utilities.
