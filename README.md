[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/d5k3FCrw)
[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=20862240)
# Tastes of Africa – Website Project

## Introduction
Welcome to the **Tastes of Africa** project!  
In this assignment, you’ll build and style a multi-page website celebrating Africa’s rich and diverse culinary traditions.  
You’ll use **HTML** for structure and **CSS** for styling, creating a website that is both **visually appealing** and **user-friendly**.

---

## Learning Objectives
- Understand the fundamentals of **HTML** and **CSS**.
- Apply **semantic HTML5 tags** to structure content.
- Use various HTML elements (text, images, lists, tables, videos, forms, maps).
- Apply **CSS selectors, properties, and values** for styling.
- Incorporate **Google Fonts** for custom typography.
- Use **color palettes, spacing, and layouts** effectively.
- Ensure **basic responsiveness** across screen sizes.
- Follow **best practices** for code quality and organization.

---

## Project Requirements

### 1. Website Structure (HTML)

Your website should include the following **pages**:

#### Home Page
- Hero section: large background image, welcome text, and a YouTube video.
- Featured dishes: 3–4 African dishes with `<figure>` + `<figcaption>`.
- Explore by region: links to 2–3 region pages.
- Latest food trends: 2–3 news updates using `<article>`.
- Use `<mark>` to highlight ingredients or influences.

#### Recipes Page
- 3–5 African dishes (e.g., Jollof Rice, Tagine, Injera, Bunny Chow, Isombe).
- Include:
  - Dish name, image, and description.
  - Expandable cooking steps (`<details>` + `<summary>`).
  - Ingredients list (`<ul>` or `<ol>`).
  - YouTube tutorial embed.
  - (Optional) nutritional facts table.
  - Map (`<iframe>`) showing country of origin.

#### Culinary Regions Page
- 2–3 regions with:
  - Food culture and staples.
  - Signature dishes with links.
  - YouTube video embed.
  - Highlight spices/techniques with `<mark>`.

#### About Us Page
- Website mission and history of African cuisine.
- Embedded Google Map of a cultural food landmark or restaurant.

#### Contact Page
- A form with:
  - Name (`<input type="text">`)
  - Email (`<input type="email">`)
  - Country (`<select>` + `<datalist>`)
  - Message (`<textarea>`)
  - Submit button (`<button>`)
- All fields must have `<label>` for accessibility.

#### Optional Enhancement
- Newsletter signup form in the footer (email + submit button).

---

### 2. Website Styling (CSS)

- Create a `styles.css` file and link it to all pages.

#### General Styling
- Use a **color palette** inspired by African spices/landscapes.
- Apply consistent **margin/padding** for layout.
- Set **base font size + line height** for readability.
- Import **Google Fonts**:
  - Bold/expressive font for **headings**.
  - Readable font for **body text**.

#### Navigation
- Style `<nav>` for clarity and usability.
- Add hover effects (color change, underline).

#### Home Page
- Hero section with background image + styled overlay text.
- Featured dishes displayed as **cards** with shadows + rounded corners.
- Clean layout for food trends.

#### Recipes Page
- Recipe cards styled consistently.
- Ingredients lists, instructions, and tables formatted clearly.
- Embedded videos sized properly.

#### Culinary Regions Page
- Typography and spacing for readability.
- Custom style for `<mark>` highlights.

#### About Us Page
- Styled mission statement.
- Map integrated smoothly.

#### Contact Page
- Styled form fields (input, select, textarea, button).
- Add **focus states** (e.g., border color change).

#### Responsiveness
- Use relative units (`%`, `rem`, `vw`, `vh`) where possible.
- Ensure layout adapts to small screens.

---

## Submission Instructions
1. Commit and push your updated code to GitHub Classroom, including:
    - styles.css
    - HTML files with linked CSS.
---
