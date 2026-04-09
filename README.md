# Bhakti Shelke — Portfolio + HTML Agent

> AI Engineer & Data Scientist · New York, NY

Live site → **[bhaktishelke.github.io](https://bhaktishelke.github.io)**  
Agent tool → **[bhaktishelke.github.io/agent](https://bhaktishelke.github.io/agent)**

---

## What's in this repo

| File | What it is |
|------|-----------|
| `index.html` | Portfolio website — dark, editorial design with projects, experience, and contact |
| `agent.html` | HTML → Website Agent — paste HTML, preview live, improve with Claude AI |
| `README.md` | This file |

---

## Tech stack

The portfolio is a **zero-dependency single-file HTML site**:

- **Fonts** — Syne (display) + DM Sans (body) + DM Mono (code) via Google Fonts
- **Animations** — Pure CSS scroll-reveal + keyframe animations
- **No frameworks** — vanilla HTML, CSS, JS only
- **No build step** — open `index.html` directly in any browser

The agent tool (`agent.html`) calls the **Anthropic Claude API** to rewrite HTML on demand.

---

## Deploy to GitHub Pages (3 steps)

### Step 1 — Fork or clone this repo
```bash
git clone https://github.com/YOUR_USERNAME/YOUR_USERNAME.github.io.git
```

### Step 2 — Copy the files into your repo
```bash
cp index.html agent.html README.md YOUR_USERNAME.github.io/
cd YOUR_USERNAME.github.io
git add .
git commit -m "Add portfolio and agent"
git push origin main
```

### Step 3 — Enable GitHub Pages
1. Go to your repo on GitHub
2. Click **Settings** → **Pages**
3. Under "Branch", select `main` and `/ (root)`
4. Click **Save**

Your site will be live at `https://YOUR_USERNAME.github.io` in ~60 seconds.

---

## Customising the portfolio

Open `index.html` and update:

- **Line 1** — update `<title>` with your name
- **Hero section** — update name, tagline, and status badge
- **Projects section** — replace project cards with your own projects and GitHub links
- **Experience section** — update companies, roles, and bullet points
- **Contact section** — add your real email and social links
- **Stats** — update the hero stat numbers (years, projects, impact)

---

## Using the Agent

Open `agent.html` (or visit `/agent`):

1. Click **Load My Portfolio** to pull in your `index.html` automatically
2. Click **▶ Preview** to see it live in the browser frame
3. Switch to **AI Improve** tab → describe what you want changed
4. Hit **✦ Improve with Claude** → Claude rewrites the HTML
5. Click **✓ Apply + Preview** to see the result
6. **⬇ Download** to save the updated file

> **Note:** The AI Improve feature requires an Anthropic API key to be configured in your environment. The preview and download features work without any API key.

### Quick prompts to try:
- `"Add a floating particle animation to the hero background"`
- `"Add a dark/light mode toggle button to the nav"`
- `"Make the project cards flip on hover to reveal more detail"`
- `"Add a scroll progress bar at the top of the page"`
- `"Change the color accent from purple to electric cyan"`

---

## Keyboard shortcuts

| Shortcut | Action |
|----------|--------|
| `Ctrl/Cmd + Enter` | Render preview |

---

## License

MIT — feel free to use, fork, and customise.

---

*Built with Claude · April 2026*
