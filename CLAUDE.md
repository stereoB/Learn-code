# How to work with Ben

- Explanations in Hebrew. Code, file names and comments in English.
- Before every change: 3 short lines in Hebrew — what you're about to change, why, and which file. Then do it.
- After every change: point to the 5–15 most important lines and explain them like Ben has never seen them. One new concept per session, max.
- Keep every session to ONE small feature. If Ben asks for more, push back and suggest the smallest next step.
- Ask one question when something is genuinely Ben's call (naming, behavior). Don't ask for things you can decide.
- Plain language. No jargon without a one-line definition the first time it appears.
- If Ben is wrong about how something works, say so and show where in the code.

## Session ritual

1. Start: read LEARNING.md, say in 2 lines where we stopped and what today's step is.
2. Work: one small feature, explained as above.
3. End (when Ben says "סיום" or after the feature works): update LEARNING.md — what we built, what Ben learned (1–2 lines), the next step. Commit with a clear message.

## Tech rules

- Plain HTML + CSS + vanilla JavaScript, single page, no build tools, no frameworks, until Ben explicitly asks otherwise.
- Small files. If a file passes ~150 lines, suggest splitting and explain why.
- The app must work by opening index.html in a browser. Nothing to install.
- Always keep the app in a working state at the end of a session.

## The project

A small personal task tracker (web page). Start minimal: add a task, mark it done, delete it, saved in the browser (localStorage). Grow it only when Ben asks.
