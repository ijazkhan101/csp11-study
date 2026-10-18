# CSP11 Study

Personal study site for the BCSP Certified Safety Professional (CSP11) exam.

## What's inside

| File | What it is |
|---|---|
| `index.html` | CSP11 Prep Hub: the main page with all tabs |
| `mcqs.json` | All 3,376 practice questions with answers and explanations |
| `notes.json` | Study notes data (47 topics, 434 blueprint points, 470 questions) |
| `book.html` | The study book as web pages |
| `app.html` | Study Guide & Mock Exam app |
| `CSP11_Study_Book.pdf` | Printable study book (277 pages) |
| `netlify.toml`, `robots.txt` | Netlify settings; ask search engines not to index the site |

## Tabs
- **Dashboard:** exam countdown, 13-week plan, topic tracker, domain readiness
- **Study Notes:** all topics with a domain filter, search and interactive questions
- **All MCQs:** every question one at a time, with filters by source, domain and topic; instant right/wrong with the explanation
- **My Results:** every mock exam, drill and topic quiz, with score trend, domain averages and improvement
- **Study Book (PDF):** the book as pages, plus the PDF
- **Study Guide & Exam:** study guide and timed mock exams weighted to the CSP11 blueprint

## Where results are saved
Each visitor's results are saved in their own browser (localStorage). Nobody else can see them, and they stay until the visitor clicks "Delete history" or clears their browser data. Use "Export JSON" to back them up and "Import JSON" to restore them on another device.

## Deploy
Netlify: "Add new site", then "Import an existing project", pick this repository, leave the build command empty and set the publish directory to `.`. No build step is needed.

## Note
Private study copy. It contains material from personal study guides that must not be shared publicly.
