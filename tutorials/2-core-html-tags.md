# Core HTML Tags

1. **`<p>`**: Adds a paragraph of text.
2. **Headlines (`<h1>` to `<h6>`)**: Defines headings from most important to least important.
3. **`<ul>` and `<ol>`**: Define unordered (bulleted) and ordered (numbered) lists.
4. **`<li>`**: Defines each item within a list.
5. **`<img>`**: Embeds an image.
6. **`<a>`**: Creates hyperlinks to other pages or locations.
7. **`<div>`**: Groups content for styling and layout purposes.

---

### 1. `<p>`: Paragraph
The `<p>` tag is used to define paragraphs in HTML. It's used to add blocks of text.

```html
<p>This is a paragraph of text.</p>
```

### 2. Headline Tags: `<h1>` to `<h6>`
Headline tags are used to define headings of different levels, from `<h1>` (most important) to `<h6>` (least important). 

```html
<h1>Main Heading (most important)</h1>
<h2>Subheading</h2>
<h3>Sub-subheading</h3>
<h4>...</h4>
<h5>...</h5>
<h6>Least Important Heading</h6>
```

- Use `<h1>` for the main title of the page.
- Use `<h2>` to `<h6>` for subheadings as needed.

### 3. `<ul>`: Unordered List
The `<ul>` tag is used to create an unordered list, typically styled as bullet points.

```html
<ul>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ul>
```

### 4. `<ol>`: Ordered List
The `<ol>` tag is used to create an ordered list, typically numbered.

```html
<ol>
    <li>Step 1</li>
    <li>Step 2</li>
    <li>Step 3</li>
</ol>
```

### 5. `<li>`: List Item
The `<li>` tag is used to define an item in either an ordered (`<ol>`) or unordered (`<ul>`) list. Each list item is enclosed in `<li>` tags.

### 6. `<img>`: Image
The `<img>` tag is used to embed an image in an HTML page. It is a self-closing tag and requires at least two attributes:
- `src`: The URL/path to the image.
- `alt`: Alternative text describing the image for accessibility.

```html
<img src="example.jpg" alt="Description of the image">
```

### 7. `<a>`: Anchor
The `<a>` tag is used to create hyperlinks. It requires an `href` attribute to specify the link's destination.

```html
<a href="https://www.example.com">Visit Example Website</a>
```

You can also use `<a>` to link to other parts of your page or to an email address.

### 8. `<div>`: Division
The `<div>` tag is used as a container for other HTML elements. It helps group and organize content and is commonly used for styling and layout purposes.

```html
<div>
    <h2>Section Title</h2>
    <p>This is some content inside a div.</p>
</div>
```

---

These tags form the foundation for structuring and organizing content on your web page.

You can find a comprehensive list of all HTML5 tags and their descriptions on the following resource:

[MDN Web Docs: HTML elements reference](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)

MDN Web Docs is an excellent reference maintained by Mozilla, providing detailed information about all HTML5 tags, their attributes, and usage examples.
