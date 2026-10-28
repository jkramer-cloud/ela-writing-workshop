# The Writing Workshop — RACES & RACECES

A free, offline-capable HTML/CSS/JavaScript writing-coach app intended for grades 5–8. **No AI, API key, server, or subscription required.**

## Get started

1. Download `ela-writing-workshop.html` and open it in Chrome, Edge, or another modern browser.
2. Select 5th or 6th grade for **RACES** (one evidence/explanation pair) or 7th or 8th grade for **RACECES** (two pairs).
3. Enter a book, author, and teacher's writing prompt, **or** choose one of 12 original practice passages across 6 genres.
4. Write each section, view optional hints, and examine the structural writing checks.
5. Open **Review & Export**, edit the assembled paragraph, copy your response, download it, print it, or open Google Docs to paste it.

## For the Learning Hub / GitHub Pages

- Rename the app file to `index.html` if you want it to load as the root of a GitHub Pages repository.
- Or add it as `ela-writing-workshop.html` in your Learning Hub project and link to that file.
- It is a **single self-contained file**. There are no external libraries, fonts, images, API calls, or credentials.
- You can link to the deployed page from the Learning Hub, or embed it in an iframe if your hosting and page settings permit it.

Suggested Learning Hub entry:

**Title:** ELA Writing Workshop — RACES & RACECES

**Description:** Build better written responses one step at a time. Grades 5–6 practice RACES and grades 7–8 practice RACECES. Explore original stories, get guided hints and writing checklists, organize text evidence, revise a complete paragraph, and export your work. No AI account or sign-in needed.

## Included

- RACES and RACECES grade-aware workflows
- 12 original fictional practice passages in Fantasy, Mystery, Science Fiction, Realistic Fiction, Historical Fiction, and Adventure
- Page/paragraph source reminders and explain-vs-cite coaching
- Rule-based checks for structure, wording, mechanics, citations, and some repetition
- Optional hint levels, unrelated models, and teacher-adjustable local workshop settings
- Skill challenge to distinguish Restate, Answer, Cite, Explain, and Summarize
- Automatic browser-local saving, multiple drafts, manual JSON backup/import
- Assembled paragraph, optional final polishing, copy, TXT, printable HTML, print, Google Docs launch, and email draft
- Responsive screen and keyboard-friendly controls

## Important limitations

- The checks are **heuristics, not grades**. They cannot reliably judge whether an interpretation is accurate or whether quoted evidence actually exists in the student's book.
- All sample passages are built into the file. The app does not actually generate new AI stories; "Surprise me" randomly selects from the original passage library.
- "Open Google Docs" opens Google Docs separately. Students must paste their copied response; there is no access to school Google accounts.
- "Prepare email" opens the user's default mail app; it does not send a message itself. For longer responses, copying/pasting is more reliable.
- Browser storage remains on that computer and browser profile. Shared profiles may expose drafts to others; clearing browser data may remove them. **Download a JSON backup** for important work. Some browser privacy policies block local storage for local `file://` URLs, so hosting on GitHub Pages is preferable.
- Settings are not password-protected and cannot enforce a secure assessment mode.
- A print/exported response still needs the teacher's review.

## Privacy

The application has no analytics, server, or external data connections of its own. Text is saved in browser `localStorage` on the user's device unless the user manually copies, emails, opens Docs, prints, or downloads it. As with any classroom device, use individual browser profiles and avoid entering unnecessary personal information.

## Future ideas

- Separate classroom presets or importable teacher-created assignment packs
- Richer library with nonfiction practice passages, poetry, and argumentative prompts
- Student-friendly revision exercises and additional clarity checks
- A built-in self-evaluation rubric based on teachers' actual grade-level expectations
