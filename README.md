# Baby Diary — ready-made bilingual 40-week library

## This version works without generating 562 AI articles

This package includes a prepared content library with 40 week-specific pregnancy entries in English and Lithuanian plus seven rotating daily focus modules in both languages. The site composes a day-specific article from the relevant gestational week and the daily focus, so changing the due date immediately remaps dates to the same developmental stage. It does not require an API key, GitHub Actions, or waiting for generated articles.

The included content is educational and intentionally cautious. It is not 280 unique long-form research essays, and it does not claim to provide fresh daily research, verified personal stories, or current Lithuanian benefit amounts for every date. It provides a usable prepared daily content library, with a weekly development note and a different daily focus. For richer researched editions, you can later add a reviewed content pack.

## Publish on GitHub Pages

1. Back up the current repository.
2. Copy the contents of this folder into the root of `kimavei/baby-diary`, preserving the files as shown.
3. Commit and push to the branch used by GitHub Pages.
4. Confirm `index.html` and `content-library.json` are both at the site root.
5. Open the site and test the due-date field and English/Lithuanian switch.

## How due date personalization works

The browser calculates the start of the conventional pregnancy timeline as due date minus 280 days. Each calendar date maps to a gestational day index; the week-specific and daily-focus content is displayed for that index. It includes dates from 0+0 to 40+0 inclusive (281 calendar dates, with 280 elapsed days between endpoints).

The date is editable in the page and is not sent anywhere. If a visitor chooses a new due date, all calendar dates and gestational stages recalculate instantly. No account, API, or backend is required.

## Limitations and safety

- This is prepared, template-composed daily content, not 281 fully unique, freshly researched articles.
- Sources are described generally rather than attached to every individual claim. For publication as a medical resource, add source-checked citations and clinical review.
- The Lithuanian text is provided as a practical bilingual draft; have a fluent Lithuanian health professional review it before relying on it for medical/legal guidance.
- The calendar's due date is an estimate and should follow the date advised by the user's maternity team.
- Educational information only. Seek urgent care for reduced/changed fetal movement, bleeding, leaking fluid, severe headache or visual changes, severe abdominal pain, chest pain or severe shortness of breath.
- If the repository is public, the content is public. Do not add personal medical records.
