# Firehouse

Your Firehouse hub as a phone app, hosted free on GitHub Pages.

## Put it online
1. On github.com, click **New repository**. Name it (for example `firehouse`). Pick **Public** (free Pages needs public unless you have Pro). Create it.
2. Click **Add file > Upload files** and drag in everything in this folder: `index.html`, `data.json`, `manifest.json`, `icon-192.png`, `icon-512.png`, `README.md`. Click **Commit changes**.
3. Go to **Settings > Pages**. Under *Build and deployment* pick **Deploy from a branch**, branch **main**, folder **/ (root)**. Save.
4. Wait a minute or two. Your link appears at the top of that page: `https://<your-username>.github.io/<repo>/`.

Note: a public repo means anyone with the link can read `data.json`. Keep private details out, or use a private repo with a paid plan.

## Put it on your phone
1. Open the link on your phone.
2. iPhone (Safari): tap **Share > Add to Home Screen**. Android (Chrome): tap **⋮ > Add to Home screen** / **Install app**.

## Where your data lives
- First open loads `data.json` from the site. After that, changes are saved on that device (browser storage).
- Backup any time: gear menu > **Export data.json**. Restore: **Import data.json**.

## Optional: sync with GitHub
1. GitHub > **Settings > Developer settings > Personal access tokens > Fine-grained tokens > Generate new token**.
2. Repository access: **Only select repositories** > your Firehouse repo only.
3. Permissions: **Contents: Read and write**. Nothing else. Set an expiration.
4. In the app: gear menu > **GitHub sync…**. Enter owner (your username), repo, branch `main`, and the token. Tap **Save**.
5. **Sync now** saves your data to `data.json` in the repo. **Pull latest** replaces this device's data with the repo copy (asks first).

The token is stored only on that device and is never written into `data.json`. Don't share your screen while it's showing.
