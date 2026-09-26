# Project conventions

## No prompt-related comments

Never leave prompt- or request-derived comments anywhere in the codebase
(HTML, JS, CSS, or any other file). Do not record in comments what was
asked for, why a change was made, where content was copied from, or any
back-and-forth from the working session.

Examples of what NOT to write:
- `<!-- removed on request 2026-09-19; un-comment to restore -->`
- `/* harmonized with coaching.istvankis.com */`
- `/* professional background (brought from coaching) */`
- `// per the user's request, use Inter here`

Comments should only describe the code itself when genuinely useful
(functional section labels, non-obvious behavior). Keep the source clean
of any trace of the prompt or the collaboration.
