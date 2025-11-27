# HTML Advanced - README.md

## Overview

This project is the **HTML Advanced** stage of the overall front-end curriculum. The goal is to translate a Figma design into a complete and semantically correct HTML structure **without CSS**. You are expected to focus only on layout structure, hierarchy, and proper HTML tags.

You will later style this exact structure in the **CSS Advanced** project.

---

## Project Objectives

* Build a webpage from scratch **using only HTML**.
* Reproduce the layout seen in the Figma design file.
* Understand how to translate a design into semantic structure.
* Prepare clean HTML that will later be styled with CSS.

This project ensures you understand:

* Semantic tags (`header`, `main`, `section`, `footer`, etc.)
* Structural organization
* Nesting and hierarchy of elements
* Clean, readable HTML for future styling

---

## Figma Resources

The designer file for this project is provided on Figma.

You should:

* Create a Figma account.
* Open the design file.
* **Duplicate to Drafts** to view all layers and spacing values.

### Fonts used in the design

If the fonts do not display correctly on your computer:

* Download **Source Sans Pro**
* Download **Spin Cycle OT**

Some spacing values may be floating-point numbers — feel free to round them.

---

## Project Structure Requirements

Below is a breakdown of what your HTML must contain based on the wireframe and designer file.

---

## 1. HTML Skeleton

Create the base HTML structure:

* `<!DOCTYPE html>`
* `<html>`
* `<head>` (metadata + title)
* `<body>`

---

## 2. Header Section

Inside the `<body>` tag, add a `<header>` that contains:

* A link element (`<a>`) containing the site logo image (`<img>`)
* A block containing **three navigation links** (`<a>`)

This represents the top navigation bar.

---

## 3. Banner Section

Under the header, add a `<main>` tag, then create a first `<section>` for the banner.

This section must contain **two main blocks**:

### Block 1 (Left/Primary Banner Content)

* A heading (`<h1>` or `<h2>` depending on hierarchy)
* A text element (`<p>`)
* A button (`<button>`)

### Block 2 (Right Banner Content)

* A heading (`<h2>` or `<h3>` depending on hierarchy)
* A grid of **four blocks**, each containing:

  * An image
  * A heading
  * A text

---

## 4. Quote Section

Under the banner (still inside `main`), create another `<section>` for the quote.

This section must include:

* A block containing:

  * An image
  * A nested block containing:

    * A `<blockquote>` element for the quote
    * A quote author
    * A supporting text paragraph

---

## 5. Videos Section

Add a new `<section>` containing:

* A heading
* A container holding **four video blocks**

Each video block contains:

* An image (thumbnail)
* A heading
* A text paragraph
* An author block containing:

  * An image
  * A heading (author name)
* A rating block containing:

  * A group of star images
  * A text label

---

## 6. Membership Section

This section mirrors the video layout structure.

Add a new `<section>` with:

* A heading
* A block containing **four membership item blocks**

Each item block must include:

* An image
* A heading
* A text paragraph
* A button

---

## 7. FAQ Section

Before the footer, add a final `<section>` for the FAQ.

Structure:

* A container holding **two rows**
* Each row contains **two FAQ items**
* Each FAQ item includes:

  * A heading
  * A text paragraph

---

## 8. Footer

Outside the main, add a `<footer>` element containing:

* A container for centering content
* A row with:

  * An image (footer logo)
  * A block containing:

    * Social media icon links (images inside `<a>` tags)
  * A text element

---

## Assets

All images (logos, thumbnails, icons) can be exported directly from the Figma file.

---

## Deliverables

For this project, you must submit:

### **1. README.md** (this file)

* Summary of project purpose
* Instructions
* Structure overview
* Notes regarding Figma & fonts

### **2. index.html**

* Fully structured HTML file following **all** requirements
* No CSS styles included yet
* Semantic and clean

---

## Author
IvyItumbi - Created for the HTML/CSS Advanced tasks. Ready to be used as the foundation for styling in the next project.
footer {
    background-color: #071629;
    color: white;
    text-align: center;
    padding: 40px 0;
    font-size: 16px;
}

footer p {
    margin: 0;
}

footer a {
    color: #ffffff;
    text-decoration: underline;
}

footer a:hover {
    opacity: 0.7;
}
