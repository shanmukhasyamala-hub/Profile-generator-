# Day 1 — Student Profile Generator

## Goal
Set up the development environment and understand HTML fundamentals by building
a small, semantic HTML page: a **Student Profile Generator** that accepts a
student's **name, age, college, and branch**, then displays a generated
profile ("ID card") on the same page.

## Topics covered
- VS Code setup, Git & GitHub basics, project structure
- HTML5 & semantic tags (`header`, `main`, `section`, `article`, `footer`, `form`, `fieldset`)
- Headings, paragraphs, lists, links, images
- Forms & labels, input validation attributes (`required`, `min`, `max`)

## What was built
A single-page app (`index.html`) with:
- A **form** collecting Name, Age, College, Branch, using proper `<label>` /
  `<input>` pairing and `required` validation attributes.
- A **generator** (vanilla JavaScript) that reads the form values and renders
  a styled student ID card into a semantic `<section>` using `<article>`,
  `<dl>`/`<dt>`/`<dd>` for the details.
- No frameworks — pure HTML, CSS, and JS, matching the Day 1 brief.

## How to run
Open `index.html` directly in any browser — no build step required.

1. Fill in Name, Age, College, Branch.
2. Click **Generate profile**.
3. The student ID card appears on the right (or below, on mobile).

## Files
```
day1/
├── index.html   # the profile generator page
├── README.md    # this file
└── Notes.md     # personal learning notes
```

## Status
✅ Completed — estimated 2h, actual ~3h.