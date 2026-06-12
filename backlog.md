# WRO Advisory Website — Backlog

## Status: Live

---

## Phase 1 — Publish to Cloudflare Pages ✓

- [x] Create `.gitignore` (exclude .docx, OS junk, editor files)
- [x] Initialize git repo (`git init`)
- [x] Create GitHub/GitLab remote repository
- [x] Push initial commit
- [x] Connect repo to Cloudflare Pages and deploy

---

## Phase 2 — Post-publish Fixes ✓

### Blocking / Functional

- [x] **Missing hero background image** — removed dead CSS reference to `assets/img/skyline-overlay.jpg` in `assets/css/styles.css`.
- [ ] **Contact form backend** — form currently shows a success state but sends nothing. Integrate Formspree so submissions actually arrive at info@wroadvisory.com. (Deferred — needs Formspree account setup.)

### Cleanup

- [x] **Delete `logo.jpeg`** — removed unused 284 KB duplicate.
- [x] **Update placeholder links** — LinkedIn now points to Victor's profile; Privacy Policy and Terms of Use link to new `privacy.html` and `terms.html` pages.

### Optimization

- [x] **Image optimization** — converted `logo.png` (309 KB) to `logo.webp` (112 KB, 64% smaller). All pages updated.
- [x] **Add analytics** — Cloudflare Web Analytics enabled via Pages dashboard (auto-injected).

---

## Phase 3 — Outstanding / Future

- [ ] **Contact form backend** — set up Formspree account, add form ID to `contact.html`, wire up real submission handling.
- [ ] **Hero skyline image** — optionally add a real `assets/img/skyline-overlay.jpg` (subtle overlay, opacity 0.12) to enhance the hero section.
- [ ] **Insights content** — "Read More" links on `insights.html` all point to `#`. Add real article pages or link to external publications.
- [ ] **Contact page CTAs** — "Book a Call", "Learn More", "Explore Options" buttons on `contact.html` point to `#`. Wire up to Calendly or relevant pages.
- [ ] **Move assets to subfolders** — `logo.png`, `logo.webp`, and `WRO_Advisory_Full_Design_Document.docx` are in the root. Consider `assets/img/` for logos and `docs/` (gitignored) for the design doc.
