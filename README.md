# ElectroTrack

A mobile-first, installable Electrical Engineering study companion. It is intentionally dependency-free: open `index.html` in a current browser to explore it.

## What the MVP includes

- Ten core EE subjects, each with four topics and subtopics
- Live focus timer, per-topic/subject time totals, completion tracking, and a seven-day study rhythm
- Topic-linked multiple-choice questions with completion and correctness tracking
- Spaced revision reminders on 1, 3, 7, 14, and 30-day intervals
- Subject-wise PDF upload and in-app reading; PDFs stay on the device in browser storage
- Official links for GATE EE, UPSC ESE, RRB JE, and PSU careers

## Install on a phone

Host the `electrotrack` folder over HTTPS (for example GitHub Pages, Netlify, or any static host), open it on the phone, then use the browser's **Install app** / **Add to Home Screen** option. It is also fully usable as a regular web page.

## Important product notes

Study records are saved only in the current browser. A production release should add secure sign-in and cloud sync. Automatic examination dates also need the learner's country and chosen examinations plus a verified source/API; official-source links are used here so no unverified date is presented as fact.
