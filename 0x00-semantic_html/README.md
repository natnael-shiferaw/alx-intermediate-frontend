# Semantic HTML: Best Practices for Accessibility and SEO

## Project Overview
This project emphasizes the importance of Semantic HTML, accessibility, and SEO optimization. Through structured tasks, you will learn to enhance the usability and visibility of web pages by using semantic elements, ARIA roles, and attributes effectively. The focus is on creating accessible and SEO-friendly web pages while adhering to modern web development standards.

### Learning Objectives
- **Master Semantic HTML**: Use semantic elements like `<header>`, `<main>`, `<article>`, `<section>`, and `<footer>` for better organization and accessibility.
- **Optimize for SEO**: Improve webpage visibility through meta tags and proper document structure.
- **Enhance Accessibility**: Utilize ARIA roles and attributes for better accessibility for users with disabilities.
- **Form Design Best Practices**: Create accessible and user-friendly forms using modern HTML techniques.
- **Incremental Development**: Build progressively on previous tasks to enhance web pages step by step.

### Requirements
- Familiarity with HTML5.
- Basic knowledge of semantic HTML elements and their purpose.
- Understanding of SEO and its role in web development.
- Awareness of web accessibility standards, including ARIA roles and attributes.

## Tasks

### 0. Creating a Structured HTML Document Using Semantic Elements
**Objective**: Practice structuring a simple HTML document using semantic elements.

#### Instructions
- Create a file named `0-index.html`.
- Inside the `<html>` tag, add the `<head>` and `<body>` tags.
- Inside the `<body>` tag:
  - Add a `<header>` containing a `<nav>` with at least three links.
  - Create a `<main>` section with an `<article>` that includes:
    - An `<h1>` tag for the title.
    - A `<section>` for the content.
  - Add a `<footer>` with the text: `@copyright`.

#### Repository Details
- **Directory**: `0x00-semantic_html`
- **File**: `0-index.html`

---

### 1. Enhancing HTML Document with Meta Tags and Title for SEO and Accessibility
**Objective**: Improve the structure of the HTML document by adding meta tags for SEO, accessibility, and responsiveness.

#### Instructions
- Copy the content of `0-index.html` into `1-index.html`.
- Inside the `<head>` tag, add:
  - A `<meta>` tag with `charset="utf-8"`.
  - Four additional `<meta>` tags:
    1. `name="description" content="A blog post about semantic HTML and accessibility practices."`
    2. `name="keywords" content="HTML, Semantic, Accessibility, Blog, SEO"`
    3. `name="author" content="<author name>"`
    4. `name="viewport" content="width=device-width, initial-scale=1.0"`
  - A `<title>` tag with the content: `Semantic HTML Blog Post`.

#### Repository Details
- **Directory**: `0x00-semantic_html`
- **File**: `1-index.html`

---

### 2. Creating a Blog Post Layout Using Semantic HTML Elements
**Objective**: Apply semantic elements to create a blog post layout.

#### Instructions
- Copy the content of `1-index.html` into `2-index.html`.
- Update the `<header>` tag to include:
  - An `<h1>` tag with `My Blog`.
  - A `<nav>` containing a `<ul>` with three `<li>` elements for:
    - Home
    - About
    - Contact
- Enhance the `<article>` in `<main>` by adding:
  - A `<header>` with an `<h2>`: `Understanding Semantic HTML`.
  - A `<p>`: `Published on <time datetime="2024-09-10">September 10</time>`.
  - A `<section>` with:
    - `<h3>`: `Introduction`
    - `<p>`: `Semantic HTML helps improve the accessibility and SEO of your website. In this post, we’ll explore its benefits and how to implement it.`
  - Another `<section>` with:
    - `<h3>`: `Main Content`
    - `<p>`: `Using elements like <code>&lt;article&gt;</code>, <code>&lt;section&gt;</code>, and <code>&lt;header&gt;</code> ensures that both users and search engines can better understand the structure and content of a webpage.`
    - `<figure>` containing:
      - `<img src="" alt="example">`
      - `<figcaption>`: `An illustration of semantic HTML elements`
  - A third `<section>` with:
    - `<h3>`: `Conclusion`
    - `<p>`: `By adopting semantic HTML, you enhance your site's accessibility, improve SEO, and make the content easier to navigate.`
  - A `<footer>` with:
    - `<p>`: `Written by <author name>`
    - `<p>`: `Published on 2024-09-11`

#### Repository Details
- **Directory**: `0x00-semantic_html`
- **File**: `2-index.html`

---

### 3. Enhancing Form Accessibility with ARIA Roles and Attributes
**Objective**: Implement ARIA roles and attributes to improve form accessibility.

#### Instructions
- Copy the content of `2-index.html` into `3-index.html`.
- Inside the `<main>` element, add a new `<section>` containing:
  - A `<form>` with:
    - `action="#"`
    - `method="POST"`
    - `aria-labelledby="form-title"`
    - `role="form"`
  - Inside the `<form>`, include:
    - A `<div>` containing:
      - `<label for="name">Name:</label>`
      - `<input type="text" id="name" name="name" aria-required="true">`
    - Another `<div>` containing:
      - `<label for="email">Email:</label>`
      - `<input type="email" id="email" name="email" aria-required="true">`
    - A `<div>` with:
      - `<button type="submit" aria-label="Submit the form">Submit</button>`
    - A `<div>` with:
      - `aria-live="polite"`
      - `role="alert"`

#### Repository Details
- **Directory**: `0x00-semantic_html`
- **File**: `3-index.html`

---

## Project Repository
**GitHub Repository**: `alx-intermediate-frontend`
