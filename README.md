# responsive-css

This repo is personal but anyone who want to see can view and read to fresh their HTML and CSS and its guide for beautiful layouts.

# A High-Level Overview of Web Development

When a user requests a page (URL) on the browser, the browser asks the server to access the file. The server sends the requested files as a response: HTML, CSS, and JavaScript.

These files are the core files that any browser can understand. Upon receiving them, the browser renders the page.

The process where the browser understands the code and renders it is called **Front-end Web Development**.

Whenever the file is simply sent from the server to the browser without any changes, it's called a **Static Website**.

**Example**: When a user requests a blog post or a landing page, the content appears on the browser exactly as it is on the server, without any change.

In contrast, when content is requested based on user preferences or the latest updates, the server processes the request or queries the latest data from the database. This data is then processed and assembled, alongside HTML, CSS, and JavaScript files. This process is handled by a back-end application, and then the final (pre-rendered) data or just the data itself is sent back to the browser.

This process is called **Back-end Web Development** or a **Dynamic Website**, as the content is dynamically assembled from different sources.

**Example**: Udemy.com, where the contents are ever-changing (e.g., latest courses, ratings, reviews, comments). All these changes are processed and queried into the database. Upon request, the data is assembled by a back-end application and sent as a dynamic response to the client.

---

## The 3 Languages of the Front-End

1. **HTML (Noun)**: Contains all the raw content of the page like images, text, buttons, etc.
2. **CSS (Adjective)**: Describes the layout and presentation of the content with styles.
3. **JavaScript (Verb)**: An actual programming language of the front-end that allows adding dynamic and interactive content to the front-end. It also allows manipulation of the content of the page (HTML and CSS), loading data from the server, and even building the entire front-end application.

---

## HTML

- **HyperText Markup Language**
- HTML is a markup language that structures and describes the content of a webpage (it is not a programming language).
- HTML consists of different types of elements: paragraphs, links, headings, images, videos, etc.
- Web browsers understand HTML and render HTML code as websites.

---

## HTML Document Structure

1. `<!DOCTYPE html>`  
   Specifies that the webpage should use modern HTML5, unlike older XHTML and HTML versions below 5.

2.`<html>`  
 Wraps all the content needed to make a webpage fully functional.

3. `<head>`

   ```html
   <meta
     name="description"
     content="Wraps the required metadata for SEO and external sources that aid in maintaining the page."
   />
   <title>HTML Document Structure</title>
   ```

   `</head>`

4. `<body>`

   ```html
   <headers>Wraps top most section of the page</headers>
   <main>Wraps all the main content of the page.</main>
   ```

   `</body>`

5. `<footer>`

   ````html
   	Wraps all the top bottom section, mostly webpage additional information, and scripts
     <script src='../main.js'></script>
   	```
    `</footer>`

    `</body>`
   ````

`</html>`

## Summary of Key Sections:

- **`<!DOCTYPE html>`**: Defines the document as HTML5.
- **`<html>`**: The root element that wraps everything.
- **`<head>`**: Contains metadata, external links (CSS, fonts), and the page title.
- **`<body>`**: Contains all visible content (text, images, videos, etc.) for the webpage.
- **`<header>`**: Top section, usually containing the title or logo.
- **`<nav>`**: Navigation section with links.
- **`<main>`**: Primary content of the page (main sections and content).
- **`<footer>`**: Bottom section for things like copyright and additional links.
- **`<script>`**: For linking external JavaScript files or embedding inline scripts.

<br>
<br>
<br>
<br>
<br>

---

# CSS

---

# Cascading Style Sheet

CSS describes the visual style and presentation of the content written in HTML
