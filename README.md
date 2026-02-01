# Be My Valentine

This is the small reactive HTML site intended to be published with GitHub Pages.

Files included:
- `index.html` — the page to publish.
- `404.html` — fallback that redirects to the index preserving the path (useful if you later add client-side routing).

To publish from the GitHub website:
1. Create a new repository:
   - Visit https://github.com/new
   - Repository name: be-my-valentine
   - Public (checked)
   - Leave "Initialize with a README" unchecked (we will upload files), or check it if you prefer.
   - Click "Create repository".

2. Upload the files:
   - In your new repository page click "Add file" → "Upload files".
   - Drag & drop `index.html`, `404.html`, and `README.md`.
   - Commit changes (Commit directly to the main branch).

3. Enable GitHub Pages:
   - Go to Settings → Pages (left sidebar).
   - Under "Build and deployment" / "Branch", select Branch: `main` and Folder: `/ (root)`.
   - Click "Save".
   - The site URL will appear at the top of the Pages settings (or it will be https://SUddz017.github.io/be-my-valentine/).

4. Wait ~30–60 seconds, then open:
   https://SUddz017.github.io/be-my-valentine/

If you prefer to use the command line (git + GH CLI):
1. Locally in the folder with the files:
   - git init
   - git add .
   - git commit -m "Initial commit: add site"
   - git branch -M main
   - gh repo create SUddz017/be-my-valentine --public --source=. --remote=origin --push
   (If you don't have gh: create the repo on GitHub.com, then run the git remote add + git push commands shown below.)
2. Or using git only (after creating the repo on GitHub):
   - git remote add origin https://github.com/SUddz017/be-my-valentine.git
   - git push -u origin main

Notes & quick checks
- Make sure the file is named exactly `index.html` (lowercase) at repository root.
- If you see a 404, confirm in Settings → Pages that branch is main and folder is root.
- External GIFs used in the page are loaded from Giphy; if you want everything local, download them and reference with relative paths.

Next steps I can do for you
- Guide you step-by-step while you complete the "Upload files" step in the web UI (tell me when you’re on the repo page).
- Verify Pages settings and the live site once you finish and share the repo URL or tell me you’ve enabled Pages.

Tell me: do you want to proceed now with the web UI upload? If yes, open https://github.com/new (or say "I'm ready") and I will guide you through each click.