# 🌐 HTML Learning Project
Master the Building Blocks of the Web

---

## 🚀 What is HTML?
**HTML (HyperText Markup Language)** is the standard markup language for creating web pages. Think of it as the skeleton or foundation of every website you visit.

> **Key Points:**
> * **HyperText:** Text with links to other texts
> * **Markup:** A way to annotate text to show structure and meaning
> * **Language:** A set of rules and syntax for creating web content

### 🏗️ How HTML Works
HTML uses **tags** to define elements. Tags are keywords surrounded by angle brackets like `<tagname>`. Most tags come in pairs:

```html
<tagname>Content goes here</tagname>
<h1>This is a heading</h1>
<p>This is a paragraph</p>
```

---

## 📋 Basic HTML Structure
Every HTML document follows this basic structure:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Page Title</title>
</head>
<body>
    <h1>Welcome to My Website</h1>
    <p>This is my first paragraph.</p>
</body>
</html>
```

> ### Structure Breakdown:
> * **`<!DOCTYPE html>`** - Tells the browser this is HTML5
> * **`<html>`** - Root element of the page
> * **`<head>`** - Contains metadata (not visible on page)
> * **`<body>`** - Contains visible content

---

## 🏷️ Essential HTML Tags
| Tag                    | Purpose                        | Example                                   |
| :--------------------- | :----------------------------- | :---------------------------------------- |
| `<h1>` - `<h6>`        | Headings (largest to smallest) | `<h1>Main Title</h1>`                     |
| `<p>`                  | Paragraphs                     | `<p>This is text</p>`                     |
| `<a>`                  | Links                          | `<a href="url">Link text</a>`             |
| `<img>`                | Images                         | `<img src="image.jpg" alt="Description">` |
| `<div>`                | Container/section              | `<div>Content here</div>`                 |
| `<ul>`, `<ol>`, `<li>` | Lists                          | `<ul><li>Item</li></ul>`                  |

### 🎯 Live Examples:
This is an H1 heading
## This is an H2 heading
### This is an H3 heading
This is a paragraph with **bold text** and *italic text*.

Here's a [sample link](#).

#### Unordered List:
* First item
* Second item
* Third item

#### Ordered List:
1.  Step one
2.  Step two
3.  Step three

---

## 📝 HTML Forms
Forms allow users to input data.

```html
<form>
    <label for="name">Name:</label>
    <input type="text" id="name" name="name">
    
    <label for="email">Email:</label>
    <input type="email" id="email" name="email">
    
    <label for="message">Message:</label>
    <textarea id="message" name="message"></textarea>
    
    <button type="submit">Submit</button>
</form>
```

#### Example Form:
* **Name:** [Text Input]
* **Email:** [Email Input]
* **Subject:** [Dropdown: Question, Feedback, Support]
* **Message:** [Text Area]
* [Submit Form Button]

---

## 🎨 HTML Attributes
Attributes provide additional information about HTML elements:

```html
<!-- Common attributes -->
<img src="photo.jpg" alt="A beautiful sunset" width="300" height="200">
<a href="https://example.com" target="_blank" title="Visit Example">Click here</a>
<div class="container" id="main-content" style="color: blue;">Content</div>
```

> ### Important Attributes:
> * **id** - Unique identifier for an element
> * **class** - Groups elements for styling
> * **src** - Source file for images, videos, etc.
> * **href** - URL for links
> * **alt** - Alternative text for images
> * **style** - Inline CSS styling

---

## 📊 Tables in HTML
Tables organize data in rows and columns:

```html
<table>
    <thead>
        <tr>
            <th>Name</th>
            <th>Age</th>
            <th>City</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>John</td>
            <td>25</td>
            <td>New York</td>
        </tr>
    </tbody>
</table>
```

#### Sample Table:
| Student       | Subject     | Grade | Status   |
| :------------ | :---------- | :---- | :------- |
| Alice Johnson | Mathematics | A+    | ✅ Passed |
| Bob Smith     | Physics     | B     | ✅ Passed |
| Carol Davis   | Chemistry   | A     | ✅ Passed |

---

## 💻 Practice Exercises
### Beginner Tasks:
1.  Create a basic HTML page with a title, heading, and paragraph
2.  Add an image with alt text
3.  Create a list of your favorite movies
4.  Build a simple table with your weekly schedule

### Intermediate Tasks:
1.  Create a contact form with different input types
2.  Build a navigation menu with links
3.  Design a simple blog post layout
4.  Create a photo gallery grid

---

## 🗂️ Project Structure
Here's how to organize your HTML project:

```
my-website/
│
├── index.html        (Main page)
├── about.html        (About page)
├── contact.html      (Contact page)
│
├── css/
│   └── styles.css    (CSS stylesheets)
│
├── js/
│   └── script.js     (JavaScript files)
│
└── images/
    ├── logo.png
    ├── hero-image.jpg
    └── gallery/
        ├── photo1.jpg
        └── photo2.jpg
```

---

## 🎯 Next Steps in Your Learning Journey
After mastering HTML, continue with:
* **CSS (Cascading Style Sheets)** - Style your HTML elements
* **JavaScript** - Add interactivity and dynamic behavior
* **Responsive Design** - Make websites work on all devices
* **Web Accessibility** - Make websites usable for everyone
* **Modern Frameworks** - React, Vue.js, or Angular

---

## 🔧 Development Tools
### Recommended Tools:
* **Text Editors:** VS Code, Sublime Text, Atom
* **Browsers:** Chrome DevTools, Firefox Developer Tools
* **Version Control:** Git and GitHub
* **Online Editors:** CodePen, JSFiddle, Repl.it

---

## 🎉 Congratulations!
You've completed the HTML Learning Project! You now understand the fundamentals of HTML and can create your own web pages. Keep practicing and building projects to strengthen your skills.