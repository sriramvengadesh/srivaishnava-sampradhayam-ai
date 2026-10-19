
# Sri Vaishnava Knowledge Base

An independent, source-aware knowledge collection and browsing website.

## Features

- Browse topics by category
- Search titles, summaries, content, and aliases
- Open individual entries and follow source links
- Explore related topics
- Find potentially relevant entries for a question
- Track each entry's review status
- Switch between light and dark themes

## Project structure

- `index.html` — website interface and search logic
- `data/entries.json` — knowledge entries
- `data/categories.json` — category definitions
- `SOURCES.md` — source and review guidelines

## Run and publish

The website loads JSON files using `fetch()`. Browsers may block this when
`index.html` is opened directly as a file.

Publish this folder as a separate static website using GitHub Pages or a
separate Vercel project. Keep the folder structure intact.

Do not connect this project to the Dhasanudhasan repository yet.

## Adding an entry

Give each entry a unique ID and include:

- title
- category
- summary
- content
- aliases
- related entry IDs
- sources
- review_status
- review_note

Use `needs_review` until the content and references have been checked.
Only use `reviewed` when the agreed review process has genuinely been completed.

## Question lab limitations

The question lab uses basic keyword overlap. It does not understand meaning
like a semantic search model, generate answers, or verify claims. A matching
entry is a research lead, not proof that an answer is correct.

## Editorial principles

- Preserve source links.
- Distinguish traditional accounts from academic or historical interpretations.
- Record uncertainty instead of inventing details.
- Have doctrinal explanations reviewed by a knowledgeable Sri Vaishnava teacher.
- Correct mistakes transparently.
- Never present an unreviewed entry as authoritative.
