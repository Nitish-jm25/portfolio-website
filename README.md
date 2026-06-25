# Nitish Raj J M — Portfolio Website

A single-page portfolio built with React + Vite. No paid services required to deploy it.

---

## 1. Run it locally (optional, just to preview)

You'll need [Node.js](https://nodejs.org) installed (any recent LTS version).

```bash
npm install
npm run dev
```

Then open the URL it prints (usually `http://localhost:5173`).

---

## 2. Push this folder to GitHub

1. Go to [github.com/new](https://github.com/new) and create a new repository — e.g. `portfolio-website`. Leave it empty (no README, no .gitignore — you already have those here).
2. In this folder, run:

```bash
git init
git add .
git commit -m "Initial portfolio"
git branch -M main
git remote add origin https://github.com/Nitish-jm25/portfolio-website.git
git push -u origin main
```

(Replace the URL above with the one GitHub shows you after creating the repo.)

---

## 3. Deploy for free on Vercel

1. Go to [vercel.com](https://vercel.com) and sign up using your **GitHub account** — no credit card needed.
2. Click **"Add New… → Project"**.
3. Select the `portfolio-website` repo you just pushed.
4. Vercel will auto-detect it's a Vite project. Leave all settings as default.
5. Click **Deploy**. Wait ~1 minute.

You'll get a live URL immediately, something like:
`https://portfolio-website-xyz123.vercel.app`

---

## 4. Claim a clean free subdomain

1. In your Vercel project, go to **Settings → Domains**.
2. Type a custom subdomain you want, e.g. `nitishraj.vercel.app` (first-come-first-served).
3. Click **Add**. It's free and instant — no domain purchase needed.

Your site is now live at `https://nitishraj.vercel.app` (or whatever you chose), with free HTTPS automatically.

---

## 5. Future updates

Any time you change `src/Portfolio.jsx` and push to GitHub:

```bash
git add .
git commit -m "Update portfolio"
git push
```

Vercel automatically redeploys within a minute or two. No manual re-upload ever needed.

---

## Alternative free hosts (if you ever want options)

- **GitHub Pages** — free, gives you `nitish-jm25.github.io`. Needs an extra build step (`npm run build`, then deploy the `dist` folder to a `gh-pages` branch using a tool like `gh-pages` npm package).
- **Netlify** — same workflow as Vercel, free subdomain like `nitishraj.netlify.app`.

Vercel is recommended here since it has the smoothest zero-config experience for Vite projects.

---

## What's inside

- `src/Portfolio.jsx` — the entire site (single component, all sections, all styling)
- `src/main.jsx` — mounts the component to the page
- `index.html` — page shell + SEO meta tags
- `package.json` / `vite.config.js` — build configuration

No backend, no database, no API keys. The contact form opens the visitor's email client directly; the resume and your photo are embedded directly into the page so there's nothing else to upload separately.
