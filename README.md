# Garvit Jain | Personal Portfolio

A responsive personal portfolio website built with **HTML5, CSS3, and vanilla JavaScript**. It brings together my background, skills, education, experience, selected projects, and contact information in one place.

🌐 **Live website:** https://garvitjain6104.github.io/My-Portfolio-Website/

## Overview

This project is a lightweight, static portfolio designed to present my work as an Electronics and Communication Engineering undergraduate and web/software developer. It uses a dark navy visual theme with teal accents, responsive layouts, and small JavaScript interactions.

## Features

- **Responsive layout:** adapts the navigation, project cards, about section, and career timeline for smaller screens.
- **Interactive navigation:** mobile hamburger menu and scroll-aware navbar styling.
- **Animated hero text:** a JavaScript typewriter effect cycles through short phrases.
- **About and skills section:** introduces my background and current technical skills.
- **Education and career timeline:** uses the Intersection Observer API to reveal timeline items as they enter the viewport.
- **Project showcase:** displays selected projects with preview images, live demos, source-code links, and technology labels.
- **Contact form:** sends submissions through Formspree.
- **Social links:** provides links to my GitHub, LinkedIn, and Instagram profiles.

## Tech stack

| Technology / Service | Usage |
| --- | --- |
| HTML5 | Semantic page structure and content |
| CSS3 | Responsive styling, layout, transitions, and animations |
| Vanilla JavaScript | Navigation, typewriter effect, scroll behavior, and timeline observer |
| Intersection Observer API | Scroll-triggered timeline animations |
| Font Awesome | Interface and social icons |
| Google Fonts | Montserrat and Open Sans typography |
| Formspree | Contact form submission endpoint |
| GitHub Pages | Static website hosting |

## Project structure

```text
My-Portfolio-Website/
├── index.html          # Main page and portfolio content
├── style.css           # Layout, theme, responsive rules, and animations
├── script.js           # Client-side interactions
├── profile.jpeg        # Profile image
├── favicon.png         # Browser icon
├── project 1.png       # Project preview image
├── Project 2.png       # Project preview image
├── Project 3 img.png   # Project preview image
├── Project 4.png       # Project preview image
├── Project 5.png       # Project preview image
└── README.md           # Project documentation
```

## Run locally

No build tools or package installation are required.

1. Clone the repository:

   ```bash
   git clone https://github.com/garvitjain6104/My-Portfolio-Website.git
   ```

2. Open the project folder:

   ```bash
   cd My-Portfolio-Website
   ```

3. Open `index.html` in a browser, or use the VS Code Live Server extension.

## Deployment

The site is hosted using **GitHub Pages**.

To publish updates, push the changes to the repository's `main` branch and ensure GitHub Pages is configured to deploy from the intended branch and folder in the repository settings.

## Contact form

The contact form uses a Formspree endpoint configured in the form's `action` attribute in `index.html`. Form submissions are processed by Formspree; this repository does not contain a custom backend or database.

## Architecture notes

This is a **static, frontend-only website**:

- The browser loads the HTML, CSS, JavaScript, and local image assets.
- JavaScript runs in the browser and handles UI interactions.
- GitHub Pages serves the static files.
- Formspree handles contact form submissions.

There is currently no login, user authentication, authorization, application API, or database in this project.

## Future improvements

- Add accessible focus states and keyboard-friendly mobile navigation.
- Add success and error feedback after contact form submission.
- Improve image optimization and loading performance.
- Add social sharing metadata and a custom not-found page.
- Keep project descriptions, links, and experience details up to date.

## Author

**Garvit Jain**

- GitHub: [@garvitjain6104](https://github.com/garvitjain6104)
- LinkedIn: [garvittt99](https://www.linkedin.com/in/garvittt99/)
- Portfolio: [garvitjain6104.github.io/My-Portfolio-Website](https://garvitjain6104.github.io/My-Portfolio-Website/)

---

If you find an issue or have a suggestion, feel free to open a GitHub issue.
