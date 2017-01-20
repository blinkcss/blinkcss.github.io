# blinkcss.github.io

Documentation site for **blink.css** — web and interface design in the blink of an eye.

[blinkcss.github.io](https://blinkcss.github.io)

*Work in progress!*

---

## Notes:

### Up for discussion:

- text-decoration
- vertical-align
- writing-mode
- column-count (R)
- hyphens
- list-style
- background-blend-mode
- negative margins
- cursor (pointer)

### Thoughts:

- Check :a and :f consistency
- Steps (8, 16) also in `z-index` and `top`, `right`… modules? (Consistency)

## Add:

- width, max-width and height should have responsive classes (at least vh + %/vw)
- max-width should contain breakpoint widths e.g. .mw-md {max-width: --var(breakpoint-md)}
- `padding_child.css` (then, margin und padding need !important)
- separate section for “add-ons” (like `margin_child.css`)
- add responsive classes to `order.css`

## Demo:

- `margin_child.css`
- `order.css`

## Exceptions:

- `bgc` (background-color) vs. `bc` (border-color)
- font-weight: normal (`fw-n`) vs. flex-wrap: nowrap (`fw-nw` also: `ws-nw`)

---

## Breakpoint template

```css
@media screen and (min-width: 40rem) {}

@media screen and (min-width: 60rem) {}

@media screen and (min-width: 80rem) {}
```
