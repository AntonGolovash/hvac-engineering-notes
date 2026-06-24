# HVAC Engineering Notes

Static personal engineering website for independent notes on heat pumps, ventilation, cooling, indoor air quality and HVAC control logic.

The site is designed as a calm technical knowledge base and personal engineering portfolio. It is not an online shop and does not use tracking scripts, cookies, external analytics or a build system.

## Folder structure

```text
/
|-- index.html
|-- about.html
|-- heat-pumps.html
|-- ventilation-co2.html
|-- cooling.html
|-- case-studies.html
|-- contact.html
|-- cases/
|   `-- heat-pump-water-temperature-control.html
|-- assets/
|   |-- css/
|   |   `-- style.css
|   |-- js/
|   |   `-- main.js
|   |-- images/
|   |   `-- placeholder-readme.txt
|   |-- diagrams/
|   |   `-- placeholder-readme.txt
|   `-- pdf/
|       `-- placeholder-readme.txt
|-- README.md
`-- .gitignore
```

## Preview locally

Open `index.html` directly in a browser. No install step, local server or build command is required.

The site can also be previewed with any simple static file server if desired, but the links are written to work from local files.

## Editing pages

Each page is plain HTML and can be edited manually:

- `index.html` is the home page.
- Topic pages are `heat-pumps.html`, `ventilation-co2.html` and `cooling.html`.
- `case-studies.html` lists published case studies.
- Individual case studies live in `cases/`.
- Shared styles live in `assets/css/style.css`.
- Shared navigation behavior lives in `assets/js/main.js`.

When adding a new case study, create a new HTML file under `cases/`, then add a card and link to it from `case-studies.html`.

## Adding PDFs

Place downloadable PDF files under `assets/pdf/`.

The first case study already includes a visible PDF download button for:

```text
assets/pdf/heat-pump-water-temperature-control-case-study.pdf
```

The PDF itself can be added later after diagrams and final technical formatting are complete.

## Deployment

This repository is ready for static hosting.

For GitHub Pages, enable Pages in the repository settings and deploy from the default branch after the pull request is merged.

For Cloudflare Pages, connect the repository and use the project root as the output directory. No build command is required.
