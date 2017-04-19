# blinkUI.github.io

Documentation site for **blink UI** — web and interface design in the blink of an eye.

[blinkUI.github.io](https://blinkui.github.io)

![](screenshot.png)

*Work in progress!*

---

## Notes:

### Up for discussion:

- grids
- vertical-align
- writing-mode
- column-count (R)
- hyphens
- background-blend-mode
- cursor (pointer)
- taking it further: filters, transitions

### Thoughts:

- Steps (8, 16) also in `z-index` and `top`, `right`… modules? (Consistency)
- Moving away from number steps to semantic steps like: XXS › XS › S › M › L › XL › XXL?

## Add/Improve:

- `padding_child.css` (then, margin und padding need !important)
- separate section for “add-ons/helpers” (like `margin_child.css`)
- negative margins (for grids) — or is it better to go for the grid module?

## Make responsive:

- width, max-width and height should have responsive classes (at least vh + %/vw)
- `order`
- `flex-grow`
- `z-index`
- `position`

## Demo:

- `margin_child.css`
- `order.css`

## Exceptions:

- `bgc` (background-color) vs. `bc` (border-color)
- font-weight: normal (`fw-n`) vs. flex-wrap: nowrap (`fw-nw` also: `ws-nw`)

## Duplicates:

- `fs`: flex-shrink, font-size, font-style
- `fw`: font-weight, flex-wrap
- `o`: order, opacity
- `bs`: border-style, box-shadow, box-sizing

---

## Breakpoint template

```css
@media screen and (min-width: 40rem) {}

@media screen and (min-width: 60rem) {}

@media screen and (min-width: 80rem) {}
```

---

The MIT License (MIT)

Copyright 2016 – 2017 Damian Gerbaulet

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NON-INFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
