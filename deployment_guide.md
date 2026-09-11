# 🚀 Complete Deployment Guide: HireAssess Assessment Portal

Because this is a **100% Zero-Backend, Client-Side Single Page Application (SPA)**, you can host and deploy it for **FREE** with instant global CDN speed in under 2 minutes.

---

## 📁 Files to Deploy

Your directory contains everything needed:
- `index.html` (The entire application: UI, engine, scoring, PDF generation, proctoring)
- `tcs_nqt_demo.json` (Official TCS NQT Mock)
- `infosys_demo.json` (Official Infosys Mock)
- `cognizant_genc_demo.json` (Official Cognizant AMCAT Mock)
- `ai_exam_generator_prompt.md` (AI Question Prompt Guide)

---

## ⚡ Option 1: GitHub Pages (Recommended & Easiest)

1. Create a new repository on [GitHub.com](https://github.com) (e.g., `placement-exam-portal`).
2. Push or upload all files (`index.html`, JSON files) to the repository `main` branch.
3. In GitHub, go to **Settings** > **Pages** (in left sidebar).
4. Under **Branch**, select `main` and folder `/ (root)`, then click **Save**.
5. Your website will be live at:
   `https://<your-username>.github.io/<repo-name>/`

---

## ⚡ Option 2: Vercel (1-Click Instant Deploy)

### Method A (Drag and Drop):
1. Go to [vercel.com](https://vercel.com) and log in.
2. Click **Add New** > **Project**.
3. Drag and drop your project folder (`placementexam`).
4. Click **Deploy**. Done!

### Method B (CLI):
```bash
npm install -g vercel
vercel
```

---

## ⚡ Option 3: Netlify (Drag and Drop)

1. Go to [app.netlify.com/drop](https://app.netlify.com/drop).
2. Drag and drop the `placementexam` folder into the browser.
3. Your site is live immediately on a free `.netlify.app` subdomain with SSL.

---

## ⚡ Option 4: Cloudflare Pages

1. Log into [dash.cloudflare.com](https://dash.cloudflare.com).
2. Go to **Workers & Pages** > **Create application** > **Pages** > **Upload assets**.
3. Upload your folder.
4. Instant global edge deployment on `*.pages.dev`.

---

## ⚡ Option 5: Local Offline Use (No Internet / Intranet Testing)

Double-click `index.html` on any machine, or serve via Python / Node:

```bash
# Python 3
python -m http.server 8080

# Or Node (npx)
npx serve .
```
Access at `http://localhost:8080`.
