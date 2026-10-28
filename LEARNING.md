# Learning log

Claude updates this at the end of every session. Ben reads it at the start of the next one.

## Current status

- Project: personal task tracker (HTML/CSS/JS, single page)
- Where we stopped: clicking "הוסף" pops up an alert with the typed text (JS lives in a `<script>` at the bottom of index.html)
- Next step: instead of an alert, add the typed text to a visible list on the page (`<ul>` + JS creates an `<li>`)
- Workflow: commit and push directly to main

## Concepts I've learned

(one line each, newest at the top)

- Event listener: `button.addEventListener("click", function () {...})` = "when this is clicked, run this code".
- `<input>` = a box to type in, `<button>` = a clickable button; `id` = a unique name so JavaScript can find the element later.
- `lang="he" dir="rtl"`: attributes on `<html>` — the page's language, and that it reads right-to-left.
- HTML structure: `<head>` = info about the page (title, encoding), `<body>` = what you actually see; tags open `<x>` and close `</x>`.

## Session log

(newest at the top: date — what we built — what I learned)

- 2026-10-28 — First JavaScript: "הוסף" shows the typed text in an alert — finding elements by id, and reacting to a click.
- 2026-10-28 — Added a text input and an "הוסף" button — input/button tags, and `id` as a name for JS to find elements.
- 2026-10-28 — Switched the page to Hebrew (RTL), moved to working directly on main — `dir="rtl"` flips the whole page's direction.
- 2026-10-28 — Created index.html with a title — How an HTML file is built: doctype, html, head, body.
