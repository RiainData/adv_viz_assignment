# adv_viz_assignment

NOTE: rename local file pathway to render the dashboard. 

This is a A lightweight, front‑end–only dashboard for exploring Brooklyn Museum ticket sales.
Built with HTML + CSS, D3.js for data wrangling, and Plotly.js for the five interactive charts.

To reproduce

1. Clone the repo
2. Open the project in a code editor
3. Add a Mapbox token if you want to customize the basemap.
4. Open with a service like VSCODE live server to previwe the dashbaord. 

Further notes:
Data Ingestion: through a JSON array from a cleaned json file. Raw data is not provided, due to privacy concerns around PII's. 
Filtering: user choices (events, modes, date range) are applied in the browser (Array.filter). The charts re‑draw instantly—no back‑end round‑trips.

