# Lecture 02 – Semantic HTML & Structure

## 1. What I implemented this lecture
- Used semantic structure with `<header>`, `<main>`, `<section>`, `<article>`, and `<footer>`
- Created a Portfolio / Works section with images, captions, links, and an embedded video
- Added accessibility basics: skip link, correct heading hierarchy, and alt text for images

## 2. Semantic decisions I made (REQUIRED)

### Decision 1
- Element(s) used: `<header>`
- Where in the page: At the top of the page
- Why this element is semantically correct: It contains the main introduction (name and personal information).

### Decision 2
- Element(s) used: `<main id="main">`
- Where in the page: Wraps the primary page content
- Why this element is semantically correct: It represents the main content and is the target for the skip link.

### Decision 3
- Element(s) used: `<figure>` and `<figcaption>`
- Where in the page: Around profile image, project images, and embedded video
- Why this element is semantically correct: It groups media with a caption, giving clear meaning and context.

---

## 3. Accessibility considerations
- Skip link (`<a href="#main">Skip to content</a>`) for keyboard users
- Correct heading hierarchy (h1 → h2 → h3 → h4) for screen reader navigation
- Alt text on all images for non-visual users
- Semantic landmarks to improve navigation for assistive technologies

---

## 4. What I learned
- How to structure a portfolio page using semantic HTML instead of div-only layouts

## 5. What I still need to improve
- Writing more detailed project descriptions and more specific alt text

## 6. Notes about AI usage (if any)
- Tool used: ChatGPT
- What I accepted as-is: Basic semantic layout structure
- What I modified manually: Personal details, GitHub/LinkedIn links, and images
