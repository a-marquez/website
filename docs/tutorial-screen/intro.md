---
sidebar_position: 1
---

# Image Search

> "A picture is worth a thousand words"

When it comes to desktop automation, this holds true as well.
`nut.js` allows you to locate template images on your screen, a key capability for automation.

[find](https://nut-tree.github.io/apidoc/classes/screen.html#find) and [waitFor](https://nut-tree.github.io/apidoc/classes/screen.html#waitfor) are the two main functions when it comes to image search.

While [find](https://nut-tree.github.io/apidoc/classes/screen.html#find) tries to locate an image on screen at the very moment, [waitFor](https://nut-tree.github.io/apidoc/classes/screen.html#waitfor) will repeatedly scan the screen for the image until a certain timeout is reached.

By default, image search is carried out over multiple scales.

Both [find](https://nut-tree.github.io/apidoc/classes/screen.html#find) and [waitFor](https://nut-tree.github.io/apidoc/classes/screen.html#waitfor) are very powerful helpers when automating more complex tasks, so let's see how we can use them to our advantage!