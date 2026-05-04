# chrismeyer.dev — personal portfolio

A simple, hand-built personal portfolio site. Plain HTML and CSS, no build step, hosted on GitHub Pages.

## Files

```
portfolio/
├── index.html     ← Home page
├── about.html     ← Background and experience
├── projects.html  ← Project list
├── contact.html   ← Contact details
├── styles.css     ← Shared stylesheet
└── README.md      ← This file
```

## How to edit

1. Open the folder in VS Code (`code .` from Terminal)
2. Right-click any `.html` file → **Open with Live Server** to preview
3. Edit any HTML file — the content is plain text wrapped in tags
4. Save → Live Server auto-refreshes the browser
5. When happy, commit + push via GitHub Desktop or VS Code's Source Control panel
6. GitHub Pages auto-deploys within a minute

## To add a real photo

1. Save a square portrait as `portrait.jpg` in this folder
2. In each `.html` file, find the `<div class="portrait">CM</div>` line
3. Replace `CM` with `<img src="portrait.jpg" alt="Chris Meyer">`

## To add a new project

1. Open `projects.html`
2. Copy an existing `<div class="project">...</div>` block
3. Edit the date, status, title, description, and tags
4. Save

## Hosting

This site is deployed via **GitHub Pages** from the `main` branch. Any push to `main` triggers a fresh deployment. The live URL is set in repository Settings → Pages.
