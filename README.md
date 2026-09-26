# Personal Portfolio

My personal portfolio site: a single-page overview of who I am, what I've built, and how to reach me.

**Live site:** [rish-vish.github.io/Portfolio](https://rish-vish.github.io/Portfolio/)

## About

I'm Rishik Vishwakarma, a Computer Science + Data Science student at UW–Madison, originally from Lucknow, India. This site puts my resume, projects, experience, and contact info in one place. It's built to load fast, work well on mobile, and give visitors a clear picture in under a minute.

## What's in it

- **About:** who I am, where I'm from, and what I'm looking for
- **Experience:** DoIT IT Support and SuccessWorks, laid out as a timeline with photos
- **Projects:** P-31 NMR Dashboard, Student Performance Predictor, Internship Application Tracker, and Movie Budget vs. Box Office Analysis, each with links to the GitHub repo and live demo where there is one
- **Leadership:** ISS Advisory Board, Badminton Club, and India Students Association
- **Skills:** languages, data & ML libraries, and tools
- **Resume:** direct link to my latest resume PDF
- **Contact:** email (with a one-click copy button), LinkedIn, and GitHub

## Features

- Sticky sidebar navigation that highlights the section you're reading
- Light and dark mode: follows your system setting, with a toggle that remembers your choice
- Scroll-in animations, a reading progress bar, and count-up stats
- Hand-drawn SVG illustrations for each project card
- Click-to-enlarge photo lightbox (close with Esc)
- Respects `prefers-reduced-motion` for anyone who has animations turned off

## Tech

- **Plain HTML/CSS/JavaScript:** no framework, no build step
- **Hosted on GitHub Pages:** free, fast, and always in sync with `main`
- **Single file:** styles, scripts, and images are all inlined in `index.html`, so the first load is a complete page
- **Fonts:** Fraunces, Source Sans 3, and JetBrains Mono from Google Fonts

## Deploy your own copy

```bash
# 1. Clone
git clone https://github.com/Rish-Vish/Portfolio.git
cd Portfolio

# 2. Edit index.html: change the name, sections, and content to yours
#    and replace resume.pdf with your own

# 3. Push to a repo named <your-username>.github.io, OR enable GitHub Pages
#    under Settings → Pages for any repo, pointed at the main branch
```

## Contents

```
├── index.html    # Everything: content, styling, scripts, and images
├── resume.pdf    # Downloadable resume
└── README.md
```

## What I learned

- **Design for a specific audience with a specific goal.** Recruiters usually want to either read the resume or look at a project, and every design decision was about shortening the path to one of those.
- **Get feedback from people who do the job.** After talking with a software engineer at Salesforce, I rebuilt the site to drop a game theme that got in the way of the content and a "skill level" chart that didn't say anything real.
- **Single-file HTML is underrated.** With no dependencies, nothing breaks between now and whenever someone opens the site in three months.
