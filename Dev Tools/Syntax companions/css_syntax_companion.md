# CSS Syntax Companion

Searchable reference for common CSS syntax and layout.


# RULE — CSS Rule

Search terms: rule, ruleset, selector, declaration

## Syntax

```css
h1 {
    color: blue;
    font-size: 2rem;
}
```

## Anatomy

```text
h1
→ selector

color
→ property

blue
→ value

color: blue;
→ declaration

{ ... }
→ declaration block
```


# COMMENT — CSS Comment

Search terms: comment, note

## Syntax

```css
/* This is a CSS comment */
```


# ELEMENT SELECTOR

Search terms: element selector, type selector, body, h1, p

## Syntax

```css
body {
    background: white;
}

h1 {
    color: black;
}
```


# CLASS SELECTOR

Search terms: class, selector, dot

## HTML

```html
<p class="message">Hello</p>
```

## CSS

```css
.message {
    color: blue;
}
```


# ID SELECTOR

Search terms: id, hash, unique

## HTML

```html
<div id="menu"></div>
```

## CSS

```css
#menu {
    width: 200px;
}
```


# ROOT — Global CSS Variables

Search terms: root, global, variables, custom properties

## Syntax

```css
:root {
    --background-color: #FFFFFF;
    --text-color: #000000;
}
```

Use a variable:

```css
body {
    background: var(--background-color);
    color: var(--text-color);
}
```


# COLOR — Text Color

Search terms: color, text color

## Syntax

```css
p {
    color: #000000;
}
```


# BACKGROUND — Background Color

Search terms: background, background color

## Syntax

```css
body {
    background-color: #FFFFFF;
}
```


# FONT FAMILY — Typeface

Search terms: font, font family, typeface

## Syntax

```css
body {
    font-family: Arial, sans-serif;
}
```


# FONT FACE — Local Font

Search terms: font-face, local font, custom font

## Syntax

```css
@font-face {
    font-family: "My Font";
    src: url("../assets/fonts/MyFont.ttf")
        format("truetype");

    font-style: normal;
    font-weight: 100 700;
}
```


# FONT SIZE

Search terms: font size, text size

## Syntax

```css
h1 {
    font-size: 2rem;
}
```


# FONT WEIGHT

Search terms: font weight, bold

## Syntax

```css
h1 {
    font-weight: 600;
}
```


# FONT STYLE

Search terms: italic, font style

## Syntax

```css
em {
    font-style: italic;
}
```


# LINE HEIGHT

Search terms: line height, text spacing, lines

## Syntax

```css
p {
    line-height: 1.5;
}
```


# TEXT ALIGN

Search terms: text align, center text, left, right

## Syntax

```css
h1 {
    text-align: center;
}
```


# TEXT DECORATION

Search terms: underline, decoration, link

## Syntax

```css
a {
    text-decoration: none;
}
```


# LETTER SPACING

Search terms: letter spacing, tracking

## Syntax

```css
h1 {
    letter-spacing: 2px;
}
```


# WIDTH

Search terms: width, horizontal size

## Syntax

```css
.sidebar {
    width: 200px;
}
```


# HEIGHT

Search terms: height, vertical size

## Syntax

```css
.logo {
    height: 80px;
}
```


# MAX WIDTH

Search terms: max width, maximum width

## Syntax

```css
main {
    max-width: 1200px;
}
```


# MIN HEIGHT

Search terms: min height, viewport height

## Syntax

```css
body {
    min-height: 100vh;
}
```


# MARGIN — Outside Spacing

Search terms: margin, outside spacing

## All Sides

```css
section {
    margin: 20px;
}
```

## Individual Sides

```css
section {
    margin-top: 10px;
    margin-right: 20px;
    margin-bottom: 10px;
    margin-left: 20px;
}
```

## Shorthand

```css
section {
    margin: 10px 20px;
}
```


# PADDING — Inside Spacing

Search terms: padding, inside spacing

## Syntax

```css
main {
    padding: 20px;
}
```


# BORDER

Search terms: border, line, divider

## Syntax

```css
section {
    border-width: 1px;
    border-style: solid;
    border-color: #000000;
}
```

Shorthand:

```css
section {
    border: 1px solid #000000;
}
```


# BORDER RADIUS

Search terms: radius, rounded corners

## Syntax

```css
button {
    border-radius: 8px;
}
```


# DISPLAY BLOCK

Search terms: block, display

## Syntax

```css
div {
    display: block;
}
```


# DISPLAY INLINE

Search terms: inline, display

## Syntax

```css
span {
    display: inline;
}
```


# FLEXBOX — Flex Layout

Search terms: flex, flexbox, row, column, layout

## Basic

```css
.container {
    display: flex;
}
```


# FLEX DIRECTION

Search terms: flex direction, row, column

## Row

```css
.container {
    display: flex;
    flex-direction: row;
}
```

## Column

```css
.container {
    display: flex;
    flex-direction: column;
}
```


# ALIGN ITEMS

Search terms: align items, cross axis, vertical alignment

## Syntax

```css
.container {
    display: flex;
    align-items: center;
}
```


# JUSTIFY CONTENT

Search terms: justify, horizontal alignment, center

## Syntax

```css
.container {
    display: flex;
    justify-content: center;
}
```


# GAP

Search terms: gap, spacing, flex spacing

## Syntax

```css
.container {
    display: flex;
    gap: 10px;
}
```


# FLEX — Fill Remaining Space

Search terms: flex 1, remaining space, grow

## Syntax

```css
main {
    flex: 1;
}
```


# GRID — Grid Layout

Search terms: grid, columns, rows

## Syntax

```css
.container {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 20px;
}
```


# POSITION

Search terms: position, static, relative, absolute, fixed

## Relative

```css
.element {
    position: relative;
}
```

## Absolute

```css
.element {
    position: absolute;
    top: 10px;
    left: 10px;
}
```

## Fixed

```css
.element {
    position: fixed;
    top: 0;
}
```


# HOVER

Search terms: hover, mouse, interaction

## Syntax

```css
a:hover {
    color: blue;
}
```


# FOCUS

Search terms: focus, keyboard

## Syntax

```css
button:focus {
    outline: 2px solid blue;
}
```


# OPACITY

Search terms: opacity, transparent, faded

## Syntax

```css
p {
    opacity: 0.7;
}
```


# IMAGE SIZE

Search terms: image, responsive image

## Syntax

```css
img {
    max-width: 100%;
}
```


# TABLE COLLAPSE

Search terms: table, borders, collapse

## Syntax

```css
table {
    border-collapse: collapse;
}
```


# TABULAR NUMBERS

Search terms: numbers, tabular, lining, financial

## Syntax

```css
.number {
    font-variant-numeric: lining-nums tabular-nums;
}
```


# MEDIA QUERY

Search terms: responsive, mobile, breakpoint, media

## Syntax

```css
@media (max-width: 768px) {

    .container {
        flex-direction: column;
    }

}
```


# INHERIT

Search terms: inherit, parent value

## Syntax

```css
a {
    color: inherit;
}
```


# REM

Search terms: rem, unit, root font size

## Example

```css
h1 {
    font-size: 2rem;
}
```

`1rem` normally corresponds to the root font size.


# PX

Search terms: px, pixel, fixed size

## Example

```css
.sidebar {
    width: 200px;
}
```


# VH

Search terms: vh, viewport height, screen height

## Example

```css
body {
    min-height: 100vh;
}
```

`100vh` means 100% of the viewport height.


# PERCENT

Search terms: percent, percentage, relative width

## Example

```css
table {
    width: 100%;
}
```