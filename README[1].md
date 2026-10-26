# NEXUS Devtools (demo website)

A self-contained, responsive 4-page developer-tools demo website.

## Pages
- Overview
- Code Studio (simulated generation; no AI API)
- Developer Tools (real local JSON formatting; simulated bug detector and code explainer)
- Virtual Terminal (safe simulated commands only)

## Deploy to Vercel (beginner-friendly)
This is a static website and needs no build command.

1. Create/sign in to a GitHub account at https://github.com
2. Create a new repository named `nexus-devtools`.
3. In the repository, choose **Add file → Upload files**.
4. Extract this ZIP on your computer, then upload `index.html` and `vercel.json` from the extracted folder. Commit the files.
5. Sign in at https://vercel.com and choose **Add New → Project**.
6. Import the `nexus-devtools` GitHub repository.
7. If Vercel asks for settings, use **Framework Preset: Other**, leave Build Command blank, and set Output Directory to `.` (a single dot). Then deploy.
8. Vercel will show your public `.vercel.app` address.

No API key, database, or local coding setup is required.
