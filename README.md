# WST 156 · Web Media Production

Eight 180-minute classes for a four-week course. Student-facing notes, actual browser experiments, four graded projects, practice assets, quizzes and downloadable worksheets. No build process or paid account is required for the website itself.

## Preview
Open `index.html` or, for best video/caption behavior, open the folder in VS Code with Live Server. Alternatively run `python -m http.server 8000` in this folder and visit http://localhost:8000.

## GitHub Pages
1. Create a repository (e.g. `web-media-production`). A public repository is the simplest GitHub Pages option.
2. Upload the **contents** of this folder to the root of the repository, including `assets/`, `index.html`, CSS, JS and `.nojekyll`.
3. In Settings → Pages, select **Deploy from a branch**, choose `main` and `/(root)`, then Save.
4. Open the published URL shown by GitHub. All internal file links use relative paths and work under a project repository path.
5. Commit changes to the same branch to update the site.

Official instructions: https://docs.github.com/en/pages/quickstart

## Instructor setup
- Set your LMS submission instructions and due dates (the site deliberately does not invent dates).
- Class 1–2: meme; 3–4: static ad campaign; 5–6: AI-assisted commercial; 7–8: final reel. The second day of each week continues the same graded project.
- Preview AI tool availability before Class 5. Free credits and eligibility vary; do not require paid credits. The assignment includes an equal-credit non-AI fallback.
- Class 6: optionally prepare two short approved PS5 captures of the same scene at different encoding settings; use the local upload controls. The supplied synthetic test clips work immediately without gameplay. Class 7: supply approved gameplay or use the synthetic clips for the practice edit. Do not place copyrighted gameplay, private voice chat or student files in a public repo unless authorized.
- The site's class completion and quality checklist are stored in the local browser only; no student tracking, LMS, accounts or server-side submission is implemented.
- `index.html`: editable lecture content and assignment briefs; `style.css`: visual theme and responsive layout; `labs.js` and `course.js`: demonstrations, navigation and quizzes. The links use hashes, so a lesson can be shared directly (e.g. `#class-6`).
- Practice graphics and motion patterns are original synthetic content created for these lessons; they are not gameplay or actual AI-generated clips. The HDR example is illustrative, not calibrated footage.
- Technical references are linked in the Resource library. Based on the original ten-page WMP notes, corrected and expanded for November 2026.
