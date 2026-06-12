# WRO Advisory Website — Backlog

## Status: Pre-publish

---

## Phase 1 — Publish to Cloudflare Pages

- [ ] Create `.gitignore` (exclude .docx, OS junk, editor files)
- [ ] Initialize git repo (`git init`)
- [ ] Create GitHub/GitLab remote repository
- [ ] Push initial commit
- [ ] Connect repo to Cloudflare Pages and deploy

---

## Phase 2 — Post-publish Fixes

### Blocking / Functional

- [ ] **Contact form backend** — form currently shows a success state but sends nothing. Integrate Formspree (or Cloudflare Workers email relay) so submissions actually arrive.
- [ ] **Missing hero background image** — `assets/img/skyline-overlay.jpg` is referenced in `assets/css/styles.css` (line 330) but the file doesn't exist. Either add the image or remove the CSS rule.

### Cleanup

- [ ] **Delete `logo.jpeg`** — unused duplicate (284 KB). Only `logo.png` is referenced in the HTML.
- [ ] **Update placeholder links** — Privacy Policy, Terms of Use, and LinkedIn all point to `#`. Create pages or link to real URLs.

### Optimization

- [ ] **Image optimization** — convert `logo.png` (309 KB) to WebP for faster load times.
- [ ] **Add analytics** — wire up Google Analytics or Cloudflare Web Analytics if tracking is desired.
