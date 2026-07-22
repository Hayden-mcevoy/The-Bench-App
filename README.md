# The Bench

The Bench is a basketball coaching hub. It is a searchable library of drills, set plays, coaching principles, articles and trusted coaching video channels, plus a practice plan builder. It runs entirely in the browser from a single HTML file, with no server and no install.

## Features

- 54 drills across shooting, ballhandling, passing, defence, rebounding, transition and conditioning, filterable by skill, level and duration.
- 28 set plays with court diagrams, including baseline inbounds, sideline inbounds and zone attacks.
- 11 offensive and defensive principles, each with the rules to install at the start of the season and the counters that answer them.
- 17 coaching articles and 21 trusted coaching video channels, with a Watch link matched to every item.
- Practice Plan Builder with a timed schedule, an "adapt on the fly" panel for extra time, print or save as PDF, and download.
- Like and dislike on every item, plus Liked and Recently Used tabs.
- Downloads: save any drill, play, principle or plan as a clean, printable file.

## Usage

Open `the-bench.html` in any modern web browser. That is all. Nothing to install.

## Live demo (GitHub Pages)

Once the repository is on GitHub, you can host it for free so anyone can use it from a link:

1. On GitHub, open the repository and go to **Settings**, then **Pages** (left sidebar).
2. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
3. Choose the **main** branch and the **/ (root)** folder, then click **Save**.
4. Wait about a minute, then your app is live at:
   `https://YOUR-USERNAME.github.io/the-bench/`

The `index.html` page in the repository automatically redirects to `the-bench.html`, so the short link above just works.

## Notes

- Everything lives in the single HTML file. Likes, plans and recently used items are saved locally in the browser (localStorage), so they are per device for now.
- Advanced content is adapted from publicly documented professional and collegiate programs, with sources listed on each item.
- This is a prototype.

## Tech

Plain HTML, CSS and JavaScript in one file. Fonts load from Google Fonts. No build step and no dependencies.
