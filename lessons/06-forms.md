# Lesson 06 — Forms

## Getting Information from Users

Forms let visitors interact with your website by typing text, selecting options, and clicking buttons. Perfect for contact forms, surveys, signups, and more.

---

## What is a Form?

A form collects information from users. It has:
- Input fields (text boxes, checkboxes, radio buttons)
- A submit button
- A place to send the information

---

## The Form Tag

Every form starts with `<form>` and ends with `</form>`.

```html
<form>
  <!-- Form elements go here -->
</form>
```

---

## Text Input Fields

The `<input>` tag creates fields for typing.

### Single Line Text Input:

```html
<label for="name">Your Name:</label>
<input type="text" id="name" name="name">
```

- `label` = descriptive text for the field
- `for` = connects label to input (must match `id`)
- `type="text"` = creates a text box
- `name` = the field's identifier

### Password Input (Text is Hidden):

```html
<label for="password">Password:</label>
<input type="password" id="password" name="password">
```

### Email Input (Validates email format):

```html
<label for="email">Email:</label>
<input type="email" id="email" name="email">
```

### Number Input:

```html
<label for="age">Age:</label>
<input type="number" id="age" name="age">
```

---

## Text Area (Multi-Line Input)

For longer text like comments:

```html
<label for="message">Your Message:</label>
<textarea id="message" name="message" rows="5" cols="40"></textarea>
```

- `rows` = number of lines
- `cols` = character width

---

## Checkboxes (Multiple Selections)

Let users select one or more options:

```html
<p>What are your interests?</p>
<input type="checkbox" id="sports" name="interests" value="sports">
<label for="sports">Sports</label>

<input type="checkbox" id="music" name="interests" value="music">
<label for="music">Music</label>

<input type="checkbox" id="gaming" name="interests" value="gaming">
<label for="gaming">Gaming</label>
```

---

## Radio Buttons (Single Selection)

Let users pick ONE option:

```html
<p>What is your favorite color?</p>

<input type="radio" id="red" name="color" value="red">
<label for="red">Red</label>

<input type="radio" id="blue" name="color" value="blue">
<label for="blue">Blue</label>

<input type="radio" id="green" name="color" value="green">
<label for="green">Green</label>
```

**Note:** All radio buttons in a group have the same `name`.

---

## Dropdown Menus (Select)

```html
<label for="country">Select your country:</label>
<select id="country" name="country">
  <option value="">-- Choose one --</option>
  <option value="usa">United States</option>
  <option value="uk">United Kingdom</option>
  <option value="canada">Canada</option>
  <option value="australia">Australia</option>
</select>
```

---

## Submit Button

Every form needs a button to send data:

```html
<button type="submit">Send</button>
```

Or:

```html
<input type="submit" value="Send">
```

---

## Complete Contact Form Example

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Contact Form</title>
  </head>
  <body>
    <h1>Contact Me</h1>
    
    <form>
      <label for="fullname">Full Name:</label>
      <input type="text" id="fullname" name="fullname" required>
      <br><br>
      
      <label for="email">Email:</label>
      <input type="email" id="email" name="email" required>
      <br><br>
      
      <label for="subject">Subject:</label>
      <input type="text" id="subject" name="subject">
      <br><br>
      
      <label for="message">Message:</label><br>
      <textarea id="message" name="message" rows="5" cols="40"></textarea>
      <br><br>
      
      <label for="priority">Priority:</label>
      <select id="priority" name="priority">
        <option value="low">Low</option>
        <option value="medium">Medium</option>
        <option value="high">High</option>
      </select>
      <br><br>
      
      <input type="checkbox" id="subscribe" name="subscribe">
      <label for="subscribe">Subscribe to my newsletter</label>
      <br><br>
      
      <button type="submit">Send Message</button>
    </form>
  </body>
</html>
```

---

## Form Elements Reference

| Element | Purpose | Example |
|---------|---------|---------|
| `<form>` | Creates a form | `<form>...</form>` |
| `<label>` | Describes an input | `<label for="name">Name:</label>` |
| `<input type="text">` | Text box | `<input type="text" name="username">` |
| `<input type="password">` | Hidden text | `<input type="password" name="pwd">` |
| `<input type="email">` | Email validation | `<input type="email" name="email">` |
| `<input type="number">` | Number only | `<input type="number" name="age">` |
| `<textarea>` | Multi-line text | `<textarea rows="5"></textarea>` |
| `<input type="checkbox">` | Multiple select | `<input type="checkbox">` |
| `<input type="radio">` | Single select | `<input type="radio">` |
| `<select>` | Dropdown menu | `<select><option>...</option></select>` |
| `<button>` | Clickable button | `<button type="submit">Send</button>` |

---

## Try It Yourself

### Challenge 1: Simple Form
Create a form with:
1. Text input for name
2. Email input for email
3. Submit button

### Challenge 2: Survey Form
Create a survey with:
1. Text input for name
2. Radio buttons for age group
3. Checkboxes for interests
4. A submit button

### Challenge 3: Feedback Form
Create a feedback form that includes:
1. Name input
2. A dropdown for satisfaction level
3. Text area for comments
4. A submit button

---

## Important Notes

✅ **Do:**
- Always use `<label>` tags to describe inputs
- Use appropriate `type` for each input
- Group related radio buttons with the same `name`
- Use `required` attribute for mandatory fields

❌ **Don't:**
- Forget closing tags
- Use wrong `type` attributes
- Forget the `name` attribute on inputs
- Forget the submit button!

---

## Summary

- Forms collect information from users
- Use `<label>` to describe each field
- Use correct `type` attributes for different inputs
- Text input types: text, password, email, number
- Use `<textarea>` for multiple lines
- Checkboxes allow multiple selections
- Radio buttons allow one selection
- `<select>` creates dropdown menus
- Always include a submit `<button>`

**Note:** This lesson teaches HTML forms only. To actually send form data, you need backend technology like PHP, Node.js, or Python (covered in advanced courses!).

---

[← Previous Lesson](05-lists-and-tables.md) | [Next Lesson →](07-publishing-your-website.md)
