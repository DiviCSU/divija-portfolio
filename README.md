# Divija Rajaraman — Developer Portfolio

A responsive React + Vite portfolio with an identical layout in light and dark themes, project case-study pages, experience, skills, leadership, education, conferences, and contact information.

## Run locally

Install Node.js 20+ and then:

```bash
npm install
npm run dev
```

Open the local URL printed by Vite (usually http://localhost:5173).

## Customize before publishing

1. Edit `src/data.js` to update all career content and profile links.
2. Set `profile.github` to your actual GitHub profile URL. No GitHub URL has been guessed.
3. Add your portrait to `public/photos/portrait.jpg`, then set `profile.photo` to `/photos/portrait.jpg`.
4. Add screenshots and approved project links to project detail pages if desired.
5. Review the three university campus roles, GHC details, credential statuses, metrics, and employer-related descriptions before publishing.
6. Replace `public/Divija_Rajaraman_Resume.pdf` when your resume changes. **The included resume contains personal contact information.** Remove or edit it if you don't want those details public.
7. Review all content in `src/data.js` for confidentiality and accuracy. Never upload private company code or internal screenshots.

## GitHub

```bash
git init
git add .
git commit -m "Build personal developer portfolio"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
git push -u origin main
```

Create an empty GitHub repository first, and replace `YOUR_USERNAME` and `YOUR_REPO` with your real values.

## Deploy to Vercel

1. Sign in to Vercel with GitHub.
2. Select **Add New > Project** and import the repository.
3. Framework preset: **Vite**. Build command: `npm run build`. Output directory: `dist`.
4. Deploy. Vercel will generate a `*.vercel.app` URL.
5. Future pushes to `main` will trigger deployments when the Git integration is configured.

The static portfolio does not require a database or API key. Check Vercel's current Hobby-plan terms for eligibility and usage restrictions.

## Navigation

The site is a single-page portfolio. Project cards open hash-based detail views (`#/project/project-id`) so links work without server-side routing rules.
