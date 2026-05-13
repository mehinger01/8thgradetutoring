# Grade 8 State Test Tutor MVP

Fast local-first tutoring app for an anonymous Grade 8 math diagnostic and targeted practice session.

## What it includes

- Student-facing diagnostic
- Auto-expanding 12 to 18 question baseline
- Tutor report
- Manual ability sliders
- Targeted practice generator
- Hints and 3 retries
- 4-correct streak boss unlock
- Badges and local browser progress
- Copy report button for Notion/session notes

## Tutor passcode

Default passcode: `tutor`

Change it in `src/main.jsx`:

```js
const TUTOR_PASSCODE = 'tutor';
```

## Run locally

```bash
npm install
npm run dev
```

## Deploy to Vercel

1. Create a GitHub repo.
2. Upload these files.
3. In Vercel, import the repo.
4. Build command: `npm run build`
5. Output directory: `dist`

## Notes

This MVP is intentionally local-first. Results save in the browser using `localStorage`. No student names, logins, database, or third-party data sync are required.

Question content is test-style and based on the attached 2025 Grade 8 released math item structure, skill categories, and standards map. The app does not reproduce the full test as a mini-test.
