# Sabi Public Beta Package

## What this package is
A static, deployable beta of Sabi: personalised WASSCE learning, practice, mock exams, skills, analytics, planner and school-dashboard concepts.

## Included
- index.html — app
- manifest.webmanifest — installable PWA metadata
- sw.js — offline cache/service worker
- privacy.html — beta privacy notice
- terms.html — beta terms/limitations

## Deploy
Upload the entire `sabi-public-beta` folder to any static host:
- Netlify Drop
- Vercel static site
- GitHub Pages
- Cloudflare Pages

Do not upload only `index.html`; offline/PWA support depends on the other files.

## Beta data model
This build intentionally uses browser localStorage, so it requires no account or backend. That makes it suitable for controlled usability testing, but not for cross-device accounts or school-wide production use.

## Before inviting a broad student audience
1. Have practising WASSCE teachers review every question and explanation.
2. Expand the bank well beyond the current demo set.
3. Confirm current syllabus/paper structures country-by-country from official WAEC sources.
4. Replace indicative grade/readiness logic with a validated model.
5. Add server-side authentication/database only after a real privacy/security review.
6. If minors' personal data will be collected centrally, obtain appropriate legal/privacy advice for each launch jurisdiction.
7. Add monitoring, backups and admin moderation before paid school deployment.

## Public-beta success metrics
Track manually or through a privacy-reviewed analytics setup:
- diagnostic completion rate
- D1/D7 return rate
- repair-session completion
- mock completion
- score improvement after repair
- student-reported usefulness
- question-error reports per 100 questions
