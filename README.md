# blinkcss.github.io

Documentation site for blink.css — web and interface design in the blink of an eye.

[blinkcss.github.io](https://blinkcss.github.io)

Work in progress!

---

## Notes:

### Needed?:

- text-decoration
- vertical-align
- writing-mode
- column-count (R)
- hyphens
- list-style
- background-blend-mode
- negative margins

### Thoughts:

- Check :a and :f consistency 
- Steps (8, 16) also at z-index and top, right…? (Consistency)

---

## Add: 

- width, max-width and height should be responsive (at least vh + %/vw)
- max-width should contain breakpoint widths e.g. .mw-md {max-width: --var(breakpoint-md)}
- padding_child (then, margin und padding need !important)
- separate section for “add-ons” (like margin_child)

---

## Demo:

- margin_child
- order (also add responsive classes)

---

## Exceptions:

- bgc vs. bc 
- font-weight: normal (fw-n) vs. flex-wrap: nowrap (fw-nw; also ws-nw)

---

## Breakpoint template

`
@media screen and (min-width: 40rem) {}

@media screen and (min-width: 60rem) {}

@media screen and (min-width: 80rem) {}
`


---
