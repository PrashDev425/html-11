
# HTML Basic
---

## Introduction

**Hypertext Markup Language (HTML)** is the standard markup language for documents designed to be displayed in a web browser. It defines the content and structure of web content.

## HTML Structure

**Structure:**

```html
<html>
    <head>
        <title></title>
    </head>
    <body>

    </body>
</html>
```
- ``<html>`` : Root element of the HTML page.
- ``<head>`` : Contains meta information (title, styles, scripts).
- ``<title>`` : Sets the title shown in the browser tab.
- ``<body>`` : Contains the visible content of the webpage.

**Task:**  
Create a simple HTML document named `firstpage.html` that displays a heading and a short paragraph.

**Example:**

```html
<html>
<head>
    <title>HTML Page</title>
</head>
<body>
    <h1>Welcome to My First HTML Page</h1>
    <p>This is my introduction to web development using HTML.</p>
</body>
</html>
```
**Key Points:**

- HTML uses tags enclosed in ``< >``.
- Most tags have opening ``<tag>`` and closing ``</tag>``.
- HTML is not case-sensitive, but lowercase is preferred.
- HTML defines structure, not style (CSS handles design).

---

## Background, Foreground & Titles

**Task:**  
Modify your page with background and text color using `<body>` attributes.

You can use:

- Color names (e.g., ``lightblue``, ``pink``, ``yellow``)
- Hex codes (e.g.,``#ffcc00``)
- RGB values (e.g., ``rgba(225, 201, 106, 1)``)

```html
<html>
<head>
    <title>HTML Page</title>
</head>
<body bgcolor="lightblue" text="darkblue">
    <h2>HTML Colors Example</h2>
    <p>The background is light blue and text is dark blue.</p>
</body>
</html>
```

---

## Headings, Paragraphs, and Line Breaks

**Task:**  
Use heading tags (`<h1>` to `<h6>`), paragraph (`<p>`), and line break (`<br>`) tags.

```html
<html>
<head>
    <title>HTML Page</title>
</head>
<body>
   <h1>Heading 1</h1>
   <h2>Heading 2</h2>
   <h3>Heading 3</h3>
   <h4>Heading 4</h4>
   <h5>Heading 5</h5>
   <h6>Heading 6</h6>
   <p>This is a paragraph.<br>It continues on the next line.</p>
</body>
</html>
```

---

## Text Formatting

**Task:**  
Create a file `formatting.html` using the following tags:
```html
<b>Bold</b>, <i>Italic</i>, <u>Underline</u>, <mark>Marked</mark>, 
<sup>Superscript</sup>, <sub>Subscript</sub>, <em>Emphasis</em>
```

**Example:**
```html
<html>
<head>
    <title>HTML Page</title>
</head>
<body>
   <p>This is <b>bold</b> and <i>italic</i> text.</p>
   <p>This is <mark>Marked</mark>, <u>Underline</u>, <sup>Superscript</sup>, <sub>Subscript</sub> and <em>Emphasis</em></p>
   <p>Water formula is H<sub>2</sub>O and 3<sup>2</sup> = 9.</p>
</body>
</html>
```

---

## Lists (Ordered, Unordered & Definition)

| **Type**             | **Tag** | **Description**                                                                 |
| -------------------- | ------- | ------------------------------------------------------------------------------- |
| **Ordered List**     | `<ol>`  | Displays list items in a **specific order** (numbers, letters, roman numerals). |
| **Unordered List**   | `<ul>`  | Displays list items with **bullets** (no specific order).                       |
| **Description List** | `<dl>`  | Displays **terms and their descriptions** (like a glossary).                    |

**Task:**  
Create a file `lists.html` and practice all three list types.


### Types of Ordered List:

| Type       | Description              | Example Output  |
| ---------- | ------------------------ | --------------- |
| `type="1"` | Numbers (default)        | 1, 2, 3, ...    |
| `type="A"` | Uppercase letters        | A, B, C, ...    |
| `type="a"` | Lowercase letters        | a, b, c, ...    |
| `type="I"` | Uppercase Roman numerals | I, II, III, ... |
| `type="i"` | Lowercase Roman numerals | i, ii, iii, ... |

### Types of Unordered List:

| Type            | Description            | Example Bullet |
| --------------- | ---------------------- | -------------- |
| `type="disc"`   | Solid circle (default) | ●              |
| `type="circle"` | Hollow circle          | ○              |
| `type="square"` | Solid square           | ■              |


```html
<html>
<head>
    <title>HTML Page</title>
</head>
<body>
   <h2>Ordered List</h2>
   <ol type="A" start="3">
      <li>HTML</li>
      <li>CSS</li>
      <li>JavaScript</li>
   </ol>

   <h2>Unordered List</h2>
   <ul type="square">
      <li>Chrome</li>
      <li>Firefox</li>
      <li>Edge</li>
   </ul>

   <h2>Definition List</h2>
   <dl>
      <dt>HTML</dt>
      <dd>HyperText Markup Language</dd>
   </dl>
</body>
</html>
```

---

## Creating Links

**Task:**  
Learn how to create internal and external links using the `<a>` tag.

```html
<html>
<head>
    <title>HTML Page</title>
</head>
<body>
   <a href="lists.html">Open Lists Page</a><br>
   <a href="https://www.google.com" target="_blank">Go to Google</a>
</body>
</html>
```

---

## Address and Comments

**Task:**
Use `<address>` and comments to make your page more descriptive.

```html
<html>
<head>
    <title>HTML Page</title>
</head>
<body>
   <address>
   Written by: <b>John Doe</b><br>
   Email: john@example.com<br>
   Location: Kathmandu, Nepal
   </address>
</body>
</html>
```

---

## Final Practical — Simple Information Page about HTML

**Objective:**  
Create a single-page HTML document called `info.html` that includes:
- Headings & Paragraphs  
- Text Formatting  
- Ordered & Unordered Lists  
- A Link  
- An Address Section  

**Example Output:**
---
