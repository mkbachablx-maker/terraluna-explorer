# TerraLuna Explorer

TerraLuna Explorer is a browser-based prototype for exploring terrestrial analog sites that may help prepare for lunar and Martian missions. It presents four example Earth sites, illustrative environment comparisons, a simple field-test planner, and links to public NASA data portals.

## Project files

- `index.html` — page structure and the five views: Home, Map Explorer, Compare Studio, Mission Simulator, NASA Datasets, and About.
- `styles.css` — responsive dark-space theme and layout.
- `app.js` — site examples, Leaflet map, tab navigation, comparisons, and simulator interactions.

## Run the site

Open `index.html` in a modern browser. An internet connection is needed for Leaflet, fonts, map tiles, and linked data portals.

## Publish with GitHub Pages

1. Create a **public** GitHub repository.
2. Upload `index.html`, `styles.css`, and `app.js` to the repository's top level, then commit the files.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, then select the `main` branch and `/(root)` folder and save.
5. When the deployment finishes, GitHub will show the public site address in the Pages settings.

## Data and prototype notes

The dataset catalog links to public sources including LROC, HiRISE, and NASA Earthdata. The site-match scores, comparison values, and equipment recommendations in this prototype are illustrative examples for exploration planning; they are not validated scientific measurements or mission specifications. Verify and document the NASA data and research used in any final challenge submission.

## Credits

- Map library: [Leaflet](https://leafletjs.com/)
- Map tiles: [OpenStreetMap](https://www.openstreetmap.org/copyright)
- Featured data portals: [LROC](https://wms.lroc.asu.edu/lroc), [HiRISE](https://www.uahirise.org/), and [NASA Earthdata](https://earthdata.nasa.gov/)
