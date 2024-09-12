# Introduction to HTML and Semantic Web

## 1. What is HTML?

HTML (Hypertext Markup Language) is the standard markup language for creating web pages. It describes the structure of a web page semantically and originally included cues for the appearance of the document.

- HTML elements are the building blocks of HTML pages
- HTML elements are represented by tags
- Browsers don't display the HTML tags, but use them to render the content of the page

## 2. Basic Structure of an HTML Document

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document Title</title>
</head>
<body>
    <!-- Content goes here -->
</body>
</html>
```

## 3. Common HTML Elements

- Headings: `<h1>` to `<h6>`
- Paragraphs: `<p>`
- Links: `<a href="url">link text</a>`
- Images: `<img src="image.jpg" alt="description">`
- Lists: 
  - Unordered: `<ul>` with `<li>` items
  - Ordered: `<ol>` with `<li>` items
- Div: `<div>` (generic container)

## 4. What is Semantic HTML?

Semantic HTML introduces meaning to the web page structure, rather than just presentation. It uses HTML tags that convey the meaning of the content.

### Benefits of Semantic HTML:
1. Improves accessibility
2. Enhances SEO
3. Easier to maintain and understand code

## 5. Examples of Semantic HTML Elements

- `<header>`: Introductory content or navigational links
- `<nav>`: Navigation links
- `<main>`: Main content of the document
- `<article>`: Self-contained content
- `<section>`: Thematic grouping of content
- `<aside>`: Content tangentially related to the content around it
- `<footer>`: Footer of a document or section

## 6. Semantic HTML vs. Non-Semantic HTML

### Non-Semantic Example:
```html
<div id="header">
    <div class="nav">
        <!-- navigation items -->
    </div>
</div>
<div id="main-content">
    <div class="article">
        <!-- article content -->
    </div>
</div>
<div id="footer">
    <!-- footer content -->
</div>
```

### Semantic Example:
```html
<header>
    <nav>
        <!-- navigation items -->
    </nav>
</header>
<main>
    <article>
        <!-- article content -->
    </article>
</main>
<footer>
    <!-- footer content -->
</footer>
```

## 7. Best Practices for Semantic HTML

1. Use appropriate tags for their intended purpose
2. Avoid overusing `<div>` and `<span>` when a semantic element would be more appropriate
3. Use heading tags (`<h1>` to `<h6>`) to create a logical document structure
4. Utilize `<strong>` and `<em>` for importance and emphasis, not just for styling
5. Make use of WAI-ARIA roles and properties when HTML5 semantic elements are not sufficient

## 8. Exercise

Task: Convert the following non-semantic HTML into semantic HTML:

```html
<div class="header">
    <h1>My Website</h1>
    <div class="nav">
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </div>
</div>
<div class="main">
    <div class="article">
        <h2>Welcome to My Website</h2>
        <p>This is a paragraph about my website.</p>
    </div>
    <div class="sidebar">
        <h3>Recent Posts</h3>
        <ul>
            <li>Post 1</li>
            <li>Post 2</li>
            <li>Post 3</li>
        </ul>
    </div>
</div>
<div class="footer">
    <p>&copy; 2024 My Website. All rights reserved.</p>
</div>
```

## 9. Conclusion

- Semantic HTML is crucial for creating well-structured, accessible, and SEO-friendly web pages
- It improves code readability and maintainability
- Always strive to use the most appropriate HTML elements for your content

## 10. Additional Resources

- [MDN Web Docs: HTML elements reference](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)
- [W3C: HTML5 Semantic Elements](https://www.w3schools.com/html/html5_semantic_elements.asp)
- [Web Accessibility Initiative (WAI)](https://www.w3.org/WAI/)