# Germany Territory Map

## Quick Start

1. Upload all files in this folder to your web hosting
2. Open `index.html` (or `Germany_map_partitioned.html`) in a web browser
3. That's it!

## Files Included

- `index.html` / `Germany_map_partitioned.html` - Main application
- `kreise.geojson` - Landkreis boundaries
- `plz.geojson` - PLZ boundaries  
- `assignments_plz.csv` - PLZ assignments
- `assignments_landkreis.csv` - Landkreis assignments
- `company_counts_plz.json` - Company data
- `Broker addresses.csv` - Broker locations (optional)

## Deployment Options

See DEPLOYMENT.md for detailed instructions on:
- GitHub Pages (free, recommended)
- Netlify Drop (easiest)
- Vercel
- Any static hosting

## Features

- Interactive map with broker zones
- Partition zones into subzones
- Reassign PLZs or subzones
- Save/load state
- Company heat map
- All data processing happens in the browser (no server needed)
