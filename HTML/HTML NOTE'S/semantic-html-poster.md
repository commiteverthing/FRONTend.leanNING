# 🧠 Semantic HTML Poster (Easy English)

---

## 🔷 STRUCTURE (PAGE LAYOUT)

- `<header>`   → Top part of page (logo, title)
- `<nav>`      → Menu with links (Home, About, etc.)
- `<main>`     → Main content of the page (only one)
- `<section>`  → A group of related content (like a chapter)
- `<article>`  → A complete piece (blog post, news, card)
- `<aside>`    → Side content (ads, tips, sidebar)
- `<footer>`   → Bottom part (copyright, links)

---

## 🔷 TEXT CONTENT

- `<h1>` - `<h6>` → Headings (h1 biggest, h6 smallest)
- `<p>`           → Paragraph (normal text)
- `<blockquote>`  → Big quote (from someone)
- `<figure>`      → Image or media container
- `<figcaption>`  → Text below image (caption)

---

## 🔷 INLINE (SMALL TEXT MEANING)

- `<a>`        → Link (click to go somewhere)
- `<strong>`   → Important text (bold meaning)
- `<em>`       → Emphasized text (stress/feeling)
- `<mark>`     → Highlighted text
- `<abbr>`     → Short form (like HTML = HyperText Markup Language)
- `<time>`     → Date or time
- `<code>`     → Code text

---

## 🔷 LISTS

- `<ul>` → Bullet list
- `<ol>` → Numbered list
- `<li>` → List item

---

## 🔷 FORMS (USER INPUT)

- `<form>`     → Form container
- `<label>`    → Name of input field
- `<input>`    → Input box
- `<textarea>` → Big text box
- `<button>`   → Click button

---

## ❌ NOT SEMANTIC (USE LESS)

- `<div>`   → Just a box (no meaning)
- `<span>`  → Small inline box (no meaning)

---

## ⚡ SIMPLE RULES

- Use `<section>` → when content is grouped  
- Use `<article>` → when content is complete by itself  
- Use `<main>` → only once  
- Avoid too many `<div>`

---


Semantic Elements in HTML
Below is a list of some of the semantic elements in HTML.

Tag	Description
<article>	Defines independent, self-contained content
<aside>	Defines content aside from the page content
<details>	Defines additional details that the user can view or hide
<figcaption>	Defines a caption for a <figure> element
<figure>	Specifies self-contained content, like illustrations, diagrams, photos, code listings, etc.
<footer>	Defines a footer for a document or section
<header>	Specifies a header for a document or section
<main>	Specifies the main content of a document
<mark>	Defines marked/highlighted text
<nav>	Defines navigation links
<section>	Defines a section in a document
<summary>	Defines a visible heading for a <details> element
<time>	Defines a date/time




## 🧾 BASIC PAGE STRUCTURE

```html
<header></header>
<nav></nav>
<main>
  <section>
    <article></article>
  </section>
</main>
<aside></aside>
<footer></footer>



