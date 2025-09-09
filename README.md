# HTML Cheat Sheet

Essential HTML tags and attributes for web development.

---

## Table of Contents
- [Document Structure](#document-structure)
- [Text Elements](#text-elements)
- [Links & Media](#links--media)
- [Forms](#forms)
- [Semantic Elements](#semantic-elements)
- [Meta Tags](#meta-tags)

---

## Document Structure

| Tag | Description | Example |
|-----|-------------|---------|
| `<!DOCTYPE html>` | HTML5 document type | `<!DOCTYPE html>` |
| `<html>` | Root element | `<html lang="en">` |
| `<head>` | Document metadata | `<head>...</head>` |
| `<body>` | Document content | `<body>...</body>` |

## Text Elements

| Tag | Description | Example |
|-----|-------------|---------|
| `<h1>` to `<h6>` | Headings | `<h1>Main Title</h1>` |
| `<p>` | Paragraph | `<p>Text content</p>` |
| `<strong>` | Important text | `<strong>Bold text</strong>` |
| `<em>` | Emphasized text | `<em>Italic text</em>` |
| `<br>` | Line break | `Line 1<br>Line 2` |
| `<hr>` | Horizontal rule | `<hr>` |

## Links & Media

| Tag | Description | Example |
|-----|-------------|---------|
| `<a>` | Hyperlink | `<a href="#">Link</a>` |
| `<img>` | Image | `<img src="image.jpg" alt="Description">` |
| `<video>` | Video content | `<video src="video.mp4" controls></video>` |
| `<audio>` | Audio content | `<audio src="audio.mp3" controls></audio>` |

## Forms

| Tag | Description | Example |
|-----|-------------|---------|
| `<form>` | Form container | `<form action="/submit" method="post">` |
| `<input>` | Input field | `<input type="text" name="username">` |
| `<textarea>` | Multi-line input | `<textarea name="message"></textarea>` |
| `<select>` | Dropdown | `<select><option>Option 1</option></select>` |
| `<button>` | Button | `<button type="submit">Submit</button>` |
| `<label>` | Input label | `<label for="username">Username:</label>` |

## Semantic Elements

| Tag | Description | Example |
|-----|-------------|---------|
| `<header>` | Page/section header | `<header>Site header</header>` |
| `<nav>` | Navigation links | `<nav>Menu items</nav>` |
| `<main>` | Main content | `<main>Primary content</main>` |
| `<article>` | Standalone content | `<article>Blog post</article>` |
| `<section>` | Document section | `<section>Content section</section>` |
| `<aside>` | Sidebar content | `<aside>Related links</aside>` |
| `<footer>` | Page/section footer | `<footer>Copyright info</footer>` |

## Meta Tags

*See [head.md](./head.md) for comprehensive meta tag reference*

| Meta Tag | Description | Example |
|----------|-------------|---------|
| `<title>` | Page title | `<title>Page Title</title>` |
| `<meta charset>` | Character encoding | `<meta charset="UTF-8">` |
| `<meta viewport>` | Responsive design | `<meta name="viewport" content="width=device-width, initial-scale=1">` |
| `<meta description>` | Page description | `<meta name="description" content="Page description">` |

---

## Resources
- [MDN HTML Reference](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [HTML5 Specification](https://html.spec.whatwg.org/)
- [Can I Use](https://caniuse.com/)

---
*Originally compiled from various sources. Contributions welcome!*
