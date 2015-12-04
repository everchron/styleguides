# HTML Styleguide

## Void Elements

A void element is any element that can not, by definition, have any content in between the start and end tags, but the only type of data that void elements are allowed to have are attributes.

We do never write "closing" slashes `/>` when dealing with void elements.

This is **correct**: `<img src="image.png">`, this is **incorrect**: `<img src="image.png" />`.

These are all valid void elements:

```area, base, br, col, command, embed, hr, img, input,
keygen, link, meta, param, source, track, wbr```
