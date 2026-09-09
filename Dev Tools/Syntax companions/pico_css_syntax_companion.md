# Pico CSS Syntax Companion

Searchable reference for Pico CSS.

Pico is a minimalist CSS framework that primarily styles normal semantic HTML automatically.


# INSTALL — Local Pico CSS

Search terms: install, local, stylesheet, pico

## Syntax

```html
<link rel="stylesheet" href="css/pico/pico.min.css">
```

Load your custom CSS after Pico:

```html
<link rel="stylesheet" href="css/pico/pico.min.css">
<link rel="stylesheet" href="css/style.css">
```

## Notes
Pico loads first.
Your stylesheet loads second and can override Pico.


# STARTER PAGE

Search terms: starter, template, basic page

## Syntax

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">

    <meta
        name="viewport"
        content="width=device-width, initial-scale=1.0"
    >

    <title>Page Title</title>

    <link rel="stylesheet" href="css/pico/pico.min.css">
    <link rel="stylesheet" href="css/style.css">
</head>

<body>

    <main class="container">
        <h1>Hello World</h1>
    </main>

</body>

</html>
```


# CONTAINER — Centered Content

Search terms: container, centered, width, main

## Purpose
Creates a responsive centered content area.

## Syntax

```html
<main class="container">
    <h1>Hello World</h1>
</main>
```


# CONTAINER FLUID — Full Width

Search terms: container fluid, full width

## Syntax

```html
<main class="container-fluid">
    <h1>Hello World</h1>
</main>
```


# THEME — Light or Dark

Search terms: theme, light, dark, color scheme

## Force Light

```html
<html lang="en" data-theme="light">
```

## Force Dark

```html
<html lang="en" data-theme="dark">
```

## Notes
Without forcing a theme, Pico can follow the user's system color preference.


# GLOBAL FONT

Search terms: font, global font, pico font family

## Syntax

```css
:root {
    --pico-font-family: "Source Sans 3", sans-serif;
}
```


# GLOBAL BACKGROUND

Search terms: background, global background, pico background

## Syntax

```css
:root {
    --pico-background-color: #FFFFFF;
}
```


# GLOBAL TEXT COLOR

Search terms: text color, global color, pico color

## Syntax

```css
:root {
    --pico-color: #000000;
}
```


# PRIMARY COLOR — Accent

Search terms: primary, accent, color, button, link

## Syntax

```css
:root {
    --pico-primary: #0000FF;
}
```


# CUSTOM THEME VARIABLES

Search terms: custom variables, theme, root

## Example

```css
:root {
    --background-color: #FFFFFF;
    --text-color: #000000;
    --accent-color: #0000FF;

    --pico-background-color: var(--background-color);
    --pico-color: var(--text-color);
    --pico-primary: var(--accent-color);
}
```


# TYPOGRAPHY — Automatic Styling

Search terms: typography, headings, paragraph

## HTML

```html
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<p>Paragraph text.</p>
```

## Notes
Pico automatically supplies typography, spacing and sizing.


# BUTTON — Standard Button

Search terms: button, action

## Syntax

```html
<button>
    Continue
</button>
```


# LINK AS BUTTON

Search terms: link button, role button

## Syntax

```html
<a href="about.html" role="button">
    Continue
</a>
```


# SECONDARY BUTTON

Search terms: secondary, button

## Syntax

```html
<button class="secondary">
    Secondary
</button>
```


# OUTLINE BUTTON

Search terms: outline, button

## Syntax

```html
<button class="outline">
    Outline
</button>
```


# FORM

Search terms: form, input, fields

## Syntax

```html
<form>

    <label for="name">
        Name
    </label>

    <input
        type="text"
        id="name"
        name="name"
    >

    <button type="submit">
        Submit
    </button>

</form>
```

## Notes
Pico automatically styles forms and their controls.


# INPUT

Search terms: input, form field

## Syntax

```html
<input type="text">
```

Email:

```html
<input type="email">
```

Password:

```html
<input type="password">
```

Number:

```html
<input type="number">
```


# SELECT

Search terms: select, dropdown, option

## Syntax

```html
<select>
    <option>Option One</option>
    <option>Option Two</option>
</select>
```


# TEXTAREA

Search terms: textarea, message

## Syntax

```html
<textarea></textarea>
```


# CHECKBOX

Search terms: checkbox, form

## Syntax

```html
<label>
    <input type="checkbox">
    Remember me
</label>
```


# RADIO

Search terms: radio, choice

## Syntax

```html
<label>
    <input
        type="radio"
        name="choice"
    >
    Option One
</label>
```


# GROUP — Joined Controls

Search terms: group, buttons, joined inputs

## Syntax

```html
<div role="group">

    <input
        type="text"
        placeholder="Search"
    >

    <button>
        Search
    </button>

</div>
```


# NAVIGATION

Search terms: nav, navigation, menu

## Basic

```html
<nav>
    <a href="index.html">Home</a>
    <a href="about.html">About</a>
</nav>
```

## Structured Navigation

```html
<nav>

    <ul>
        <li>
            <strong>Website</strong>
        </li>
    </ul>

    <ul>
        <li>
            <a href="index.html">Home</a>
        </li>

        <li>
            <a href="about.html">About</a>
        </li>
    </ul>

</nav>
```


# TABLE

Search terms: table, data, rows, columns

## Syntax

```html
<table>

    <thead>
        <tr>
            <th>Name</th>
            <th>Value</th>
        </tr>
    </thead>

    <tbody>
        <tr>
            <td>Example</td>
            <td>100</td>
        </tr>
    </tbody>

</table>
```


# STRIPED TABLE

Search terms: striped table, alternating rows

## Syntax

```html
<table class="striped">

</table>
```


# ARTICLE — Card-Like Content

Search terms: article, card, panel

## Syntax

```html
<article>

    <h2>Article</h2>

    <p>
        Article content.
    </p>

</article>
```

## Notes
Pico gives `<article>` a card-like presentation by default.


# DETAILS — Accordion

Search terms: details, accordion, expandable

## Syntax

```html
<details>

    <summary>
        More Information
    </summary>

    <p>
        Additional content.
    </p>

</details>
```


# PROGRESS

Search terms: progress, loading, percentage

## Syntax

```html
<progress
    value="70"
    max="100"
>
</progress>
```


# GRID

Search terms: grid, columns, layout

## Syntax

```html
<div class="grid">

    <div>
        Column One
    </div>

    <div>
        Column Two
    </div>

</div>
```

## Notes
Pico's grid automatically collapses columns on smaller screens.


# RESPONSIVE LAYOUT

Search terms: responsive, mobile, breakpoint

## Notes
Pico automatically provides responsive defaults for many elements.

Use:

```html
<meta
    name="viewport"
    content="width=device-width, initial-scale=1.0"
>
```

in the document `<head>`.


# CLASSLESS PICO

Search terms: classless, semantic, no classes

## Purpose
Uses Pico styling while requiring even fewer framework classes.

## Stylesheet

```html
<link
    rel="stylesheet"
    href="css/pico/pico.classless.min.css"
>
```

## HTML

```html
<body>

    <main>
        <h1>Hello World</h1>
    </main>

</body>
```

## Notes
With the classless version, direct `<header>`, `<main>` and `<footer>` children of `<body>` act as semantic containers.


# FLUID CLASSLESS PICO

Search terms: fluid classless, full width

## Stylesheet

```html
<link
    rel="stylesheet"
    href="css/pico/pico.fluid.classless.min.css"
>
```


# CUSTOM CSS OVERRIDE

Search terms: override, custom css, change pico

## HTML

```html
<link rel="stylesheet" href="css/pico/pico.min.css">
<link rel="stylesheet" href="css/style.css">
```

## CSS

```css
h1 {
    color: red;
}
```

## Notes
Keep Pico's own files unchanged.

Place your changes in a separate stylesheet loaded after Pico.


# PICO + CUSTOM SITE THEME

Search terms: theme template, colors, font

## Syntax

```css
@font-face {
    font-family: "Source Sans 3";

    src: url("../assets/fonts/SourceSans3.ttf")
        format("truetype");

    font-style: normal;
    font-weight: 100 700;
}


:root {
    --background-color: #FFFFFF;
    --text-color: #000000;
    --accent-color: #0000FF;

    --pico-font-family: "Source Sans 3", sans-serif;

    --pico-background-color: var(--background-color);
    --pico-color: var(--text-color);
    --pico-primary: var(--accent-color);
}
```


# PICO PHILOSOPHY

Search terms: pico purpose, semantic, why pico

Pico is designed around normal semantic HTML.

Instead of:

```html
<button class="large-blue-rounded-button">
    Continue
</button>
```

you can often simply write:

```html
<button>
    Continue
</button>
```

Pico supplies the normal styling and your custom stylesheet supplies the site's identity.