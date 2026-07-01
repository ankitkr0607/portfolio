# Ankit Kumar Swashi — Portfolio

Personal portfolio website for **Ankit Kumar Swashi**, Senior Client Partner at DViO Digital.

A single-file, self-contained portfolio built as a multi-page single-page application (SPA). No build step, no dependencies, no server required — everything (images, videos, resume, styling, and scripts) is embedded directly in `index.html`.

## Pages

- **Home** — Hero, brands worked with, featured campaigns
- **About** — Bio, photo, and core skills
- **Work** — 9 full case studies (Universal Music India, VYRL Bhojpuri, Aditya Birla Memorial Hospital, Artis, Orange Health Labs, SmartKargo, Aditya Birla Group, UnderRated Club, Flipkart)
- **Experience** — Career timeline and process
- **Contact** — Links and downloadable resume

## Files

| File | Purpose |
|------|---------|
| `index.html` | The complete portfolio website |
| `Ankit_Kumar_Swashi_Resume.pdf` | Resume (also embedded in the site's download button) |
| `Ankit_Kumar_Swashi_Resume.docx` | Editable resume source |

## Deploying with GitHub Pages

1. Create a new repository on GitHub (e.g. `portfolio` or `ankitkumarswashi.github.io`).
2. Upload all files in this folder to the repository (or push via Git).
3. Go to **Settings → Pages**.
4. Under **Source**, select the `main` branch and the `/ (root)` folder, then **Save**.
5. Wait a minute — your site goes live at:
   - `https://<your-username>.github.io/<repo-name>/` for a normal repo, or
   - `https://<your-username>.github.io/` if the repo is named `<your-username>.github.io`

Because `index.html` is at the root, GitHub Pages serves it automatically.

## Deploying elsewhere

The site is a single static file. It also works on:

- **Netlify / Vercel** — drag and drop the folder, or connect the repo
- **Cloudflare Pages** — connect the repo, no build command needed
- **Any web host** — just upload `index.html`
- **Locally** — double-click `index.html` to open it in any browser

## Editing

To update content, open `index.html` in a code editor. All copy, links, and embedded media live inside that one file. The resume download button reads an embedded copy of the PDF, so if you change the resume, re-embed it or update the link accordingly.

---

Built with a cinematic dark editorial aesthetic. Fonts: Cormorant Garamond + DM Sans (loaded from Google Fonts).
