# Fairfax Speeding Map

React app for viewing Fairfax County speeding hotspots and checking speeding ticket density along a selected route.

## Run locally

1. Install dependencies:

```bash
npm install
```

2. Create a `.env` file in the project root with:

```bash
REACT_APP_MAPBOX_TOKEN=your_mapbox_public_token_here
GENERATE_SOURCEMAP=false
```

3. Start the app:

```bash
npm start
```

4. Open `http://localhost:3000`.

## Included files

- `src/`: React app source
- `public/speeding_heatmap_data.geojson`: map data used by the app

## Not included

- raw datasets
- preprocessing scripts
- build output
- local notes
- private environment files
