# CV Project

Personal CV for João da Silva Santos — Platform & DevOps Engineer.

## Structure

- `main.tex` — main CV document (two-page layout using altacv class)
- `page1sidebar.tex` — sidebar for page 1 (languages, skills & tooling)
- `page2sidebar.tex` — sidebar for page 2 (education, certificates, additional skills, hobbies)
- `altacv.cls` — custom document class
- `joao.jpg` — profile photo

## Build

Compile with `pdflatex` (or LuaLaTeX/XeLaTeX). Requires `lato`, `fontawesome`, `CJKutf8`, `enumitem`, `hyperref` packages.

## Guidelines

- Keep wording concise — CV bullet points should be action-oriented and result-driven.
- Preserve the existing LaTeX formatting conventions and altacv macros (`\cvevent`, `\cvtag`, `\cvskill`, etc.).
- The CV is two pages; avoid adding content that would push it to a third page.
- Dates and locations must stay accurate to real experience.
