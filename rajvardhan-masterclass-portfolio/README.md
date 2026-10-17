# Personal Portfolio Website

A personal portfolio website built using HTML and CSS to showcase my background, technical skills, projects, education, and extracurricular experiences. This project is part of my Web Development Internship — Week 2: CSS Styling.

## 1. Project Overview

The portfolio presents my academic journey, technical interests, projects, and involvement in college and community activities through a clean, responsive, and professional interface.

The design uses a **Charcoal and Amber** color scheme, readable typography, structured layouts, interactive hover effects, and responsive styling for different screen sizes.

## 2. Objectives

- Understand and apply CSS styling concepts.
- Create and use an external stylesheet.
- Apply selectors, colors, typography, borders, margins, and padding.
- Use the CSS box model, Flexbox, and Grid.
- Add hover effects and visual transitions.
- Create a responsive layout using CSS media queries.
- Style portfolio sections, project cards, images, and form elements.
- Test the website and document the results.

## 3. Technologies Used

- **HTML5:** Website structure and content.
- **CSS3:** Styling, layouts, hover effects, transitions, and responsive design.
- **JavaScript:** Existing basic functionality for mobile navigation, scroll-reveal animations, the contact email draft, and the footer year.
- **Google Fonts:** DM Sans and Manrope typography.
- **Visual Studio Code:** Code editor.
- **Google Chrome:** Browser testing.

No CSS framework is required for this project.

## 4. Project Structure

```text
portfolio/
├── index.html
├── style.css
├── README.md
├── images/
│   ├── profile.jpg
│   ├── project-1.jpg
│   └── project-2.jpg
└── screenshots/
    ├── desktop-home.png
    ├── projects.png
    ├── experience.png
    └── mobile-view.png
```

**Note:** The screenshot files should be added after capturing the actual website. Keep the image filenames consistent with the paths used in `index.html`.

## 5. Website Sections

### Home
Introduces me as a Computer Science Engineering student, highlights my name and interests, and provides navigation to other sections.

### About
Describes my academic background, interest in technology, and approach to learning and software development.

### Skills
Displays programming languages, web development technologies, tools, and professional skills.

### Projects
Showcases selected projects, including HandyConnect, Image Dehazing, and Advanced Text Editor.

### Education
Presents my academic qualifications and educational timeline.

### Experience and Activities
Highlights four experiences:
- Placement Coordinator — Training and Placement Cell
- Operations Team Member — Prarambh Development Cell
- Volunteer — SRIJAN DIPEX 2024
- NSS Volunteer

### Contact
Provides contact information links and a form that prepares an email draft through the user's default email application.

## 6. CSS Implementation

The external stylesheet, `style.css`, contains the website's visual design and layout rules.

### Color Scheme

| Color | Hex Code | Purpose |
|---|---|---|
| Charcoal | `#252525` | Main background |
| Amber | `#E3A542` | Highlights and accents |
| Warm Off-White | `#F4F1EA` | Main text |
| Muted Sand | `#D5C6A0` | Secondary accents |
| White | `#FFFFFF` | Supporting contrast |

### CSS Concepts Applied

- **Selectors:** Element, class, and pseudo-class selectors.
- **Typography:** Font families, font sizes, weights, and line heights.
- **Box Model:** Margins, padding, borders, and sizing.
- **Backgrounds:** Background colors and gradients.
- **Flexbox:** Navigation, buttons, tags, and footer layout.
- **CSS Grid:** Hero, skills, projects, and experience layouts.
- **Hover Effects:** Interactive styling for links, buttons, and cards.
- **Transitions:** Smooth visual changes.
- **Media Queries:** Responsive layouts for tablets and mobile screens.
- **Accessibility:** Visible keyboard focus and reduced-motion support.

## 7. Setup Instructions

1. Install Visual Studio Code and a modern web browser.
2. Open the project folder in Visual Studio Code.
3. Verify that `index.html`, `style.css`, and the `images/` directory are present.
4. Confirm that the HTML file links to the external stylesheet:

   ```html
   <link rel="stylesheet" href="style.css">
   ```

5. Open `index.html` directly in a browser, or use the Live Server extension in Visual Studio Code.
6. If using Live Server, right-click `index.html` and select **Open with Live Server**.
7. Resize the browser or use the browser's device toolbar to test responsive behavior.

An internet connection is required to load Google Fonts. Local fallback fonts are available if the external fonts cannot be loaded.

## 8. Testing and Verification

Complete the following checks before submission.

| Test Case | Expected Result | Status |
|---|---|---|
| Open `index.html` | Website loads successfully | Pending verification |
| Load external CSS | Charcoal and amber styling appears | Pending verification |
| Check images | Profile and project images display correctly | Pending verification |
| Navigate between sections | Navigation links reach the correct sections | Pending verification |
| Hover over buttons and cards | Styling transitions appear | Pending verification |
| Open mobile navigation | Menu opens and closes correctly | Pending verification |
| Check tablet layout | Content adapts to the available width | Pending verification |
| Check mobile layout | Cards stack and content remains readable | Pending verification |
| Check contact form | Required fields are validated by the browser | Pending verification |
| Submit contact form | An email draft is prepared when supported | Pending verification |
| Check browser console | No unexpected errors appear | Pending verification |

Update the test statuses after running each test. Save genuine screenshots of the tested website in the `screenshots/` directory.

## 9. Screenshots

Add the following screenshots after testing:

- `screenshots/desktop-home.png` — Desktop home section.
- `screenshots/projects.png` — Projects section.
- `screenshots/experience.png` — Experience and activities section.
- `screenshots/mobile-view.png` — Responsive mobile layout.

These screenshots provide visual evidence of the completed styling work.

## 10. Current Scope

This project focuses on Week 2 of the Web Development Internship: CSS styling of an existing portfolio website.

The work includes external CSS organization, typography, colors, layout, interactive hover styling, and responsive design. Existing basic JavaScript behavior is retained.

Additional JavaScript features, extra website pages, and new backend functionality are outside the scope of this week's task.

## 11. Future Improvements

Potential improvements for later stages include enhanced form validation, additional interactive features, and further website enhancements as required by subsequent internship tasks.

## 12. Author

**Rajvardhan Pradeep Vharambale**

B.Tech — Computer Science Engineering  
D. Y. Patil College of Engineering, Kolhapur

- **GitHub:** https://github.com/rajvardhanvharambale
- **Portfolio:** https://rajvardhanvharambale.github.io/rajvardhan-portfolio/

---

*Developed as part of the Web Development Internship — Week 2: CSS Styling.*