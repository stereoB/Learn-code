# Learning log

Claude updates this at the end of every session. Ben reads it at the start of the next one.

## Current status

- Project: personal task tracker (HTML/CSS/JS, single page)
- Where we stopped: clicking "הוסף" adds the typed text to a list and clears the input; empty or spaces-only input is ignored. Tasks disappear on refresh (not saved yet).
- Next step: pressing Enter in the input adds the task too (no need to click the button)
- Workflow: commit and push directly to main

## Concepts I've learned

(one line each, newest at the top)

- `if (condition) { ... }` runs the code only when the condition is true; `!==` means "is not equal to".
- Creating elements with JS: `document.createElement("li")` makes a new element, `list.appendChild(item)` puts it on the page.
- Event listener: `button.addEventListener("click", function () {...})` = "when this is clicked, run this code".
- `<input>` = a box to type in, `<button>` = a clickable button; `id` = a unique name so JavaScript can find the element later.
- `lang="he" dir="rtl"`: attributes on `<html>` — the page's language, and that it reads right-to-left.
- HTML structure: `<head>` = info about the page (title, encoding), `<body>` = what you actually see; tags open `<x>` and close `</x>`.

## Session log

(newest at the top: date — what we built — what I learned)

- 2026-10-28 — Empty tasks are no longer added — `if` lets code make decisions.
- 2026-10-28 — Tasks now appear in a list on the page — JS can create new HTML elements and add them to the page.
- 2026-10-28 — First JavaScript: "הוסף" shows the typed text in an alert — finding elements by id, and reacting to a click.
- 2026-10-28 — Added a text input and an "הוסף" button — input/button tags, and `id` as a name for JS to find elements.
- 2026-10-28 — Switched the page to Hebrew (RTL), moved to working directly on main — `dir="rtl"` flips the whole page's direction.
- 2026-10-28 — Created index.html with a title — How an HTML file is built: doctype, html, head, body.
