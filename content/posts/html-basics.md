---
title: "HTML Basics: A Beginner's Guide and Cheatsheet"
date: 2025-09-20
draft: false
---

## Introduction to HTML

HTML, which stands for HyperText Markup Language, is the standard markup language for creating web pages and web applications. It is the foundation of every website, providing the structure and content of the page.

## Basic Structure of an HTML Document

An HTML document has a simple, hierarchical structure. Here is the basic boilerplate:

```html
<!DOCTYPE html>
<html>
<head>
    <title>Page Title</title>
</head>
<body>

    <h1>My First Heading</h1>
    <p>My first paragraph.</p>

</body>
</html>
```

*   `<!DOCTYPE html>`: This declaration defines that this document is an HTML5 document.
*   `<html>`: The root element of an HTML page.
*   `<head>`: Contains meta-information about the HTML page, such as the title.
*   `<title>`: Specifies a title for the HTML page (which is shown in the browser's title bar or in the page's tab).
*   `<body>`: The main content of the HTML page.

## HTML Elements Cheatsheet

Here is a cheatsheet of some of the most common HTML elements:

| Element | Description |
|---|---|
| `<h1>` to `<h6>` | Headings of different levels. |
| `<p>` | A paragraph of text. |
| `<a>` | A hyperlink. |
| `<img>` | An image. |
| `<ul>` | An unordered list. |
| `<ol>` | An ordered list. |
| `<li>` | A list item. |
| `<div>` | A division or a section in an HTML document. |
| `<span>` | An inline container used to mark up a part of a text, or a part of a document. |
| `<table>` | A table. |
| `<tr>` | A row in a table. |
| `<th>` | A header cell in a table. |
| `<td>` | a cell in a table. |
| `<form>` | An HTML form for user input. |
| `<input>` | An input control. |
| `<button>` | A clickable button. |

## HTML Graphical Layout

HTML provides several elements for defining the different parts of a web page's layout. Here are some of the most common layout elements:

*   `<header>`: Defines a header for a document or a section.
*   `<nav>`: Defines a set of navigation links.
*   `<section>`: Defines a section in a document.
*   `<article>`: Defines an independent, self-contained article.
*   `<aside>`: Defines content aside from the content (like a sidebar).
*   `<footer>`: Defines a footer for a document or a section.

Here is an example of a simple layout:

```html
<header>
  <h1>My Website</h1>
  <nav>
    <ul>
      <li><a href="#">Home</a></li>
      <li><a href="#">About</a></li>
      <li><a href="#">Contact</a></li>
    </ul>
  </nav>
</header>

<section>
  <article>
    <h2>Article Title</h2>
    <p>Article content...</p>
  </article>
</section>

<aside>
  <h3>Related Links</h3>
  <ul>
    <li><a href="#">Link 1</a></li>
    <li><a href="#">Link 2</a></li>
  </ul>
</aside>

<footer>
  <p>Copyright &copy; 2025</p>
</footer>
```

This blog post provides a basic overview of HTML. There is much more to learn, but this should give you a solid foundation to start building your own web pages.
