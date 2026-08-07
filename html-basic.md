# HTML Basic

1. [Tags: Opening and Closing Tags](#tags-opening-and-closing-tags)
2. [HTML Attributes](#html-attributes)
   - [Common HTML Attributes](#common-html-attributes)
3. [Basic HTML Structure](#basic-html-structure)
4. [Basic HTML Tags](#basic-html-tags)
   - [1. Heading Tags](#1-heading-tags)
   - [2. Paragraph](#2-paragraph)
   - [3. Line Break](#3-line-break)
   - [4. Horizontal Line](#4-horizontal-line)
   - [5. Bold Text](#5-bold-text)
   - [6. Italic Text](#6-italic-text)
   - [7. Underlined Text](#7-underlined-text)
   - [8. Highlighted Text](#8-highlighted-text)
   - [9. Small Text](#9-small-text)
   - [10. Deleted Text](#10-deleted-text)
   - [11. Inserted Text](#11-inserted-text)
   - [12. Superscript](#12-superscript)
   - [13. Subscript](#13-subscript)
   - [14. Hyperlink](#14-hyperlink)
   - [15. Image Tag](#21-image-tag)
   - [16. Division](#16-division)
   - [17. Span](#17-span)
   - [18. Lists](#18-lists)
      - [Unordered List](#unordered-list)
      - [Ordered List](#ordered-list)
   - [19. Comment](#19-comment)
   - [20. Preformatted Text](#20-preformatted-text)

## Tags: Opening and Closing Tags

In **HTML**, ``tags`` are special keywords enclosed in angle brackets ``< >`` that define the structure and content of a web page. They tell the browser how to display text, images, links, forms, and other elements.

Most HTML elements have:

* **Opening tag:** `<tagname>`
* **Closing tag:** `</tagname>`

Syntax:

```html
<tagname>Content</tagname>
```

Example:

```html
<p>This is a paragraph.</p>
```

* Opening tag: `<p>`
* Content: `This is a paragraph.`
* Closing tag: `</p>`

Some tags are **self-closing (void elements)** and do not need a closing tag.

Syntax:

```html
<tagname>
```

Example:

```html
<br>
<hr>
<img src="image.jpg" alt="Image">
```

---

## HTML Attributes

Attributes provide extra information about an element. They are written inside the opening tag.

Syntax:

```html
<tagname attribute="value">Content</tagname>
```

### Common HTML Attributes

| Attribute | Purpose                    | Example                  |
| --------- | -------------------------- | ------------------------ |
| `id`      | Unique identifier          | `<p id="para1">`         |
| `class`   | Group elements for styling | `<div class="box">`      |
| `style`   | Inline CSS                 | `<p style="color:red;">` |
| `title`   | Tooltip text               | `<p title="Hello">`      |
| `href`    | Link destination           | `<a href="page.html">`   |
| `src`     | Image source               | `<img src="image.jpg">`  |
| `alt`     | Alternative text           | `<img alt="Nature">`     |
| `width`   | Width                      | `<img width="200">`      |
| `height`  | Height                     | `<img height="150">`     |
| `lang`    | Language of the document   | `<html lang="en">`       |

---

## Basic HTML Structure

```html
<html>
    <head>
        <title>My First HTML Page</title>
    </head>
    <body>
        <h1>Welcome to HTML</h1>
        <p>This is a basic HTML page.</p>
    </body>
</html>
```

```mermaid
graph TD
    A["html"]
    B["head"]
    C["title"]
    D["body"]
    E["h1"]
    F["p"]

    A --> B
    A --> D
    B --> C
    D --> E
    D --> F
```

| **HTML Tag** | **Purpose**                                                                                |
| ------------ | ------------------------------------------------------------------------------------------ | 
| `<html>`     | The root element of an HTML document. It contains all other HTML elements.                 | 
| `<head>`     | Contains metadata such as title, styles, scripts, and meta information.                    |
| `<title>`    | Defines the title of the webpage shown in the browser tab.                                 |
| `<body>`     | Contains all the content displayed on the webpage, such as text, images, links, and forms. | 

---

## Basic HTML Tags

### 1. Heading Tags

```html
<h1>Main Heading</h1>
<h2>Sub Heading</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
```

---

### 2. Paragraph

```html
<p>This is a paragraph.</p>
```

---

### 3. Line Break

```html
First Line<br>
Second Line
```

---

### 4. Horizontal Line

```html
<hr>
```

---

### 5. Bold Text

```html
<b>Bold Text</b>
```

or

```html
<strong>Important Text</strong>
```

---

### 6. Italic Text

```html
<i>Italic Text</i>
```

or

```html
<em>Emphasized Text</em>
```

---

### 7. Underlined Text

```html
<u>Underlined Text</u>
```

---

### 8. Highlighted Text

```html
<mark>Highlighted Text</mark>
```

---

### 9. Small Text

```html
<small>Small Text</small>
```

---

### 10. Deleted Text

```html
<del>Deleted Text</del>
```

---

### 11. Inserted Text

```html
<ins>Inserted Text</ins>
```

---

### 12. Superscript

```html
x<sup>2</sup>
```

Output:

```
x²
```

---

### 13. Subscript

```html
H<sub>2</sub>O
```

Output:

```
H₂O
```

---

### 14. Hyperlink

```html
<a href="https://www.google.com" title="example">Google</a>
```

##### Common Attributes

| Attribute | Description | Example | 
| --------- | ----------- | ------- | 
| href | Specifies the destination URL or file | href="https://www.example.com" | 
 | title | Displays extra information when the mouse hovers over the link | title="Visit Example" |

---

### 21. Image Tag

The `<img>` tag is used to display an image on a web page.

##### Common Attributes

| Attribute | Description | Example |
| --------- | ----------- | ------- |
| `src` | Specifies the path or URL of the image | `src="image.jpg"` |
| `alt` | Displays alternative text if the image cannot be loaded | `alt="HTML Logo"` |
| `width` | Sets the width of the image | `width="300"` |
| `height` | Sets the height of the image | `height="200"` |

```html
<img src="html-logo.png"
     alt="HTML Logo"
     width="300"
     height="200">
```

---

### 16. Division

```html
<div>
    This is a division.
</div>
```

---

### 17. Span

```html
<p>This is <span style="color:red;">red</span> text.</p>
```

---

### 18. Lists

**``type`` attribute**

The `type` attribute specifies the numbering style of an ordered list (`<ol>`) or the bullet style of an unordered list (`<ul>`).


#### Unordered List

| Type             | Description     |
| ---------------- | --------------- |
| `disc` (default) | ● Filled circle |
| `circle`         | ○ Hollow circle |
| `square`         | ■ Square        |
| `none`           | No bullet       |


```html
<ul type="disc">
    <li>Apple</li>
    <li>Banana</li>
    <li>Mango</li>
</ul>
```

#### Ordered List

| Type          | Description              | Example Output |
| ------------- | ------------------------ | -------------- |
| `1` (default) | Numbers                  | 1, 2, 3        |
| `A`           | Uppercase letters        | A, B, C        |
| `a`           | Lowercase letters        | a, b, c        |
| `I`           | Uppercase Roman numerals | I, II, III     |
| `i`           | Lowercase Roman numerals | i, ii, iii     |

```html
<ol type="1">
    <li>Wake Up</li>
    <li>Study</li>
    <li>Sleep</li>
</ol>
```

---

### 19. Comment

```html
<!-- This is a comment -->
```

---

### 20. Preformatted Text

```html
<pre>
Line 1
    Line 2
        Line 3
</pre>
```

---
