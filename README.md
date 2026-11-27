# Nashif's Kerala — 3D portfolio game

A drivable 3D portfolio for **Nashif Ali K**, digital marketing strategist from Malappuram, Kerala. You drive a Kerala autorickshaw through a golden-hour Kerala valley (river, bridges, coconut groves, paddy, hills), and each place is one part of the portfolio.

Built with [Three.js](https://threejs.org/) (r128) in a single `index.html` file. There is no build step.

## Places on the map

| Place | Section |
|---|---|
| Chaya Kada (ചായക്കട) | About me |
| University of Calicut | Education |
| Beegains Academy | Training & internship |
| Backwater jetty (കായൽ) | Client work |
| Paddy field (വയൽ) | Skills (knockable crates) |
| Market street (അങ്ങാടി) | Own brands: Kartova, Notiq, Moricaps |
| Cinema hoarding (സിനിമ) | Web & AI video |
| Petrol pump (പെട്രോൾ പമ്പ്) | Work contact + refuel |

## Controls

- **W A S D / arrow keys:** drive or walk
- **Phones:** touch and drag anywhere on the left side; the auto drives the way you drag
- **Shift:** boost while driving, run while walking
- **E:** get out of the auto and walk, or get back in
- **Space:** horn while driving, jump while walking
- **Enter:** open the place you're standing in
- **C** (or the View button): switch between outside and inside (driver's seat) view
- **R:** reset the auto to the start
- **Scroll:** zoom in or out
- **Minimap:** tap a place to jump there

Extras: a river with two drivable bridges, a backwater lake with houseboats, a vintage camper van with a campfire, swaying palms and grass that parts around the auto, a petrol system with a refill at the pump, night mode, monsoon rain, sound, and a "Simple view" for a quick 2D read.

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
npx serve .
```

## Deploy

It's a static site, so it works on Vercel, Netlify or GitHub Pages with no build settings. Point the host at the repo root.

## Add your contact details

Edit the `CONTACT` object near the top of the script in `index.html`:

```js
const CONTACT = {
  email: '',
  whatsapp: '',   // country code, no +
  instagram: '',
  linkedin: '',
  website: ''
};
```
