# landingwebpage
# Unbundl Assignment Reference Document

## Web Development Intern - Landing Page Development

### Objective

You need to create a **responsive landing page** using **HTML, CSS, and JavaScript** based on a Figma design. This means you will turn the design visuals into a live web page that works well on all screen sizes (desktop, tablet, mobile) and includes basic interactive features like a navigation menu toggle.

---

### Technologies to Use

- **HTML**: To create the structure and content of the page (headings, paragraphs, images, buttons, etc.)
- **CSS** (or SCSS compiled to CSS): To style the page, including colors, fonts, layout, spacing, and responsiveness.
- **JavaScript** (Vanilla JS only): To add interactive behaviors like menu toggles or scroll effects. **No frameworks or libraries** (like React, jQuery, etc.) allowed.

---

### Step-by-Step Guide

### 1. Access the Figma Design

- Go to the provided Figma link:
    
    https://www.figma.com/design/sm9DHhMwT84hL3vv3Rxkkg/Test-Assignment?node-id=4-1423&t=LfmzHBrjezvkcVoH-1
    
- Review all the page sections available.
- Choose **any 6 sections** you want to build for your landing page.

> Tip: Start with simpler sections like headers, hero sections, or feature lists. Later you can do more complex ones like testimonials or pricing.
> 

---

### 2. Plan Your Development

- Write down which 6 sections you will build.
- Analyze each section carefully:
    - What HTML elements are needed? (e.g., `<header>`, `<nav>`, `<section>`, `<div>`, `<img>`, `<button>`, `<p>`, `<h1>`, etc.)
    - How should it look on desktop and mobile?
    - What interactive features are there? (e.g., hamburger menu toggle, scroll animations)

---

### 3. Build the HTML Structure

- Start by creating an `index.html` file.
- Use **semantic HTML tags** where possible to give meaning to your structure:
    
    Examples:
    
    - `<header>` for the top navigation area
    - `<nav>` for the menu
    - `<main>` for main content sections
    - `<section>` for each content block
    - `<footer>` for the footer area
- Add proper attributes like `alt` for images for accessibility.
- Use meaningful class or id names for styling later.

---

### 4. Style with CSS

- Create a `style.css` file and link it in your HTML `<head>`.
- Use CSS to:
    - Match fonts, colors, sizes, and spacing as per the Figma design.
    - Use **flexbox** or **grid** to create responsive layouts.
    - Make the page responsive by using CSS media queries for different screen widths (mobile, tablet, desktop).
- Keep your CSS organized by grouping styles by sections.
- Use comments in your CSS to label different parts for clarity.

---

### 5. Add JavaScript for Interactivity

- Create a `script.js` file and link it at the end of the HTML body.
- Add basic interactivity like:
    - Toggle the navbar menu on mobile screens when hamburger icon is clicked.
    - Add scroll effects like sticky navigation or smooth scrolling if applicable.
- Use **vanilla JavaScript** only — no libraries or frameworks.

---

### 6. Test Responsiveness

- Test your page on different screen sizes:
    - Resize your browser window to see if the layout adapts properly.
    - Use Chrome Developer Tools (F12) > Toggle Device Toolbar to simulate mobile devices.
- Fix any alignment or overflow issues to ensure it looks good everywhere.

---

### 7. Deployment

- After finishing the development, deploy your landing page so it’s accessible online. You can use free platforms like:
    - **GitHub Pages** (host your static website from a GitHub repo)
    - **Netlify** (easy drag and drop or connect GitHub repo)
    - **Vercel** (also supports static sites easily)
- Deployment steps overview:
    - Create a GitHub repository and push your code to it.
    - Follow the platform’s instructions to publish the site.
    - Get the live URL of your deployed page.

---

### Deliverables

- **Live URL** of your deployed landing page.
- (Optional) Codebase repository link (GitHub or any other platform).
