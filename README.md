# Print Estimator

A single-file web app for costing printed stationery (letters, envelopes, booklets, passbooks, vouchers and multipurpose documents) and automating BOQ / tender pricing from Excel.

## Features
- Upload a tender BOQ Excel and get a rate for every costable item
- Product-type templates with editable default values (paper, GSM, size, ups, plates, printing, CPF, transport, profit)
- Paper-type dropdown with editable rates
- Items marked "Sample Required" or "Trading Product" show NA
- Annual quantity divided by 12, minimum wastage of 250 sheets (or 3%)
- Export the current item as a formatted costing sheet in Excel

## Run locally
Open `index.html` in a browser. It needs internet for the SheetJS and ExcelJS CDN scripts. No build step, no backend, no API keys.

## Deploy with GitHub Pages
Repo **Settings → Pages → Deploy from a branch → `main` / `(root)`** → Save.
Live at `https://<your-username>.github.io/print-estimator/`.
