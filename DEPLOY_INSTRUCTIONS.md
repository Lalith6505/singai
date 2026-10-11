# GitHub Pages Deployment Instructions — SingAI Website & Privacy Policy

This directory (`C:\Users\lmada\OneDrive\Desktop\SingingApp\website\`) is completely self-contained and ready for immediate deployment on GitHub Pages.

---

## What is in this directory:
- `index.html` — High-converting, responsive single-page showcase website with an embedded, full Google Play compliant Privacy Policy at `#privacy`.
- `privacy-policy.html` — Standalone Privacy Policy page (for direct Play Console linking if desired).
- `.nojekyll` — Ensures GitHub Pages serves all assets and images without Jekyll preprocessing.
- `assets/` — Real app graphics (icon, feature banner, and 5 screenshots).

---

## Deployment Option 1: Existing `marinedx.github.io` Repository (Recommended)

1. Open your existing GitHub repository for **marinedx** on GitHub:
   `https://github.com/marinedx/marinedx.github.io` (or your Pages repo).
2. Create a folder named `singai` (or copy into the root).
3. Drag and drop the contents of this `website` folder into the repository.
4. Commit the changes (`git add .`, `git commit -m "Deploy SingAI website"`, `git push`).
5. Your website will be live instantly at:
   - **Showcase & Privacy Policy:** `https://marinedx.github.io/singai/`
   - **Direct Privacy Policy URL:** `https://marinedx.github.io/singai/#privacy` or `https://marinedx.github.io/singai/privacy-policy.html`

---

## Deployment Option 2: New Standalone Repository (e.g. `singai`)

1. Go to [GitHub](https://github.com/new) and create a new public repository named `singai`.
2. Push or upload all files from this `website/` directory into the repository.
3. In your repository on GitHub:
   - Go to **Settings** ➔ **Pages** (under Code and automation).
   - Under **Build and deployment** ➔ **Source**, select **Deploy from a branch**.
   - Under **Branch**, select `main` (or `master`) and folder `/ (root)`.
   - Click **Save**.
4. In ~60 seconds, your site will be live at:
   - `https://marinedx.github.io/singai/`

---

## URLs for Google Play Console:
- **Privacy Policy URL:** `https://marinedx.github.io/privacy-policy.html` (or `https://marinedx.github.io/singai/#privacy`)
- **Store Listing Website:** `https://marinedx.github.io/singai/`
