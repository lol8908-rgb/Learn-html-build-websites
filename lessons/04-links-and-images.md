# Lesson 04 — Links and Images

## Connecting Your Web Pages

Links and images make websites interactive and visual. In this lesson, you'll learn to create clickable links and display images on your pages.

---

## Creating Links

The `<a>` tag creates clickable links. The `href` attribute tells the browser where to go.

### Basic Link Syntax:

```html
<a href="https://www.example.com">Click here</a>
```

This displays "Click here" as a blue underlined link.

---

## Types of Links

### 1. External Links (To Other Websites)

```html
<p>Visit <a href="https://www.google.com">Google</a> for searching.</p>
<p><a href="https://www.wikipedia.org">Wikipedia</a> has lots of information.</p>
```

**Important:** Always include `https://` or `http://` for external links!

### 2. Internal Links (To Other Pages on Your Site)

```html
<a href="index.html">Home</a>
<a href="about.html">About</a>
<a href="lessons/lesson1.html">Lesson 1</a>
```

For files in the same folder, no `https://` needed.

### 3. Links Within the Same Page

```html
<!-- Jump to section -->
<a href="#contact">Go to Contact Section</a>

<!-- The target section -->
<h2 id="contact">Contact Me</h2>
```

---

## Adding Images

The `<img>` tag displays images. It's different from other tags — it doesn't have a closing tag!

### Basic Image Syntax:

```html
<img src="image.jpg" alt="Description of image">
```

- `src` = the file path or web address of the image
- `alt` = text that displays if the image can't load (also helps visitors with screen readers)

---

## Image Examples

### Image from Your Computer:

```html
<img src="my-photo.jpg" alt="A photo of my cat">
```

Make sure the image file is in the same folder as your HTML file.

### Image from the Internet:

```html
<img src="https://example.com/image.jpg" alt="A landscape photo">
```

### Controlling Image Size:

```html
<img src="photo.jpg" alt="Vacation photo" width="300" height="200">
```

**Tip:** Use width and height in pixels to control size.

---

## A Complete Example Page

```html
<!DOCTYPE html>
<html>
  <head>
    <title>My Travel Blog</title>
  </head>
  <body>
    <h1>My Summer Vacation</h1>
    
    <p>This summer, I visited the beach! Here are my photos:</p>
    
    <img src="beach-sunset.jpg" alt="Beautiful sunset at the beach">
    
    <h2>About My Trip</h2>
    <p>I had an amazing time! I even saw dolphins.</p>
    <p>For more travel tips, visit <a href="https://www.travelblog.com">Travel Blog</a>.</p>
    
    <h2>Photo Gallery</h2>
    <img src="beach-photo1.jpg" alt="Me at the beach">
    <img src="beach-photo2.jpg" alt="Beach sunset">
    <img src="beach-photo3.jpg" alt="Palm trees">
    
  </body>
</html>
```

---

## Best Practices for Links

✅ **Do:**
- Use clear, descriptive link text
- Include `https://` for external links
- Use `alt` text for all images

❌ **Don't:**
- Write "Click here" (be specific like "Visit Google")
- Use web addresses as link text
- Forget `alt` text on images

### Good vs Bad Examples:

❌ Bad: `<a href="https://www.recipe.com">click</a>`  
✅ Good: `<a href="https://www.recipe.com">Find chocolate cake recipes</a>`

---

## Try It Yourself

### Challenge 1: Add Links
Create a page with links to:
1. Your favorite website
2. Another page on your site (create a second HTML file)
3. A specific section on your page (using the `id` attribute)

### Challenge 2: Add Images
1. Find a photo on your computer
2. Save it in the same folder as your HTML file
3. Add it to your page with `<img>` tag
4. Remember to add `alt` text!

**Steps:**
1. Edit your HTML file
2. Add `<a>` tags for links
3. Add `<img>` tags for images
4. Save and refresh your browser

---

## Common Mistakes

❌ `<a href="google.com">Link</a>` (missing https://)  
✅ `<a href="https://google.com">Link</a>`

❌ `<img src="photo.jpg">` (missing alt text)  
✅ `<img src="photo.jpg" alt="My photo">`

❌ `<img src="photo.jpg"></img>` (img doesn't have closing tag)  
✅ `<img src="photo.jpg" alt="My photo">`

---

## Summary

- Use `<a>` tag with `href` attribute to create links
- Include `https://` for external links
- Use descriptive text inside link tags
- Use `<img>` tag to display images
- Always add `alt` text to images
- Images are on one line with no closing tag
- Use `width` and `height` to control image size

---

[← Previous Lesson](03-headings-and-paragraphs.md) | [Next Lesson →](05-lists-and-tables.md)
