# My Personal Site

A small, beginner-friendly website following your HTML and CSS lesson. No framework, JavaScript, or installation is needed.

## Open the website

Open `index.html` in a browser. Keep `style.css` and `workspace.jpg` in the same folder as `index.html`.

## Make it yours

1. Open the folder in VS Code.
2. In `index.html`, change the browser-tab `<title>` and replace `Your Name` with your name.
3. Edit the introduction, interests, and project descriptions.
4. Change colors, fonts, spacing, and borders in `style.css`.
5. To use your own photo, replace `workspace.jpg` and update the image's `alt` description.

## How it matches the lesson

- `<!DOCTYPE html>`, `<html>`, `<head>`, and `<body>` form the document.
- `<title>` names the browser tab, while `<h1>` is the visible page heading.
- `<p>`, `<b>`, `<i>`, and `<br>` format text.
- `<header>`, `<nav>`, and `<section>` organize the page.
- Links to `#about` and `#projects` jump to the matching section ids.
- `<div>` containers group content. Repeated classes apply matching styles.
- `#first-project` demonstrates styling a unique element with an id.
- `<img>` displays a local image and provides descriptive alternative text.
- The external stylesheet demonstrates background colors, text colors, fonts, widths, heights, margins, padding, borders, and rounded corners.
- A small media query lets the layout adapt to phone screens.

HTML notes: `<!DOCTYPE html>` goes before the opening `<html>` tag. Headings indicate content hierarchy, not just text size. The `<img>`, `<br>`, `<hr>`, `<meta>`, and `<link>` elements do not need closing tags.

Photo: Christopher Gower, https://unsplash.com/photos/m_HRfLhgABo (Unsplash License).

## Publish on GitHub Pages

1. Create a public GitHub repository.
2. Upload index.html, style.css, workspace.jpg, and README.md directly into the top level of the repository. Do not upload the ZIP itself or put the files inside another folder.
3. Commit the files to main.
4. Open Settings > Pages.
5. Under Build and deployment, choose Deploy from a branch.
6. Choose main and /(root), then Save.
7. Wait for deployment to finish, then open the URL shown in Pages settings.

Official instructions: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
