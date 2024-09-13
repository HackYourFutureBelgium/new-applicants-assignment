# New Applicants Assignment: a Personal Portfolio

## Overview

Welcome to HYF-BE and to your first web development assignment! Your task is to build a **personal portfolio** using only **HTML** and **CSS**. This assignment will help you practice the essential skills needed for web development while showcasing your creativity.

### What is a Portfolio?

A **portfolio** is a collection of your work that represents your skills, achievements, and experiences. In the context of web development, a portfolio allows you to display your projects, introduce yourself to potential employers or clients, and demonstrate your proficiency in front-end technologies like HTML and CSS. A well-structured portfolio is key to building a strong online presence.

[Portfolio Example:](https://mileenka.github.io/Portfolio/index.html#about)

---

## Assignment Goals

- **Build a simple, responsive portfolio** using only HTML and CSS.
- Use **CodePen** to write, preview, and share your code.
- Practice using semantic HTML tags and properly naming CSS classes or IDs.
- Gain experience designing layouts, applying styles, and organizing content.

---

## Requirements

### 1. **HTML: Structure Your Portfolio**

Use **HTML** to create the basic structure of your portfolio. Be sure to follow these guidelines:

- **Correct Tags**: Make sure to use the appropriate HTML tags for different sections of the page.
  - Example tags: `<header>`, `<nav>`, `<section>`, `<footer>`, `<ul>`, `<img>`, `<a>`, `<div>`.
- **Semantic Tags**: Use semantic HTML tags to give meaning to your content. This improves accessibility and SEO.
  - Use semantic elements like `<header>`, `<main>`, `<article>`, `<section>`, and `<footer>` instead of generic `<div>` elements where applicable.

- **Content**: Include at least the following sections in your portfolio:
  - **Header**: Your name and navigation links.
  - **About Me**: A short introduction about who you are.
  - **Projects**: Showcase at least 2-3 projects with brief descriptions, images (if any), and links (optional).
  - **Contact Information**: A section with your contact details (e.g., email, phone number, or social media links).

### 2. **CSS: Style Your Portfolio**

- Use **CSS** to style your portfolio and make it visually appealing.
- **Naming Classes and IDs**: Make sure to properly name your classes and IDs for easy readability and maintenance.
  - Use meaningful names for classes and IDs that reflect their purpose, such as `.navbar`, `.portfolio-section`, `.about-me`, `.contact-info`, etc.

- **CSS Best Practices**:
  - Apply consistent styling for fonts, colors, and layouts.
  - Use `margin`, `padding`, and `box-sizing` to create proper spacing.
  - Add hover effects for buttons and links to enhance the user experience.
  - Responsive Design: Use media queries to ensure your portfolio looks good on different screen sizes (optional, but encouraged).

---

## Steps to Complete

1. **Set Up CodePen**:
    - [How to use CodePen](https://www.youtube.com/watch?v=vb9uYBtqmeM)
    - Go to [CodePen](https://codepen.io/).
    - Create a new pen for your portfolio project.
2. **Write HTML**:
    - Start by structuring the page using the correct HTML tags.
    - Add the content for each section (Header, About Me, Projects, Contact Information).
3. **Add CSS**:
    - Style your portfolio by adding custom CSS in the CSS panel.
    - Remember to name your classes and IDs meaningfully.
4. **Test Your Portfolio**:
    - Make sure everything works and looks good in the CodePen preview.
5. **Share Your Project**:
    - Once you're happy with the result, copy the **URL** of your CodePen project and share it.

---

## Example Code Structure

```html
<!-- HTML Structure Example -->
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>My Portfolio</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <!-- Header  -->
    <header>
        <h1>Your Name</h1>
        <nav>
            <ul>
                <li><a href="#about">About Me</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
 <!-- Main  -->
    <main>
        <section id="about">
            <h2>About Me</h2>
            <p>Write a brief introduction about yourself here.</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Your Name</p>
    </footer>
  </body>
</html>
```

```css
/* CSS Example */
body {
  font-family: Arial, sans-serif;
  line-height: 1.6;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

header {
  background-color: #333;
  color: white;
  padding: 1rem;
  text-align: center;
}

nav ul {
  list-style: none;
  padding: 0;
}

nav ul li {
  display: inline;
  margin: 0 15px;
}

nav ul li a {
  color: white;
  text-decoration: none;
}

section {
  padding: 2rem;
  margin: 2rem 0;
}

#about {
  background-color: #f4f4f4;
  border-radius: 5px;
  padding: 1.5rem;
}

footer {
  text-align: center;
  padding: 1rem;
  background-color: #333;
  color: white;
  position: relative;
  bottom: 0;
  width: 100%;
}
```

---

## Submission

Once you've completed your portfolio, share the **URL** of your CodePen project with us. Make sure that your portfolio is publicly accessible so it can be reviewed.

---

### Happy Coding! 🎉
