# HTML & CSS Essentials

A structured, week-by-week curriculum covering fundamental HTML and CSS concepts through practical exercises and projects. The progression builds from basic markup to a complete multi-page website with responsive design and accessibility.

---

## Table of Contents

- [Repository Structure](#repository-structure)
- [Weekly Breakdown](#weekly-breakdown)
  - [Week 01 - HTML Basics](#week-01---html-basics)
  - [Week 02 - CSS Basics](#week-02---css-basics)
  - [Week 03 - One-Page Website](#week-03---one-page-website)
  - [Week 04 - Multi-Page Website](#week-04---multi-page-website)
  - [Week 05 - Responsive Web Design](#week-05---responsive-web-design)
  - [Week 06 - Forms](#week-06---forms)
- [Concepts Covered](#concepts-covered)
- [How to Use](#how-to-use)
- [License](#license)

---

## Repository Structure

```
HTML-CSS-Essentials/
├── week-01-HTML-basics/          # Core HTML elements
├── week-02-CSS-basics/           # CSS selectors and styling
├── week-03-one-page-website/     # Single-page layout project
├── week-04-multipage-website/    # Full multi-page site project
├── week-05-resposive-web-design/ # Media queries and responsive layout
└── week-06-forms/                # Form structure and styling
```

---

## Weekly Breakdown

### Week 01 - HTML Basics

Introduction to core HTML elements and document structure.

| File | Description |
|---|---|
| `Anchors.html` | Heading hierarchy (H1–H6) and anchor links to external resources |
| `Headings.html` | Demonstration of all six heading levels |
| `Images.html` | Embedding images using `<figure>` and `<figcaption>` for semantic markup |
| `Lists.html` | Unordered, ordered, and nested lists with hyperlinks |

**Concepts:** Document structure, semantic elements, anchor tags, image embedding, list types.

---

### Week 02 - CSS Basics

Applying CSS to HTML elements using classes, selectors, and style properties.

| File | Description |
|---|---|
| `First.html` / `First.css` | Basic HTML linked to a stylesheet; H1 styled with color and font size |
| `Sample.html` / `Styles.css` | Multiple CSS classes applied to paragraphs; `<span>` for inline styling |
| `Images.html` | Class-based image and figure styling |
| `Tables.html` | Table markup with `<thead>`, `<tbody>`, captions, borders, and padding |
| `Lists.css` | Custom list styling with backgrounds, borders, and spacing |

**Concepts:** CSS selectors, class-based styling, color (hex, RGB, named), typography, box model basics, table styling.

---

### Week 03 - One-Page Website

A themed single-page website for a fictional sports team ("Team X") with dark styling and animations.

| File | Description |
|---|---|
| `Structure.html` | Full semantic page with `<header>`, `<nav>`, `<main>`, `<section>`, `<table>`, `<footer>` |
| `Teamx.css` | Dark theme with animations, hover effects, gold accents, and responsive wrapper |

**Highlights:**
- Dark theme (`#121212` background) with gold (`#FFD700`) typography
- `@keyframes` background color animation
- Navigation hover effects with color transitions
- Image scale animation on hover (`transform: scale(1.1)`)
- ID-based anchor navigation with a back-to-top footer link
- Fixture table with styled headers and borders

**Concepts:** Semantic HTML layout, CSS animations (`@keyframes`), flexbox, pseudo-classes (`:hover`), `transform`, `transition`, ID-based navigation.

---

### Week 04 - Multi-Page Website

A comprehensive multi-page website for a university Staff-Student Liaison Committee. This is the most complete project in the repository, covering real-world concerns including accessibility, GDPR compliance, design documentation, and testing.

#### Pages

| File | Description |
|---|---|
| `Index.html` | Home page with navigation, articles, blockquote, and footer |
| `purpose.html` | Committee purpose and interactive quiz with radio buttons |
| `membership.html` | Table of committee member roles |
| `contact.html` | Contact form with email input, dropdown, and textarea |
| `meetings & papers.html` | List of meeting names and schedules |
| `Accessibility.html` | Accessibility statement covering visual, auditory, cognitive, and speech disabilities |
| `Design.html` | Design rationale, color scheme, site map, and mockup |
| `Testing.html` | CSS validation results and error corrections (before/after screenshots) |
| `Legal and security.html` | Copyright, GDPR compliance, and image licensing |
| `Data storage policy.html` | GDPR-compliant data handling and retention policy |

#### Stylesheets

| File | Description |
|---|---|
| `index.css` | Header, navigation, content area, push-quote, and footer styles |
| `Assignment1.css` | Full site styles: background images, forms, tables, hover effects, transitions, and a media query for mobile (`max-width: 500px`) |
| `Data storage policy.css` | Scoped styles for the policy page |

**Highlights:**
- Consistent navigation linking all pages
- Form with `mailto:` action, required fields, and dropdown targeting committee members
- Accessibility documented against disability categories with references to screen readers (JAWS, NVDA, VoiceOver)
- GDPR-compliant data storage policy
- Design documentation with site map image and wireframe mockup
- CSS validation testing with documented before/after fixes

**Concepts:** Multi-page site architecture, inter-page navigation, HTML forms (`<fieldset>`, `<label>`, `<select>`, `<textarea>`), tables, accessibility best practices, GDPR considerations, design documentation, CSS validation.

---

### Week 05 - Responsive Web Design

Demonstrates mobile-first responsive design using media queries and flexible units.

| File | Description |
|---|---|
| `start.html` | Semantic layout with `<header>`, `<nav>`, `<main>`, `<aside>`, `<footer>` and three content sections |
| `start.css` | Responsive styles with three media query breakpoints |

**Breakpoints:**

| Breakpoint | Changes |
|---|---|
| `min-width: 500px` | Larger font sizes; highlighted paragraph and heading color changes |
| `min-width: 600px` | Main switches from column to row layout (side-by-side content + aside) |
| `min-width: 1400px` | Wrapper constrained to 80% width for large screens |

**Concepts:** Media queries, mobile-first design, flexbox `flex-direction`, relative units (`rem`, `%`), `min-width` strategy.

---

### Week 06 - Forms

A clean, accessible form for collecting user likes and dislikes.

| File | Description |
|---|---|
| `Forms.html` | Form with text input, two `<fieldset>` groups of checkboxes, and a submit button |
| `Forms.css` | Centered card layout with blue fieldset borders, green submit button, and focus on visual clarity |

**Highlights:**
- `<fieldset>` and `<legend>` used for semantic grouping of related inputs
- Required name field with placeholder text
- Separate fieldsets for "Likes" (Food, Sports, Movies) and "Dislikes" (Bugs, Rain, Traffic)
- Styled submit button with hover state

**Concepts:** Form elements (`<input>`, `<fieldset>`, `<legend>`, `<label>`, `<button>`), accessibility in forms, CSS card layout, `box-shadow`, `border-radius`.

---

## Concepts Covered

| Category | Topics |
|---|---|
| **HTML Structure** | Document structure, semantic elements (`header`, `nav`, `main`, `section`, `article`, `footer`, `figure`) |
| **HTML Elements** | Headings, paragraphs, lists, links, images, tables, forms |
| **CSS Selectors** | Element, class (`.`), ID (`#`), pseudo-class (`:hover`) |
| **CSS Properties** | Color, typography, box model, borders, backgrounds, shadows |
| **Layout** | Flexbox, float, max-width containers, wrappers |
| **Responsive Design** | Media queries, relative units (`rem`, `%`, `em`), mobile-first strategy |
| **Animations** | `@keyframes`, `transition`, `transform` (scale, hover effects) |
| **Forms** | Input types, `fieldset`/`legend`, labels, dropdowns, validation attributes |
| **Accessibility** | Alt text, semantic HTML, heading hierarchy, form labels, color contrast |
| **Best Practices** | CSS validation, GDPR compliance, design documentation, testing workflow |

---

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/paulezennolim/HTML-CSS-Essentials.git
   cd HTML-CSS-Essentials
   ```

2. Navigate to the week you want to explore:
   ```bash
   cd week-01-HTML-basics
   ```

3. Open any `.html` file directly in your browser:
   ```bash
   open Anchors.html        # macOS
   start Anchors.html       # Windows
   xdg-open Anchors.html    # Linux
   ```

No build tools, dependencies, or server required — all files are plain HTML and CSS.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
