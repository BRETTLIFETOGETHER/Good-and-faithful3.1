# Good and Faithful 3.1

A LifeTogether covenant and curriculum experience based on Brett Eastman's six commitments: Receive with Gratitude, Trust God Fully, Steward Faithfully, Live Generously, Prepare Others, and Begin Today.

## Included
- Responsive introduction and six complete session guides.
- Thirty original short devotional drafts with Scripture links, reflection, practice, and prayer.
- Individual, family, business-owner, and small-group applications.
- The Good and Faithful Covenant and a private 90-day practice worksheet.
- Two-page browser print layout and plain-text plan download.

## Run
Serve `public` with any static server, for example `python3 -m http.server 8000 --directory public`.

## Deploy on Netlify
Connect this repository, select `main`, leave build command blank, and publish `public`. `netlify.toml` records the publish directory. Preserve the target site's existing visitor access controls. The `.netlify` directory is ignored and must not be committed.

## Content and privacy
The curriculum is an original LifeTogether draft developed from the approved conversation outline; it does not imply endorsement by Terry Parker, NCF, The Signatry, or Generous Giving. It does not contain their licensed media. The only direct Scripture quotation is Matthew 25:21 (NIV); other passages are linked for reading. Personal worksheet entries are held only in page memory: no accounts, submissions, analytics, persistent browser storage, or backend. Reloading loses entries; visitors may print or download their own copy.

## Structure
- `public/index.html`: page structure
- `public/styles.css`: responsive navy/gold and cream design with print styles
- `public/content.js`: six sessions, 30 readings, covenant commitments, pathway copy
- `public/app.js`: accessible dialogs/tabs, reading navigation, print and download
