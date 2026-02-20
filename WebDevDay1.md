# Web Development Workshop

# What's this document for?

This document contains activities you can complete either during the workshop or at home.

You have two options:

1. Create a new sandbox by going to https://codesandbox.io/templates and selecting the **HTML and CSS** template.

OR

2. Delete the content inside the `<body>` tag of the `index.html` file and complete the exercises there.  
   (If you choose to build your project in the same file, you will need to clear the `<body>` again before starting your project.)

## Why Learn Web Dev

## AI and Prompt Engineering

### Will AI Replace Human Engineers?

While AI has transformed the way we develop and create software, it is not a replacement for human engineers. Instead, it is a collaborative tool that helps make development faster and more efficient.

Engineers still need a strong understanding of systems, design principles, and what clean, working code looks like in order to use AI tools effectively. Without that foundation, it becomes very difficult to build reliable software at scale.

This workshop is just the first step in understanding how one area of coding works.

Think of it this way: a calculator can solve many problems, but you still need an understanding of math to use it properly. Now imagine that the calculator occasionally gives you the wrong answer, and it is your responsibility to recognize when that happens. That is closer to how AI is used in the field.

Engineers are still writing code. They are simply using AI tools to do it more efficiently.

---

## Project Setup

### Code Sandbox

We will be using Code Sandbox to build out our projects.  
This is a browser-based IDE (Integrated Development Environment). This will allow you to code regardless of your computer system.

---

# Activities

## 1. Hello HTML

- An HTML tag starts with the name of the tag inside angle brackets, like `<div>`, and ends with a closing tag that includes a forward slash, like `</div>`. Inside a tag, you can place text or other HTML tags.

- In the `index.html` file, inside the `<body>` tag, create a `<div>` element with the words **"Hello World"** inside it. You should see this appear on the right side of the screen.

<details>
<summary><strong>Solution</strong></summary>

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>HTML + CSS</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <div>Hello World</div>
  </body>
</html>
```

</details>

---

## 2. Text

- While we _can_ technically build most of a page using `<div>` tags, that is not modern best practice. Instead, we use **semantic HTML**, meaning we choose specific tags for specific purposes. This helps the browser understand our structure and also makes the page more accessible for screen readers.

- Text content is handled with:
  - Heading tags `<h1>` through `<h6>` (headings get smaller as the number increases)
  - `<p>` tags for paragraphs

- Start by deleting the `<div>` tag.

- Use an `<h1>` tag for the name of your website.

- Use an `<h2>` tag for a subheading.

- Use a `<p>` tag to explain the purpose of your website.

- In my example, I am creating a startup landing page for my cat.

> **Note:** I am only focusing on the important tags in my solution below. Do not delete the rest of your HTML file just because it is not shown here.

<details>
<summary><strong>Solution</strong></summary>

```html
<body>
  <h1>Peer Reviewed Purrs</h1>
  <h2>A Startup by Rose the Cat</h2>
  <p>
    Hi, welcome to my website! I'm Rose. This is my startup, Peer Reviewed
    Purrs, the one and only app where pets can review their owners' behavior and
    daily decisions.
  </p>
</body>
```

</details>

---

## 3. Lists

- Use the `<ol>` tag to create a list of your favorite books, movies, food, or video games.
- Use the `<ul>` tag to list 3 facts about yourself.
- Note: you will need `<li>` tags nested inside both lists.

<details>
<summary><strong>Solution</strong></summary>

```html
<body>
  <h3>My Favorite Tech Books!</h3>
  <ol>
    <li>You Don't Know JS Yet</li>
    <li>Eloquent JavaScript</li>
    <li>Build an LLM from Scratch</li>
    <li>StatQuest Illustrated Guide to Neural Networks and AI</li>
  </ol>

  <h3>My Hobbies</h3>
  <ul>
    <li>Dungeons and Dragons</li>
    <li>Board games</li>
    <li>Hiking / Backpacking</li>
  </ul>
</body>
```

</details>
.

---

## 4. Layout

- Let's organize our web page.
- Use the `<nav>` tag to create a navigation section. Inside it, nest a `<ul>` with menu items like "Home", "About", and "Contact".
- Nest all of your main content inside a `<main>` tag.
- Add a `<footer>` to the end of your page.
- Put your ordered list inside an `<aside>` tag and your text content inside a `<section>` tag.

<details>
<summary><strong>Solution</strong></summary>

```html
<body>
  <nav>
    <ul>
      <li>Home</li>
      <li>About</li>
      <li>Contact</li>
    </ul>
  </nav>

  <main>
    <aside>
      <h3>My Favorite Tech Books!</h3>
      <ol>
        <li>You Don't Know JS Yet</li>
        <li>Eloquent JavaScript</li>
        <li>Build an LLM from Scratch</li>
        <li>StatQuest Illustrated Guide to Neural Networks and AI</li>
      </ol>
    </aside>

    <section>
      <h3>My Hobbies</h3>
      <ul>
        <li>Dungeons and Dragons</li>
        <li>Board games</li>
        <li>Hiking / Backpacking</li>
      </ul>
    </section>
  </main>

  <footer>Ix © 2026 WebDev Workshop</footer>
</body>
```

</details>

---

## 5. Project

### Create Your Own HTML Page

Now it's your turn to build something of your own.

Create an HTML page using the tags and structure you've learned so far. The theme can be anything you want, but keep it simple and focus on practicing good structure.

Try to include:

- Headings
- Paragraph text
- Lists
- Navigation
- A main content section
- A footer

Examples:

- Profile page
- Restaurant website
- Blog page
- Hobby page
- Startup landing page
- Photo gallery

---

## AI Transparency Note

AI was used to assist with grammar and formatting in this document. All instructional content, structure, and technical material were created by the instructor.
