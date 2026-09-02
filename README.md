# Worklist Website (No Microsoft/Azure Setup)

Worklist is a static website. It does **not** require Microsoft Entra, Azure, SharePoint, a backend server, Node.js, or API credentials.

## What it does
- Add, edit, prioritize, complete, and search tasks.
- Keep completed tasks as searchable history.
- Paste rough notes and extract proposed action items in the browser.
- Store tasks in the browser using `localStorage`.
- Export the full task ledger to `GPT To Do Database.csv`.
- Import that CSV later to restore or move the task list.

## Publish with GitHub Pages
1. Upload `index.html`, `app.js`, `styles.css`, and `.nojekyll` to the root of your GitHub repository.
2. In GitHub, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Choose your default branch (usually `main`) and `/ (root)`.
5. Save. GitHub will show the website URL after deployment.

## Important storage note
Tasks are stored in the browser on the device where you use Worklist. Clearing browser site data can remove them. Use **Export CSV** periodically as a backup. Import the CSV on another device/browser if you want to move your task history.

## No secrets
This version has no credentials, access tokens, Microsoft Graph configuration, or server-side components.
