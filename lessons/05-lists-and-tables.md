# Lesson 05 — Lists and Tables

## Organizing Information

Lists and tables help organize information in a clear way. Whether you're listing items or comparing data, these tools make content easier to read.

---

## Unordered Lists (Bullet Points)

Unordered lists show items with bullet points. Use `<ul>` (unordered list) and `<li>` (list item).

### Syntax:

```html
<ul>
  <li>First item</li>
  <li>Second item</li>
  <li>Third item</li>
</ul>
```

### Example:

```html
<h2>Things I Like</h2>
<ul>
  <li>Pizza</li>
  <li>Video games</li>
  <li>Reading books</li>
  <li>Playing soccer</li>
</ul>
```

---

## Ordered Lists (Numbered)

Ordered lists show items with numbers. Use `<ol>` (ordered list) and `<li>` (list item).

### Syntax:

```html
<ol>
  <li>First item</li>
  <li>Second item</li>
  <li>Third item</li>
</ol>
```

### Example:

```html
<h2>Steps to Bake Cookies</h2>
<ol>
  <li>Preheat oven to 350°F</li>
  <li>Mix butter and sugar</li>
  <li>Add eggs and vanilla</li>
  <li>Add flour and chocolate chips</li>
  <li>Place on baking sheet</li>
  <li>Bake for 12 minutes</li>
</ol>
```

---

## Nested Lists (Lists Inside Lists)

You can put lists inside lists for more detail:

```html
<h2>Web Development Topics</h2>
<ul>
  <li>Frontend
    <ul>
      <li>HTML</li>
      <li>CSS</li>
      <li>JavaScript</li>
    </ul>
  </li>
  <li>Backend
    <ul>
      <li>Python</li>
      <li>JavaScript (Node.js)</li>
      <li>Databases</li>
    </ul>
  </li>
</ul>
```

---

## Tables: Organizing Data

Tables display data in rows and columns. Use these tags:
- `<table>` = the entire table
- `<tr>` = table row
- `<td>` = table data (regular cell)
- `<th>` = table header (bold cell)

### Basic Table Syntax:

```html
<table>
  <tr>
    <th>Name</th>
    <th>Age</th>
    <th>City</th>
  </tr>
  <tr>
    <td>Alice</td>
    <td>25</td>
    <td>New York</td>
  </tr>
  <tr>
    <td>Bob</td>
    <td>30</td>
    <td>Los Angeles</td>
  </tr>
</table>
```

---

## Table Example

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Class Grades</title>
  </head>
  <body>
    <h1>Student Grades</h1>
    
    <table>
      <tr>
        <th>Student Name</th>
        <th>Math</th>
        <th>Science</th>
        <th>English</th>
      </tr>
      <tr>
        <td>John</td>
        <td>A</td>
        <td>B+</td>
        <td>A</td>
      </tr>
      <tr>
        <td>Maria</td>
        <td>A+</td>
        <td>A</td>
        <td>B+</td>
      </tr>
      <tr>
        <td>David</td>
        <td>B</td>
        <td>B</td>
        <td>A</td>
      </tr>
    </table>
  </body>
</html>
```

---

## When to Use What

| Use Case | Element | Example |
|----------|---------|---------|
| Simple checklist | `<ul>` | To-do items, ingredients |
| Instructions | `<ol>` | Steps in a recipe |
| Data comparison | `<table>` | Prices, scores, schedules |
| Hierarchical info | Nested lists | Categories and subcategories |

---

## List vs Table Quick Comparison

```html
<!-- Use list for simple items -->
<ul>
  <li>Apples</li>
  <li>Bananas</li>
  <li>Oranges</li>
</ul>

<!-- Use table for comparing multiple properties -->
<table>
  <tr>
    <th>Fruit</th>
    <th>Color</th>
    <th>Price</th>
  </tr>
  <tr>
    <td>Apple</td>
    <td>Red</td>
    <td>$1.50</td>
  </tr>
</table>
```

---

## Try It Yourself

### Challenge 1: Create a List
Make a page with:
1. An unordered list of your favorite foods
2. An ordered list of steps for something you do daily
3. A nested list for a topic you like

### Challenge 2: Create a Table
Create a table comparing 3 things:
- Products and prices
- Movies and their ratings
- Countries and their capitals
- Anything else fun!

### Challenge 3: Combine Everything
Create a page with:
- At least one heading
- Both lists and a table
- Description text between items

---

## Tips for Great Lists and Tables

✅ **Do:**
- Use `<ul>` for unordered lists
- Use `<ol>` for ordered lists
- Use `<th>` for table headers, `<td>` for data
- Keep tables simple and clear

❌ **Don't:**
- Mix lists for no reason (choose ul or ol)
- Create tables for simple lists
- Forget to close all `<tr>`, `<td>`, and `<th>` tags

---

## Common Mistakes

❌ `<li>Item</li>` (without `<ul>` or `<ol>`)  
✅ `<ul><li>Item</li></ul>` (always wrap in ul/ol)

❌ `<table><tr><td>Data</td></tr></table>` (forgot headers)  
✅ `<table><tr><th>Header</th></tr></table>` (use th for headers)

❌ `<ol><li>Item` (missing closing tag)  
✅ `<ol><li>Item</li></ol>` (always close tags)

---

## Summary

- Use `<ul>` with `<li>` for bullet lists
- Use `<ol>` with `<li>` for numbered lists
- Nest lists by putting a list inside `<li>`
- Use `<table>` for organized data in rows and columns
- Use `<th>` for table headers and `<td>` for data cells
- Always close all tags: `</li>`, `</tr>`, `</td>`, etc.

---

[← Previous Lesson](04-links-and-images.md) | [Next Lesson →](06-forms.md)
