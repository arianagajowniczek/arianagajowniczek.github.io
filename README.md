# Ariana Gajowniczek: personal website

A five-page static site (Home, About, Projects, Résumé, Contact) in plain HTML and CSS.
No JavaScript, no install, no build step.

## Open it on your laptop
Double-click `index.html`, or in Finder right-click it → **Open With** → your browser.

## Finish the placeholders
Search every file for `[PLACEHOLDER]` (VS Code: Cmd+Shift+F). Each one is a box or label to replace:
- `about.html`: your About paragraph
- `projects.html`: the 150–250 word project summary; links to report, slides, charts
- `resume.html`: the résumé PDF link
- `contact.html`: LinkedIn and GitHub links

**Photo:** `photo.jpg` is used on Home and About. To change it, replace that file (keep the name).

**Résumé:** put `resume.pdf` in this folder, then in `resume.html` replace the placeholder box with
`<a class="button" href="resume.pdf">Download résumé (PDF)</a>`. Use a version without your phone number
and GPA if you want to keep those off the public site.

**Project links:** when the files exist (e.g. `files/report.pdf`), replace each
`<span class="pending">…</span>` with `<a href="files/report.pdf">Report (PDF)</a>`.
Keep file and folder names lowercase with no spaces.

## Publish on GitHub Pages (no command line)
1. github.com → **+** → **New repository** → name it (e.g. `ariana-site`) → **Public** → **Create repository**.
2. Click **uploading an existing file** → drag in the *contents* of this folder (so `index.html` is at the top) → **Commit changes**.
3. **Settings** → **Pages** → **Deploy from a branch** → **main** / **(root)** → **Save**.
4. Wait 1–2 minutes, then open `https://<your-username>.github.io/<repo-name>/`.
That URL is what your résumé QR code should point to.
