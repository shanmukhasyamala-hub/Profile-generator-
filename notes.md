# Day 1 Notes — HTML Fundamentals

## Environment setup
- Installed VS Code, set up Git & GitHub (repo + first commit).
- Created project folder structure: `day1/` containing `index.html`,
  `README.md`, `Notes.md`.

## HTML concepts practiced
- **Semantic tags**: used `<header>`, `<main>`, `<section>`, `<article>`,
  `<footer>` instead of generic `<div>`s so the page structure is meaningful,
  not just visual.
- **Forms**: `<form>`, `<fieldset>`, `<legend>`, `<label for="">` linked to
  matching `<input id="">`. Learned why `label`↔`input` pairing matters for
  accessibility (clicking a label focuses its input; screen readers announce
  it correctly).
- **Input types & validation**: `type="text"`, `type="number"`, plus
  `required`, `min`, `max` attributes for basic client-side validation
  without JavaScript.
- **Description lists**: used `<dl>`/`<dt>`/`<dd>` to present key–value
  student details (Age, College, Branch) — more semantically correct than a
  table or a stack of `<div>`s for this kind of data.

## JavaScript (light touch, mostly for the generator)
- `addEventListener('submit', ...)` + `e.preventDefault()` to stop the page
  from reloading on form submit.
- Reading values with `document.getElementById(...).value`.
- Building the output card with a template literal and injecting it via
  `innerHTML`.
- Small helper functions: `initials(name)` to derive avatar letters,
  `randomId()` to fake a student ID number.

## Things to review / follow up
- Look deeper into form validation patterns (`pattern` attribute, custom
  validity messages via `setCustomValidity`).
- Revisit accessibility: currently the avatar circle is `aria-hidden`, but
  double-check the whole card reads sensibly with a screen reader.
- Compare `innerHTML` templating vs. building elements with
  `document.createElement` — the latter is safer against injection and worth
  practicing before Day 6/7 (JS-heavy days).

## Time
- Estimated: 2h
- Actual: ~3h (extra time spent tuning the ID-card layout/styling)