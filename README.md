This repository demonstrates an issue loading assets using `vite-plugin-nodecg` version 2.0.0 or newer.

## Usage

- Install this repository as a NodeCG bundle
- Install dependencies: `npm i`
- Run the development server: `npm run dev`
- Run NodeCG and open the graphic at `<nodecg>/bundles/vite-nodecg-asset-loading-repro/graphics/index.html`.
  - If using `vite-plugin-nodecg` version `2.0.0-rc3` (set by default in this repository), this graphic will display an image.
  - If using `vite-plugin-nodecg` version `2.0.0` or `2.0.1`, this graphic will fail to display an image.
