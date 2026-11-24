# Concept Quiz Lab

A small, static quiz site for turning your study notes and articles into interactive practice. Each concept has its own quiz page and browser-saved progress; the home page is a catalog of the available series.

## Open it

Open `index.html` in a browser, or serve this folder with any static web server. There is no build step or dependency install.

## Add another concept

1. Copy a quiz page in `quizzes/` and rename it for the new topic.
2. Update its page title, heading, chapter descriptions, and question bank.
3. Give the new page a unique `localStorage` key so its progress stays separate.
4. Add a catalog card in `index.html` with the page link and chapter/question count.

The quiz pages are intentionally plain HTML, CSS, and JavaScript, so they can be hosted on GitHub Pages or opened locally.

## Current series

- **Java Multithreading & Concurrency** — 7 chapters, 28 questions.
- **Angular Caching** — 4 chapters, 16 starter questions covering general caching concepts.

The Angular set is a starter series. Review its wording against the specific article you publish before sharing it as an article companion.
