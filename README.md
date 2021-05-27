# 📱 PWACSS
**THE** normalize for PWA. It focuses on new browser features and improving the UX.

**Do choose this** if you're planning on building a PWA and need a no-brainer, unopinionated boilerplate which'll make you write a lot less of useless, repetitive code while making your UI render more predictable.

## What it does?

1. Removes the default margin from `body`
2. Sets `box-sizing` to `border-box` for all elements including pseudos
3. Sets `line-height` to `1` for all elements so you don't have to worry about inline blocks' vertical alignment and other quirks. Pseudos will also inherit `vertical-alignment` and `text-decoration`
4. Sets `backface-visibility` to `hidden` to prevent typefaces from turning blurry with `transform` properties in old browsers
5. Ensures that `[hidden]` elements will be hidden
6. Enables some ligatures but not all of them
7. Optimizes typeface smoothing and legibility
8. Sets the system UI typeface as the default
9. Turns images into blocks so text wraps above and below them
10. Prevents images from being resized more than their actual size
11. Makes HTML fully responsive by default: images, canvases, tables and other less usual tags
12. Sets a monospace font and tabs of width 4 for `code` and `pre`
13. Only let users resize `textarea`s vertically
14. Makes the typeface in `input`s the same as the typeface on your website itself
15. Uses appropriate cursor based on aria-attributes
16. Disable IOS quirks that aren't useful for PWA, making your UI more predictable and less fragile across different devices. 

## Usage
```HTML
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/mvoloskov/pwacss/pwacss.min.css">
```
