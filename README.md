# Mahdi Hachicha — Portfolio

A single-page portfolio site (`index.html`, no build step, no dependencies besides a Google Fonts link) styled like a PCB schematic sheet — dark board-green background, copper accents, a "bill of materials" skills table, and projects laid out as numbered schematic sheets.

## Publish it on GitHub Pages (free, ~5 minutes)

1. **Create a new GitHub repo.** Go to github.com → New repository. Name it anything, e.g. `portfolio`. Keep it public. Don't initialize with a README (you already have one).

2. **Upload the files.** Easiest way — on the repo page, click "uploading an existing file" and drag in `index.html` and `README.md` from this folder. Commit directly to the `main` branch.

3. **Turn on Pages.** In the repo, go to **Settings → Pages**. Under "Build and deployment", set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`. Save.

4. **Wait ~1 minute**, then refresh that Settings → Pages screen — it'll show your live URL, something like:
   `https://<your-github-username>.github.io/portfolio/`

That's it — no hosting cost, no ads, no expiry.

### Optional: custom domain
If you later buy a domain (e.g. `mahdihachicha.dev`), add a `CNAME` file to the repo root with just the domain name in it, then point your domain's DNS to GitHub Pages per [GitHub's custom domain docs](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site).

## Add your resume

The "Download CV" button in the hero links to `resume.pdf`. Export your CV (the Word doc I made earlier) to PDF and add it to the repo root as `resume.pdf` — the link will then work automatically. If you skip this step, just delete that button from `index.html` (search for `Download CV`).

## Editing content later

Everything is in the one `index.html` file — no templating, no build tools. Search for the section you want to change (`<!-- PROJECTS -->`, `<!-- SKILLS -->`, etc.) and edit the text directly. Re-upload the file to GitHub (or `git push` if you're using the command line) and the live site updates automatically within a minute.
