# Unit 15 – Student Hands-On Lab

## Refining and Deploying Your Web Project

---

## Purpose of this lab

In this lab, you will:

- Review and clean up your HTML and CSS
- Validate your code
- Test accessibility and responsiveness
- Write a clear README file
- Prepare your project for submission
- Deploy your site using GitHub Pages

This lab focuses on **finishing well**: quality, clarity, and professionalism.

---

## What you will work on

You will refine an **existing web project** that you have already built.

By the end of this lab, your project will be:

- Clean and readable
- Accessible
- Responsive
- Properly documented
- Live on the web

---

## Prerequisites

Before starting, make sure you have:

- A completed HTML/CSS project
- VS Code (or another editor)
- A web browser
- Git installed
- A GitHub account

---

## Part 1 — Code Review & Clean-Up

### Goal

Improve code quality and remove unnecessary clutter.

---

### Steps

1. Open your project folder in your editor.

2. Review your HTML and CSS:
   - Remove unused classes, IDs, or commented-out code
   - Remove duplicate or unnecessary styles
   - Ensure consistent indentation (2 or 4 spaces)
   - Add brief comments to explain sections in HTML and CSS

3. Validate your HTML:
   - Go to [https://validator.w3.org](https://validator.w3.org)
   - Upload or paste `index.html`
   - Fix any errors or warnings

4. Validate your CSS:
   - Go to [https://jigsaw.w3.org/css-validator/](https://jigsaw.w3.org/css-validator/)
   - Upload or paste your CSS file
   - Fix any issues

5. Check that:
   - All links work
   - All image paths are correct
   - No files are missing or broken

---

### Checkpoint

- HTML and CSS validate without errors
- Code is readable and tidy
- Nothing unnecessary remains

---

## Part 2 — Accessibility Check

### Goal

Confirm your project meets basic accessibility expectations.

---

### Steps

1. Confirm that:
   - All form inputs (if any) have labels
   - All images have appropriate `alt` text

2. Test keyboard navigation:
   - Use `Tab` and `Shift + Tab`
   - Navigate through links, buttons, and forms
   - Use `Enter` or `Space` to activate elements

3. Confirm:
   - Tab order is logical
   - Focus is visible

4. Install and run an accessibility audit tool:
   - Install **axe DevTools** (Chrome extension)
   - Run an audit on your page
   - Fix at least **two** reported issues

---

### Checkpoint

- Page works fully with keyboard only
- Major accessibility issues have been addressed

---

## Part 3 — Responsive Testing

### Goal

Ensure the site works across different screen sizes.

---

### Steps

1. Open browser DevTools.

2. Enable the **device toolbar**.

3. Test at multiple widths, for example:
   - 375px (mobile)
   - 768px (tablet)
   - 1440px (desktop)

4. Look for:
   - Overflow
   - Broken layouts
   - Hidden or unreadable content

5. Adjust media queries if needed.

Example:

```css
@media (max-width: 768px) {
  nav ul {
    flex-direction: column;
  }
}
```

6. Confirm:
   - Buttons and inputs are touch-friendly
   - Text remains readable

---

### Checkpoint

- Layout adapts cleanly at different sizes
- No content becomes unusable

---

## Part 4 — Preparing for Submission

### Goal

Document and organise your project professionally.

---

### Steps

1. Create or update `README.md`.

Include at least the following sections:

```md
# Project Title

## Description

Short summary of what the project does.

## Features

- Semantic HTML
- Responsive layout
- Accessibility best practices
- Custom styling / Bootstrap

## Accessibility Notes

Brief description of how accessibility was tested.

## Live Site

(Link will be added after deployment)

## Author

Your name or GitHub username
```

2. Organise your files:
   - HTML, CSS, images, and assets in one clear structure
   - Remove unrelated files such as:
     - `.DS_Store`
     - `.zip`
     - draft files

---

### Checkpoint

- README explains the project clearly
- Folder structure is clean and logical

---

## Part 5 — Deploying with GitHub Pages

### Goal

Publish your project live.

---

### Steps

1. Initialise Git (if not already done):

```bash
git init
```

2. Add the remote repository:

```bash
git remote add origin https://github.com/YOUR_USERNAME/project-name.git
```

3. Add and commit your files:

```bash
git add .
git commit -m "Final version"
git branch -M main
git push -u origin main
```

4. Enable GitHub Pages:
   - Open the repository on GitHub
   - Go to **Settings → Pages**
   - Source: **Deploy from branch**
   - Branch: `main`
   - Folder: `/ (root)`
   - Save

5. Wait 30–60 seconds for deployment.

6. Copy the live site URL.

7. Paste the link into your `README.md` under **Live Site**.

---

### Checkpoint

- Site loads at the GitHub Pages URL
- Live link works correctly

---

## Final Checklist

Before finishing, confirm that:

- HTML and CSS are validated
- Project is accessible and responsive
- README is complete
- Code is pushed to GitHub
- GitHub Pages site is live and tested
- (Optional) ZIP copy of the project has been created

---

## End of Unit 15 Hands-On Lab

You have now:

- Refined a real web project
- Applied accessibility and responsiveness checks
- Documented your work clearly
- Deployed a live website

You are now ready for **final presentations, reviews, and assessments**.
