# Lesson 02 — Your First Webpage

## Welcome Back!

Now that you know what HTML is, let's create your very first webpage from scratch.

Don't worry — it's easier than you think! You only need:
- A text editor (Notepad, VS Code, or any simple editor)
- Your computer
- A web browser

---

## Step-by-Step: Create Your First Page

### Step 1: Open Your Text Editor

Open Notepad on Windows or TextEdit on Mac. You can also use VS Code or any text editor.

### Step 2: Copy This Code

```html
<!DOCTYPE html>
<html>
  <head>
    <title>My Amazing First Page</title>
  </head>
  <body>
    <h1>Welcome to My Website!</h1>
    <p>Hello! This is my first webpage. I'm learning HTML!</p>
    <p>HTML is fun and not as hard as I thought.</p>
  </body>
</html>
```

### Step 3: Save Your File

1. Click **File** → **Save As**
2. Name it `index.html` (important: use `.html` at the end)
3. Choose where to save it (Desktop is fine)
4. Make sure it says "All Files" for file type, not "Text Files"

### Step 4: Open in Your Browser

1. Open your file explorer
2. Find your `index.html` file
3. Double-click it
4. Your webpage opens! 🎉

---

## What You Just Built

Your webpage now has:
- A **title** that appears in the browser tab
- A **heading** that says "Welcome to My Website!"
- Two **paragraphs** with text

Simple, but it's a real webpage!

---

## Understanding the Basic Structure

Every HTML page has this same basic structure:

```html
<!DOCTYPE html>
<html>
  <head>
    <!-- Information about the page goes here -->
  </head>
  <body>
    <!-- Everything visible goes here -->
  </body>
</html>
```

Think of it like a letter:
- `HTML` = The entire letter
- `HEAD` = The envelope (hidden info)
- `BODY` = The letter content (what people see)

---

## Try It Yourself

**Challenge:** Edit your HTML file to make:
1. Change the title to your own name
2. Change the heading to something about you
3. Add a new paragraph with your favorite hobby

To do this:
1. Right-click your `index.html` file
2. Click "Edit" or "Open with" → your text editor
3. Make your changes
4. Save the file (Ctrl+S or Cmd+S)
5. Refresh your browser to see the changes

**Hint:** Just change the text between the tags. Don't change the tags themselves!

---

## Common Mistakes to Avoid

❌ **Wrong:** Saving as `index.txt` instead of `index.html`  
✅ **Right:** Always use `.html` at the end

❌ **Wrong:** Forgetting closing tags like `</p>`  
✅ **Right:** Every opening tag needs a closing tag

❌ **Wrong:** Deleting important tags like `<html>` or `<body>`  
✅ **Right:** Keep the basic structure in place

---

## Summary

- HTML files must be saved with the `.html` extension
- Every page needs `<html>`, `<head>`, and `<body>` tags
- The `<title>` tag shows in the browser tab
- Everything visible goes inside the `<body>` tag
- You can edit and refresh to see changes instantly

---

[← Previous Lesson](01-what-is-html.md) | [Next Lesson →](03-headings-and-paragraphs.md)
