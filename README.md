# Nazia Afrin | Portfolio

Personal portfolio site for Nazia Afrin, Data Analyst and Junior Data Engineer based in Sydney.


## About

An interactive, single-page portfolio built to give recruiters a quick look at my experience, results and skills. It uses 3D scenes to show how I work with data: raw records moving through a Medallion pipeline, before-and-after results from my time at BRAC IT Services, and my path from Dhaka to Sydney.

## What's on the page

- **Medallion pipeline (3D):** particles rise from a raw Bronze layer, get cleaned in Silver and land in an ordered Gold grid. Drag to rotate.
- **Results chart (3D):** before-and-after bars for report run time, query speed and processing efficiency.
- **Why me:** four flip cards, each with a claim on the front and the proof on the back.
- **Career path (3D):** milestones from 2022 to today, ending at the next step.
- **Projects:** Medical Data Warehouse on Azure, and Power BI dashboards.
- **Skills globe (3D):** a spinnable globe of tools, grouped by area.
- **Contact:** a 3D business card that flips to show my details.

The page works on phones and respects the "reduce motion" setting.

## Built with

- HTML, CSS and plain JavaScript (no framework, no build step)
- [three.js](https://threejs.org/) r149 for the 3D scenes
- Google Fonts: Fraunces, Inter and JetBrains Mono

## Project structure

```
.
├── index.html       # the whole site: markup, styles and scripts
├── three.min.js     # three.js library
├── images/          # illustrations used on the page
│   ├── flow.webp
│   ├── layers.webp
│   ├── dashboard.webp
│   └── network.webp
└── .nojekyll        # tells GitHub Pages to serve files as they are
```

## Run it locally

Opening `index.html` directly works in most browsers. For the most reliable result, serve the folder with a small local server:

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Deploy to GitHub Pages

1. Push these files to the `main` branch, with `index.html` at the top level.
2. Go to **Settings → Pages**.
3. Set Source to **Deploy from a branch**, choose `main` and `/(root)`, and save.
4. The site goes live within a couple of minutes.

To update the site, replace `index.html` (or any image) and commit. GitHub Pages redeploys on its own.

## Contact

- Email: nowshinwork3247@gmail.com
- LinkedIn: [linkedin.com/in/naziaafrin](https://linkedin.com/in/naziaafrin)
- GitHub: [github.com/Nowshin021](https://github.com/Nowshin021)

## Credits

three.js is © three.js authors and released under the MIT License.
