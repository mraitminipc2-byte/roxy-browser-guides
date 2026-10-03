# Roxy Browser Guides — written companion to MR AIT's video course

A static blog that turns the YouTube playlist **["how to use Roxy browser"](https://www.youtube.com/playlist?list=PLxY412qgkijKLUO1Gplz2q0MyCQC59Vnt)** by [MR AIT](https://www.youtube.com/@mrait) into written, step-by-step guides — with the original videos embedded in every lesson.

## Lessons

1. [Why Roxy Browser Is My Top Pick Now](guides/why-roxy-browser.html) — overview of the tool and the workflow
2. [How to Use Roxy Browser: The Complete Walkthrough](guides/how-to-use-roxy-browser.html) — installation, profiles, proxies, extensions, teams, synchronizer, API
3. [How to Get a Free Proxy (Step 1)](guides/free-proxy-guide.html)
4. [Antidetect Browser Explained (Step 2)](guides/antidetect-browser-explained.html)
5. [How to Use an Antidetect Browser (Step 3)](guides/how-to-use-antidetect-browser.html)
6. [Create a Windows 10 Computer: VM Setup (Step 4)](guides/windows-10-vm-setup.html)
7. [Create an iPhone Device Profile (Step 6)](guides/iphone-device-profile.html)

## How the site works

Pure static HTML + one CSS file — no build step, no JavaScript frameworks, no external dependencies. Hosted with **GitHub Pages**.

- `index.html` — course home with all lesson cards
- `guides/*.html` — one page per video: embedded player + written guide
- `css/style.css` — the whole stylesheet
- `sitemap.xml`, `robots.txt` — SEO basics
- `404.html` — GitHub Pages friendly not-found page

## Editing a lesson

Open the corresponding `guides/<slug>.html` and edit the HTML directly — each page is self-contained. Re-run the generator script (in the private workspace, not the repo) if lessons are added or reordered.

## Credits & disclaimer

All videos are © [MR AIT](https://www.youtube.com/@mrait); this site is a written study companion that embeds them via YouTube's official player. Educational content only — follow every platform's terms of service and your local laws.
