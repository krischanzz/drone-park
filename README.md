# Drone Park Website

GitHub Pages-ready static website for Drone Park.

## Files
- `index.html` — landing page
- `privacy.html` — privacy policy URL for App Store Connect
- `support.html` — support URL for App Store Connect
- `styles.css` — shared styles
- `appicon.png` — app icon used as logo/favicon

## Publish on GitHub Pages
1. Create a new GitHub repository.
2. Upload all files from this folder to the repository root.
3. In GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, choose:
   - **Source:** Deploy from a branch
   - **Branch:** `main` (or your default branch)
   - **Folder:** `/root`
5. Save.
6. Add your custom domain in GitHub Pages settings.
7. Point your domain DNS to GitHub Pages.

## Important before publishing
Replace the support email in `support.html`:
- `support@yourdomain.com`

## App Store URLs
Use these links in App Store Connect after deployment:
- Privacy Policy URL: `https://yourdomain.com/privacy.html`
- Support URL: `https://yourdomain.com/support.html`
