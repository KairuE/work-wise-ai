# Work Wise AI

A modern, privacy-compliant job search website for Kenya, powered by AI and open data.

## Features
- 🔍 Search and filter jobs from top Kenyan job boards and company career pages
- 📄 Upload your resume and match jobs
- 📝 Track jobs you have applied to
- 🏢 Discover companies and their open positions
- 🌙 Beautiful, mobile-friendly dark UI
- ⚖️ Privacy-first: no user tracking, only public/open job data

## Tech Stack
- **Frontend:** React + Vite + Material UI
- **Backend:** Python job crawler (Google Custom Search API)

## Getting Started

### 1. Clone the repo
```sh
git clone https://github.com/yourusername/work-wise-ai.git
cd work-wise-ai
```

### 2. Install dependencies
```sh
npm install
```

### 3. Run locally
```sh
npm run dev
```
Visit [http://localhost:5173](http://localhost:5173) in your browser.

### 4. Deploy to GitHub Pages
- Edit `vite.config.js` and `package.json` as described in the Deployment section below.
- Then run:
```sh
npm run deploy
```

## Deployment (GitHub Pages)
1. Add to `vite.config.js`:
   ```js
   export default defineConfig({
     base: '/work-wise-ai/',
     // ...
   });
   ```
2. Add to `package.json`:
   ```json
   "homepage": "https://yourusername.github.io/work-wise-ai",
   "scripts": {
     "predeploy": "npm run build",
     "deploy": "gh-pages -d dist"
   }
   ```
3. Install gh-pages:
   ```sh
   npm install --save-dev gh-pages
   ```
4. Deploy:
   ```sh
   npm run deploy
   ```

## Credits
- Job data: Google Custom Search API, BrighterMonday, Corporate Staffing, Fuzu, MyJobMag, and public company career pages.
- UI: Material UI

---

