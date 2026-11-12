# QFA Loans Practice

A practice quiz for the QFA **Loans** module (Professional Diploma in Financial Advice, Ireland).
It runs entirely in the browser, can be added to a phone's home screen, and works offline once opened.

> Unofficial practice questions for personal study. Not affiliated with or endorsed by the
> Institute of Banking (IOB). The questions were written with AI assistance and may contain errors.
> Always check the current IOB course text — rules, figures and thresholds change.

## What it covers

283 multiple-choice questions across 8 topics:

| Topic | Questions |
|---|---|
| Credit and interest fundamentals | 35 |
| Personal lending products | 35 |
| Mortgages and home loans | 35 |
| Assessing the borrower | 35 |
| Security and legal aspects of lending | 35 |
| Consumer credit legislation | 35 |
| Arrears, debt and insolvency | 37 |
| Regulation of lending | 36 |

Several topics include calculation questions, with the working shown in the explanation.

### Rules that changed recently

The questions follow Irish rules as of late 2026 and name the regime or date where something changed.
Your course text may be based on earlier rules.

- Mortgage arrears rules are part of the revised Consumer Protection Code from 24 March 2026
  (previously the separate Code of Conduct on Mortgage Arrears).
- Consumer credit scope questions are worded "under the 2010 Regulations"; a new EU directive
  applies from 20 November 2026.
- Central Bank mortgage limits used: 4x income for first-time buyers, 3.5x for others; 90% loan-to-value.

## Features

- **Practice** one topic or a mix, with the correct answer, an explanation and a reference after each question
- **Mistake review**: wrong answers are remembered; a question is cleared after two correct answers in a row in review mode
- **Mock exam**: timed, no feedback until the end, 60% pass mark, per-topic breakdown
- Star any question to revisit it, light and dark theme, keyboard shortcuts (1–4 or A–D, Enter for next)

## Using it

Open the site's address in a browser. With GitHub Pages the address is
`https://<username>.github.io/<repository-name>/`.

### Add to an iPhone home screen

1. Open the address in **Safari**.
2. Tap **Share**, then **Add to Home Screen**.
3. Open it once from the new icon while online. After that it works without a connection.

### Add to an Android phone

Open the address in Chrome, tap the **⋮** menu, then **Add to Home screen** (or **Install app**).

## Your progress

- Progress is stored **in the browser on each device**. Nothing is sent anywhere.
- A phone and a computer each keep their own progress. Use **Export** and **Import** in the app to move it between them.
- Clearing the browser's site data, or removing the home-screen app, deletes the progress on that device. Export first if you want to keep it.

## Publishing on GitHub Pages

1. Upload all files in this folder to the top level of a public repository.
2. Go to **Settings → Pages**, choose **Deploy from a branch**, branch `main`, folder `/ (root)`, and save.
3. Wait a minute or two for the address shown on that page to go live.

## Files

| File | Purpose |
|---|---|
| `index.html`, `app.js`, `styles.css` | The quiz interface |
| `questions.json` | All questions, with answers, explanations and references |
| `static-api.js` | Loads the questions and saves progress in the browser |
| `sw.js` | Offline cache |
| `manifest.webmanifest`, `icon-*.png` | Home-screen name and icon |
