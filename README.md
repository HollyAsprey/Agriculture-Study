# Your Name — Personal Site

A portfolio and project notebook for data science work in agriculture, landed estates, and natural capital.

Built as a static site — no frameworks, no build step. Just HTML, CSS, and a little JS.

## Structure

```
/
├── index.html              ← Home
├── about.html              ← About & skills
├── projects.html           ← Project listing
├── contact.html            ← Contact
├── projects/
│   ├── project-template.html   ← Copy this for each new project
│   └── [your-project].html
└── assets/
    ├── style.css
    ├── main.js
    └── images/             ← Put project charts/maps here
```

## Hosting on GitHub Pages

1. Create a repo named `yourusername.github.io` (or any repo name for a project page)
2. Push all files to the `main` branch
3. Go to **Settings → Pages → Source → main branch / root**
4. Your site will be live at `https://yourusername.github.io`

## Adding a New Project

1. Duplicate `projects/project-template.html` and rename it (e.g. `projects/defra-land-use.html`)
2. Fill in the title, category, tools, and write-up
3. Add a card entry in `projects.html` by copying the commented template block
4. Optionally add a card to `index.html` in the Latest Projects section

## Data Sources to Explore

- [Defra open data](https://www.data.gov.uk/organisation/department-for-environment-food-rural-affairs)
- [OS OpenData](https://osdatahub.os.uk/downloads/open)
- [UKCEH Land Cover Map](https://www.ceh.ac.uk/data/ukceh-land-cover-maps)
- [Copernicus/Sentinel satellite imagery](https://dataspace.copernicus.eu/)
- [Natural England](https://naturalengland-defra.opendata.arcgis.com/)
- [Rural Payments Agency](https://www.data.gov.uk/organisation/rural-payments-agency)
