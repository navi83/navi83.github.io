# navi83.github.io

This repository contains a lightweight personal site (single-page) for Vy Huynh, built as a simple dev-portfolio style landing page.

What's included
- `index.html` — the single-page site (hero, about, experience, skills, education, social links). The Contact section was removed per user request.
- `assets/styles.css` — styling for the page (light/dark theme variants were experimented with; current styles are applied here).
- `assets/avatar.jpg` — avatar image used in the header (replace with your own photo for best results).
- `README.md` — this file.

Current features
- Centered card layout inspired by a dev-portfolio (hero with avatar + meta, about, experience, skills, education).
- Social icons (GitHub, LinkedIn, email) and primary action buttons.
- Skill badges and simple timeline-style experience entries.
- Responsive layout and small-screen adjustments.

Notes / Pointers
- Contact: The Contact section and its button were intentionally removed. If you want it back, tell me and I'll re-add it.
- Avatar: The repository contains `assets/avatar.jpg` (originally 720×722). Replace this file with a square photo (recommended 400×400) named `assets/avatar.jpg` to remove an informational warning and improve load performance.
- Inline overrides: A small inline style block was temporarily added to `index.html` while we tuned typography and avatar rendering; after you confirm the layout looks correct I can remove that inline block so all styles live in `assets/styles.css`.

How to customize
- Edit `index.html` to update text sections: About, Experience entries, Education, and Skills.
- Edit `assets/styles.css` to change colors, spacing, and typography. The color variables live in `:root` at the top of the file.
- Replace `assets/avatar.jpg` with your photo. Use a square crop and a size of ~400×400 for best quality and performance.

Deploy (GitHub Pages)
1. Commit and push changes to the `main` branch:

   git add .
   git commit -m "Update personal site"
   git push origin main

2. In GitHub: Repository Settings → Pages → Source: choose `main` branch and `/ (root)` folder, then Save.
3. Visit `https://<your-username>.github.io/<repo>` (or check the Pages URL shown in the repo settings).

Quick local verification
- After updating CSS or the avatar, do a hard-refresh in your browser (Cmd+Shift+R on macOS) to avoid stale cache.

If you'd like
- I can remove the inline CSS override now that you confirm the layout is correct.
- I can resize/optimize `assets/avatar.jpg` to 400×400 for you and replace the file.
- I can commit & push these changes to your remote branch for you.

Tell me which follow-up you'd like and I'll apply it: remove inline overrides, resize avatar, push changes, or anything else.
