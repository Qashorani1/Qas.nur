# Nursing Atlas — Website Prototype v0.1

An English-language, responsive, static nursing learning website built with HTML, CSS, and JavaScript. No build tools, paid services, or external API keys are required. Open `index.html` in a modern browser. Google Fonts require internet access; system fonts are the fallback.

## Included
- Homepage and course catalog with five Adult Health Nursing I systems and 114 mapped headings
- Full draft Myocardial Infarction topic with 11 organized sections, quick navigation, and progress marking
- Draft NANDA-I nursing diagnosis and care plan section with evidence-based selection caveats
- Three educational clinical cases (two solved, one with reveal-after-attempt prompt)
- Four interactive NCLEX-style questions with answer-specific rationales
- Topic search, bookmark, English term translation on tap, local browser progress, mobile-responsive dark theme

## Limitations
- Only MI has developed content. Other headings are placeholders.
- The independent case uses a reveal button, not a scored multi-step submission.
- Browser localStorage is not an account system and does not sync across devices.
- All clinical content is a draft. Validate against current clinical guidelines, NANDA-I, NOC, and NIC licensed editions before public launch.
- This is not a hosted site; deployment and domain setup are separate steps.

## Hosting
Upload the three web files (`index.html`, `styles.css`, `app.js`) to any static web host (e.g. GitHub Pages, Netlify, Cloudflare Pages). Configure a custom domain separately if desired.

## Editorial references to verify
- 2025 ACC/AHA/ACEP/NAEMSP/SCAI guideline for management of acute coronary syndromes
- Fourth Universal Definition of Myocardial Infarction (2018)
- Current NANDA International nursing diagnoses classification and licensed NOC/NIC publications

Brand name 'Nursing Atlas' is a temporary placeholder, not a finalized brand.


## Optional translation (v0.2)
On mobile, long-press and select any English word or phrase in the learning content. Tap the Translate to Arabic prompt to open Google Translate in a separate tab. On desktop, select text with the mouse. Translation is opt-in, requires an internet connection, and is provided by an external service. Safari's native selection menu may also offer Translate.


## v0.3 update (October 2026)
- Expanded all 11 MI review sections with focused teaching, tables and assessment rationales.
- Added four clinical judgment practice questions (eight total).
- Independent RV infarction case now requires an answer before revealing rationales.
- Preserved optional long-press text selection translation to Arabic through Google Translate.
- Educational draft only: verify clinical content and licensed NANDA-I/NIC/NOC terminology before public educational release.

To update GitHub Pages, upload and commit `app.js` from this archive to the repository root, replacing the existing file. Other files are included for completeness.
