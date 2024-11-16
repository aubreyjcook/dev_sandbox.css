# CSS Outline

## Purpose

This is a sandbox repo dedicated to a specific technology, that technology is: CSS (CSS3.)

The content of this repo is intended to be comprised of code created with this technology independent of other technologies, but doesn't necessarily exclude the use of other technologies, especially when the main technology is dependent on or heavily used in conjuction with other technologies.

This repo was created and maintained mainly by developer AJC. This outline is meant to overview the developers personal understanding and application of the technology, as such it includes personal observations and documentation that represents the domain of the developers knowledge. The documentation listed in this outline isn't intended to comprehensively document the technology, but when documentation mirrors official documentation, it is intended to be a reflection of the developers understanding and actualy knowledge of the technology alongside any specific highly relevant key points to the developers personal application and experience with the technology.

## Technology Overview

CSS stands for Cascading Style Sheets. It is a markup language that is used to style the presentation of a document written in HTML or XML (including XHTML.) CSS describes how elements should be rendered on screen, on paper, in speech, or on other media. It is a fundamental technology of the World Wide Web, alongside HTML and JavaScript.

### Fundamentals

CSS describes how HTML elements should be displayed. CSS is interpreted by web browsers to render the style of an HTML document.

Web browsers view HTML documents as content, and CSS as style. A simple analog is that of a text document or the physical paper text of a book, magazine, or page. When viewing text in a raw text viewer like Notepad, text is displayed as raw content, and this content can be **organized** into a hierarchy using a markup language like HTML or XML (which utilize two different approachs to organizing content,) but the visible style and representation of the content is determined by the program displaying the content, altering things like font, text color, size, and other visual properties.

We will not go into the details of HTML or XML in this outline, but one of the most important aspects of HTML to understand in the context of CSS is the property of **sematics** and **logical properties**

The reason for this is that CSS to a lesser extent can control this, but is not specifically intended to do so. But CSS does apply styling upon the structure of the HTML documents semantic and logical flow.

#### HTML in relation to CSS

##### HTML Semantics

**HTML** utilizes sematics to describe the meaning of the content, here are some minimal examples:

```html
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
```

```html

<p>Paragraph</p>

<blockquote>Blockquote</blockquote>

<code>Code</code>

<em>Emphasis</em>

<strong>Strong</strong>

<ol>
  <li>Ordered List Item 1</li>
  <li>Ordered List Item 2</li>
  <li>Ordered List Item 3</li>
</ol>

<ul>
  <li>Unordered List Item 1</li>
  <li>Unordered List Item 2</li>
  <li>Unordered List Item 3</li>
</ul>

```

```html

<a href="https://www.google.com">Link</a>

<img src="image.jpg" alt="Image">

```

##### HTML Logical Properties

**HTML** utilizes logical properties to describe the flow of content as it is displayed, HTML logical properties break down into two main categories: **block** and **inline** elements, as well as a third category of **inline-block** elements.

here are some minimal examples:

```html
<div>Block Element</div>
<div>Block Element</div>
<div>Block Element</div>
```

```html
<span>Inline Element</span>
<span>Inline Element</span>
<span>Inline Element</span>
```

```html
<div style="display: inline-block;">Inline Block Element</div>
<div style="display: inline-block;">Inline Block Element</div>
<div style="display: inline-block;">Inline Block Element</div>
```

### Primary Resources

#### Documentation

#### Tutorials

#### Articles