# Personal Portfolio

My personal portfolio site — a single-page overview of who I am, what I've built, and how to reach me.

**Live site:** [rish-vish.github.io/Portfolio](https://rish-vish.github.io/Portfolio/)

## About

I'm Rishik Vishwakarma, a Computer Science + Data Science student at UW–Madison. This site is where my resume, projects, and contact info live in one place — designed to load fast, work on mobile, and give visitors a clear picture in under a minute.

## What's in it

- **About me** — background, what I'm interested in
- **Projects** — the things I've built, with links to their GitHub repos and live demos
- **Resume** — direct download of my latest resume PDF
- **Contact** — links to my email, LinkedIn, and GitHub

## Tech

- Plain HTML/CSS/JavaScript — no framework, no build step
- Hosted on **GitHub Pages** — free, fast, always up to date with `main`
- Single-page design so first load is a full page render (no client-side routing)

## Deploy your own copy

```bash
# 1. Clone
git clone https://github.com/Rish-Vish/Portfolio.git
cd Portfolio

# 2. Edit index.html — change the name, sections, and content to yours

# 3. Push to a repo named <your-username>.github.io OR enable GitHub Pages
#    under Settings → Pages for any repo, pointed at the main branch
```

## Contents

```
├── index.html                       # Everything — content, styling, scripts
├── Rishik_Vishwakarma_Resume.pdf    # Downloadable resume
└── README.md
```

## What I learned

- How to design a personal site for a specific audience (recruiters) with a specific goal (either "read the resume" or "look at a project") — every design decision was about reducing time-to-that-goal.
- That single-file HTML is underrated. No dependencies means nothing breaks between now and when someone opens it in three months.
