# Charles — Portfolio

My personal portfolio website: a single self-contained page introducing me as a Full Stack Software Engineer, showcasing my projects on an animated timeline, my skills as a visual logo grid, and how to reach me.

🌐 **Live site:** https://durandur.github.io/My-Portfolio/

## What's on the Page

- **Hero / intro** — headline ("Solving problems with software"), role, circular headshot photo, and quick navigation
- **Projects timeline** — my three real projects on a centered, animated timeline:
  - **API Project** — client-side travel budgeting app with live + historical currency conversion ([repo](https://github.com/DuranDur/Trip-Budget-APP) · [live](https://durandur.github.io/Trip-Budget-APP/))
  - **Study Session Planner** — full-stack TypeScript/Express study planner that prioritizes tasks by deadline urgency and importance ([repo](https://github.com/DuranDur/Study-Planner))
  - **Library Book Tracker** — personal library app for physical books, ebooks, and audiobooks ([repo](https://github.com/DuranDur/LibraryBook-Tracker) · [live](https://durandur.github.io/LibraryBook-Tracker/))
- **Skills grid** — visual logo grid of my stack: JavaScript, TypeScript, HTML5, CSS3, Node.js, Express, React, Git, PostgreSQL
- **Contact section** — email, LinkedIn, GitHub, and phone links

## Tech & Structure

| Aspect   | Detail                                              |
|----------|-----------------------------------------------------|
| Stack    | Plain HTML, CSS, JavaScript — no frameworks, no build step |
| Layout   | Single `index.html` with all CSS/JS and images inlined |
| Images   | Optimized to WebP (~40 KB total)                    |
| Hosting  | GitHub Pages                                        |

```
My-Portfolio/
├── index.html   # The entire site — markup, styles, scripts, and inlined assets
└── README.md
```

The timeline entries animate in as you scroll (via IntersectionObserver) and reset when scrolling back up so they replay. The layout is fully responsive — verified on desktop and mobile widths with no horizontal overflow.

## Viewing / Running Locally

It's a static page — just open `index.html` in a browser, or clone and serve it:

```bash
git clone https://github.com/DuranDur/My-Portfolio.git
cd My-Portfolio
npx serve .
# or
python3 -m http.server 8000
```

## Contact

- 📧 charlesdennis228@gmail.com
- 💼 https://www.linkedin.com/in/charles-dennis-b98314212
- 🐙 https://github.com/DuranDur
