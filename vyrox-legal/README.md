# VYROX legal pages

Files:
- `index.html` — landing page with links to both policies
- `terms.html` — Terms of Service
- `privacy.html` — Privacy Policy

## Details already filled in
- Contact: `brke5335@gmail.com`
- Bot hosting: `Orihost`
- Moderation-record retention: up to 90 days from creation

## Required checks before publishing
1. Identify the actual database or persistent storage provider (if any) and update `privacy.html`. Orihost is the bot host; do not assume it is also the database provider.
2. Inspect the deployed bot code/configuration and make the message-content paragraph precise: does the bot read message content, store it, or neither?
3. Set actual retention periods for server configuration, diagnostic/technical logs, and backups. The 90-day period in the draft applies only to moderation records.
4. Replace `[YOUR GOVERNING JURISDICTION]` in `terms.html` after deciding the appropriate governing law; consider legal advice.
5. Confirm that every listed data category, feature, and provider matches the live bot. These are practical drafts, not legal advice.

## Publish with GitHub Pages
1. Create a public GitHub repository named `vyrox-legal` (or another name you prefer).
2. Upload `index.html`, `terms.html`, `privacy.html`, and `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
5. Select branch `main` and folder `/(root)`, then click **Save**.
6. Wait for the Pages deployment to finish. GitHub notes that publishing can take several minutes.

Your URLs will be:
- `https://YOUR-GITHUB-USERNAME.github.io/vyrox-legal/`
- `https://YOUR-GITHUB-USERNAME.github.io/vyrox-legal/terms.html`
- `https://YOUR-GITHUB-USERNAME.github.io/vyrox-legal/privacy.html`

Use the Terms and Privacy URLs in Discord Developer Portal → your VYROX application → General Information. GitHub Pages sites are publicly accessible; do not put secrets, tokens, or private bot data in this repository.
