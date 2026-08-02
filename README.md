# Your Portfolio Site — Setup Guide

This is a single file (`index.html`) with everything built in — no coding, no build tools, no installs needed.

## Step 1: Fill in your details

Open `index.html` in any text editor (even Notepad, TextEdit, or GitHub's own web editor — see Step 3) and replace anything inside `[BRACKETS]` with your real information:

- Your name, role, and one-line bio (top of the file, in the sidebar section)
- Email, GitHub, and LinkedIn links (sidebar bottom + Contact section)
- About paragraph(s)
- Experience entries (copy the whole `<div class="entry">...</div>` block to add more jobs)
- Projects (copy the whole `<article class="project">...</article>` block to add more projects)
- Skills tags

If you have a resume PDF, name it exactly `resume.pdf` and place it in the same folder as `index.html` — the "Download Résumé" button already links to it.

## Step 2: Create a GitHub repository

1. Go to [github.com](https://github.com) and log in (or create a free account).
2. Click the **+** icon top-right → **New repository**.
3. Name it exactly: `yourusername.github.io` (replace `yourusername` with your actual GitHub username — this exact naming is what makes GitHub Pages work automatically).
4. Set it to **Public**, then click **Create repository**.

## Step 3: Upload your files (no command line needed)

1. On your new repo's page, click **Add file → Upload files**.
2. Drag in `index.html` (and `resume.pdf` if you have one).
3. Scroll down and click **Commit changes**.

## Step 4: Turn on GitHub Pages

1. In your repo, go to **Settings → Pages** (left sidebar).
2. Under "Build and deployment", set **Source** to **Deploy from a branch**.
3. Set **Branch** to `main` and folder to `/ (root)`, then click **Save**.
4. Wait about 1–2 minutes. Your site will be live at:

   `https://yourusername.github.io`

## Editing later

Any time you want to update content, go back to the repo, click on `index.html`, click the pencil (✏️) icon to edit, make your changes, and commit. The live site updates automatically within a minute or two.

## Optional: custom domain

If you buy a domain (e.g. from Namecheap or Google Domains), you can point it at your GitHub Pages site under **Settings → Pages → Custom domain**. Let me know if you go this route and I can walk you through the DNS setup.
