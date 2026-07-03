# Nuzhair Ali — Portfolio Website

A single-page, mobile-first portfolio built as one self-contained HTML file. No build tools, no dependencies to install — just open `portfolio.html` in a browser or host it anywhere as a static file.

## What's inside

- **Hero** — name, photo, role tagline, and quick-contact buttons (Email / WhatsApp / GitHub)
- **Skills & Tools** — programming language, core skills, and skills currently being learned
- **Projects** — featured project card with a live demo link
- **Get in Touch** — email, WhatsApp, city, and GitHub, each with a brand-style icon

## Tech notes

- Plain HTML + CSS (no framework), fonts loaded from Google Fonts (Times New Roman for headings, Inter for body, IBM Plex Mono for labels)
- Profile photo is embedded directly in the file as base64, so it stays a single portable document
- Color theme: navy blue card, amber accent, brand-colored icon badges for Gmail/WhatsApp/GitHub

## Prompt history

The site was built iteratively in conversation with Claude. Prompts used, in order:

1. Provided name, about text, skills, one project, and contact info; asked to turn it into a clean, mobile-friendly, one-page portfolio in a single HTML file
2. "Grade this page out of 10 for design and readability, then improve it." *(asked 3 times — each pass fixed newly identified issues: cluttered chip labels, missing WhatsApp CTA, no avatar, contrast, non-functional nav, chart crowding the hero)*
3. "on top of page replace the text in dark green bar with Portfolio of Nuzhair Ali"
4. "remove the buttons of A1, B1, C1, D1"
5. "change the dark green theme colour to dark grey"
6. "its not noticeable increase the tone"
7. "add SQL in programming language"
8. "suggest me where should i put sql"
9. "put it in core skills"
10. "increase the font size of headings include name skills and tools and project also change the font type to times new roman"
11. "make the background colour lightest grey family, which wont effect reading the text"
12. "restore the changes, keep it white, want to change the colour of white card"
13. "lightest of grey family which wont affect reading the text"
14. "its not noticeable increase the tone"
15. "make the background colour to navy blue"
16. Uploaded a headshot photo; "add my image"
17. "make photo as attached not in circular box"
18. "keep the size little so that the face could be visible"
19. "generate the original logo of gmail for email and of whatsapp"
20. "also do the same in GET IN TOUCH update the original logo's of all"
21. "little increase the size of image"
22. "add To be Data Scientist with data analyst and certified bi developer"
23. "give little line space"
24. "make a short README.md describing your project and the prompts you used" *(this file)*

## Files

- `portfolio.html` — the complete site
- `README.md` — this file.

