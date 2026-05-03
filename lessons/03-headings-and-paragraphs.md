# Lesson 03 — Headings and Paragraphs

## Making Your Content Stand Out

Headings and paragraphs are the building blocks of web content. They organize information so readers can quickly understand what a page is about.

---

## Headings: Creating Titles and Subtitles

HTML has **6 levels** of headings, from largest to smallest: `<h1>` to `<h6>`.

### Example:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Understanding Headings</title>
  </head>
  <body>
    <h1>This is a Heading 1 (Largest)</h1>
    <h2>This is a Heading 2</h2>
    <h3>This is a Heading 3</h3>
    <h4>This is a Heading 4</h4>
    <h5>This is a Heading 5</h5>
    <h6>This is a Heading 6 (Smallest)</h6>
  </body>
</html>
```

---

## When to Use Each Heading

| Heading | When to Use | Example |
|---------|------------|---------|
| `<h1>` | Main title of your page (use only ONE) | "Welcome to My Blog" |
| `<h2>` | Major section titles | "About Me", "My Projects" |
| `<h3>` | Subsection titles | "My Hobbies", "Education" |
| `<h4>` to `<h6>` | Smaller subsections | Rarely used on most pages |

**Important Rule:** Use only ONE `<h1>` per page. It tells search engines what your page is about.

---

## Paragraphs: Organizing Text

The `<p>` tag creates paragraphs. Use it for regular text content.

```html
<p>This is a paragraph. It can contain multiple sentences.</p>
<p>This is a second paragraph. Paragraphs are separated by space.</p>
```

**Always** remember to close your paragraphs with `</p>`!

---

## Combining Headings and Paragraphs

Here's a real example:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>My Portfolio</title>
  </head>
  <body>
    <h1>John's Portfolio</h1>
    
    <h2>About Me</h2>
    <p>Hi! I'm John, a web developer learning HTML.</p>
    <p>I enjoy building websites and learning new things.</p>
    
    <h2>My Skills</h2>
    <p>I'm currently learning HTML, which is the foundation of web development.</p>
    <p>I plan to learn CSS and JavaScript next.</p>
  </body>
</html>
```

---

## Tips for Good Structure

✅ **Do:**
- Start with ONE `<h1>` at the top
- Use headings to organize your content logically
- Use `<h2>` for main sections, `<h3>` for subsections
- Use multiple paragraphs for better readability

❌ **Don't:**
- Skip heading levels (don't go h1 → h3, use h2 in between)
- Use headings just to make text bigger
- Overuse headings (one per section is enough)

---

## Try It Yourself

Create a page about your favorite topic. Use:
- ONE `<h1>` for the title
- At least TWO `<h2>` headings for sections
- At least 3-4 paragraphs of text

Example outline:
```html
<h1>My Favorite Topic</h1>

<h2>What I Like About It</h2>
<p>First reason...</p>
<p>Second reason...</p>

<h2>Fun Facts</h2>
<p>Interesting information...</p>
```

Save and refresh in your browser. Does it look organized?

---

## Common Mistakes

❌ `<h1>heading</h1>` missing the closing tag  
✅ `<h1>heading</h1>` - always close your tags

❌ Using multiple `<h1>` tags on one page  
✅ One `<h1>` per page is the standard

❌ `<p>Paragraph` forgetting to close  
✅ `<p>Paragraph</p>` - always close paragraphs

---

## Summary

- Use `<h1>` through `<h6>` for different heading sizes
- Use only ONE `<h1>` per page (the main title)
- Use `<h2>` and `<h3>` for sections and subsections
- Use `<p>` tags for paragraphs of text
- Always remember to close every tag you open

---

[← Previous Lesson](02-your-first-webpage.md) | [Next Lesson →](04-links-and-images.md)
