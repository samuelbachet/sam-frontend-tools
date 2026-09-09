# HTML Syntax Companion

Searchable reference for common HTML structure and elements.


# DOCUMENT — HTML Document

Search terms: document, html, doctype, language

## Purpose
Defines a modern HTML document.

## Syntax

```html
<!DOCTYPE html>
<html lang="en">

</html>
```

## Notes
- `<!DOCTYPE html>` declares an HTML5 document.
- `<html>` is the root element.
- `lang="en"` declares English as the primary language.


# HEAD — Page Configuration

Search terms: head, configuration, metadata

## Purpose
Contains information and configuration about the webpage.

## Syntax

```html
<head>

</head>
```

## Common Content

```html
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Page Title</title>

<link rel="stylesheet" href="css/style.css">
```


# CHARSET — Character Encoding

Search terms: charset, utf8, utf-8, encoding, characters

## Purpose
Tells the browser how characters in the document are encoded.

## Syntax

```html
<meta charset="UTF-8">
```


# VIEWPORT — Mobile Sizing

Search terms: viewport, mobile, phone, tablet, responsive

## Purpose
Makes the webpage use the actual width of the device.

## Syntax

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```


# TITLE — Browser Tab Title

Search terms: title, tab, browser title

## Purpose
Defines the title shown in the browser tab.

## Syntax

```html
<title>Page Title</title>
```


# LINK — Connect CSS

Search terms: link, css, stylesheet

## Purpose
Connects an external stylesheet to the HTML document.

## Syntax

```html
<link rel="stylesheet" href="css/style.css">
```


# BODY — Visible Page Content

Search terms: body, visible content, webpage

## Purpose
Contains the visible content of the webpage.

## Syntax

```html
<body>

</body>
```


# HEADER — Introductory Content

Search terms: header, introduction, top

## Purpose
Contains introductory content for a page or section.

## Syntax

```html
<header>
    <h1>Website Name</h1>
</header>
```


# NAV — Navigation

Search terms: nav, navigation, menu, links

## Purpose
Groups important navigation links.

## Syntax

```html
<nav>
    <a href="index.html">Home</a>
    <a href="about.html">About</a>
</nav>
```


# MAIN — Primary Page Content

Search terms: main, primary content, page content

## Purpose
Contains the primary content of the webpage.

## Syntax

```html
<main>

</main>
```

## Notes
A page normally has one primary `<main>` element.


# SECTION — Related Content

Search terms: section, group, related content

## Purpose
Groups a related section of content.

## Syntax

```html
<section>
    <h2>Section Heading</h2>
    <p>Section content.</p>
</section>
```


# ARTICLE — Self-Contained Content

Search terms: article, post, independent content

## Purpose
Represents content that can stand by itself.

## Syntax

```html
<article>
    <h2>Article Heading</h2>
    <p>Article content.</p>
</article>
```


# ASIDE — Secondary Content

Search terms: aside, sidebar, secondary, related

## Purpose
Contains secondary or related content.

## Syntax

```html
<aside>
    <p>Related information.</p>
</aside>
```


# FOOTER — Closing Content

Search terms: footer, bottom, copyright, closing

## Purpose
Contains closing information for a page or section.

## Syntax

```html
<footer>
    <p>Footer content.</p>
</footer>
```


# H1–H6 — Headings

Search terms: heading, h1, h2, h3, hierarchy, title

## Purpose
Defines the semantic heading hierarchy.

## Syntax

```html
<h1>Main Page Heading</h1>

<h2>Major Section</h2>

<h3>Subsection</h3>

<h4>Lower Subsection</h4>
<h5>Lower Subsection</h5>
<h6>Lower Subsection</h6>
```

## Notes
Use headings according to document structure, not visual size.


# P — Paragraph

Search terms: p, paragraph, text

## Purpose
Defines a paragraph of text.

## Syntax

```html
<p>This is a paragraph.</p>
```


# STRONG — Important Text

Search terms: strong, bold, important

## Purpose
Marks text as strongly important.

## Syntax

```html
<strong>Important text</strong>
```


# EM — Emphasis

Search terms: em, emphasis, italic

## Purpose
Adds semantic emphasis to text.

## Syntax

```html
<em>Emphasized text</em>
```


# SPAN — Inline Container

Search terms: span, inline, text container

## Purpose
Provides a generic container around inline content.

## Syntax

```html
<span>Text</span>
```


# SMALL — Small Text

Search terms: small, secondary text

## Syntax

```html
<small>Small text</small>
```


# MARK — Highlighted Text

Search terms: mark, highlight

## Syntax

```html
<mark>Highlighted text</mark>
```


# SUP — Superscript

Search terms: sup, superscript, exponent

## Syntax

```html
10<sup>2</sup>
```


# SUB — Subscript

Search terms: sub, subscript

## Syntax

```html
H<sub>2</sub>O
```


# ABBR — Abbreviation

Search terms: abbreviation, abbr, acronym

## Syntax

```html
<abbr title="HyperText Markup Language">HTML</abbr>
```


# TIME — Date or Time

Search terms: time, date, datetime

## Syntax

```html
<time datetime="2026-09-09">September 9, 2026</time>
```


# A — Link

Search terms: a, link, hyperlink, href

## Purpose
Creates a hyperlink.

## Syntax

```html
<a href="about.html">About</a>
```

External link:

```html
<a href="https://example.com">Example</a>
```


# IMG — Image

Search terms: image, img, picture, src, alt

## Syntax

```html
<img
    src="assets/images/example.png"
    alt="Description of the image"
>
```

## Notes
`alt=""` can be used for a purely decorative image.


# FIGURE — Media Group

Search terms: figure, image, caption

## Syntax

```html
<figure>

    <img
        src="assets/images/example.png"
        alt="Example image"
    >

    <figcaption>
        Image caption.
    </figcaption>

</figure>
```


# UL — Unordered List

Search terms: ul, bullets, unordered list

## Syntax

```html
<ul>
    <li>Item One</li>
    <li>Item Two</li>
</ul>
```


# OL — Ordered List

Search terms: ol, numbered list, ordered

## Syntax

```html
<ol>
    <li>First</li>
    <li>Second</li>
</ol>
```


# DL — Description List

Search terms: description list, dl, dt, dd

## Syntax

```html
<dl>

    <dt>HTML</dt>

    <dd>
        Defines webpage structure.
    </dd>

</dl>
```


# BLOCKQUOTE — Long Quotation

Search terms: blockquote, quote, quotation

## Syntax

```html
<blockquote>
    This is a quotation.
</blockquote>
```


# Q — Short Quotation

Search terms: q, short quote

## Syntax

```html
<q>Short quotation.</q>
```


# CITE — Citation

Search terms: cite, source

## Syntax

```html
<cite>Source Title</cite>
```


# CODE — Inline Code

Search terms: code, programming, inline code

## Syntax

```html
<code>console.log("Hello");</code>
```


# PRE — Preformatted Text

Search terms: pre, code block, preserve spacing

## Syntax

```html
<pre><code>function hello() {
    console.log("Hello");
}</code></pre>
```


# KBD — Keyboard Input

Search terms: keyboard, kbd, shortcut

## Syntax

```html
<kbd>Ctrl</kbd> + <kbd>C</kbd>
```


# TABLE — Tabular Data

Search terms: table, rows, columns, data

## Syntax

```html
<table>

    <thead>
        <tr>
            <th scope="col">Name</th>
            <th scope="col">Value</th>
        </tr>
    </thead>

    <tbody>
        <tr>
            <td>Example</td>
            <td>100</td>
        </tr>
    </tbody>

    <tfoot>
        <tr>
            <td>Total</td>
            <td>100</td>
        </tr>
    </tfoot>

</table>
```


# FORM — Form

Search terms: form, input, submit

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


# INPUT — User Input

Search terms: input, text, email, password, number

## Text

```html
<input type="text">
```

## Email

```html
<input type="email">
```

## Password

```html
<input type="password">
```

## Number

```html
<input type="number">
```

## Checkbox

```html
<input type="checkbox">
```

## Radio

```html
<input type="radio">
```


# LABEL — Input Label

Search terms: label, form label

## Syntax

```html
<label for="email">
    Email
</label>

<input
    type="email"
    id="email"
>
```


# SELECT — Selection Menu

Search terms: select, dropdown, option

## Syntax

```html
<select>

    <option>Option One</option>
    <option>Option Two</option>

</select>
```


# TEXTAREA — Multi-Line Input

Search terms: textarea, message, multiline

## Syntax

```html
<textarea></textarea>
```


# BUTTON — Button

Search terms: button, submit

## Syntax

```html
<button type="button">
    Button
</button>
```

Submit:

```html
<button type="submit">
    Submit
</button>
```


# DETAILS — Expandable Content

Search terms: details, summary, accordion, expandable

## Syntax

```html
<details>

    <summary>
        More Information
    </summary>

    <p>
        Hidden content.
    </p>

</details>
```


# PROGRESS — Progress Indicator

Search terms: progress, percentage

## Syntax

```html
<progress value="70" max="100">
    70%
</progress>
```


# METER — Measurement

Search terms: meter, measurement, range

## Syntax

```html
<meter value="0.7" min="0" max="1">
    70%
</meter>
```


# HR — Thematic Break

Search terms: hr, horizontal line, divider, break

## Syntax

```html
<hr>
```


# BR — Line Break

Search terms: br, line break, new line

## Syntax

```html
First line.<br>
Second line.
```


# COMMENT — HTML Comment

Search terms: comment, note

## Syntax

```html
<!-- This is an HTML comment -->
```