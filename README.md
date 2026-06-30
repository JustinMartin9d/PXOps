# Shoreside Analytics Portal Shell

Static front-end shell for a neutral shoreside analytics portal.

## Included workflows

1. Port & Crew Arrival Alignment Verification
2. Crew Assignments & Flight Optimization
3. Staffing Forecast

Each landing-page card opens a workflow page with instructions and three Excel upload slots. The upload controls currently validate `.xlsx` and `.xls` files in the browser. The Run Analysis button is a placeholder that can be connected to a Python backend later.

## Files

- `index.html`: Complete static portal with embedded CSS and JavaScript.

## Hosting note

This shell can be hosted on GitHub Pages as a static site. To run Python analysis from the upload buttons, connect the front end to a backend such as Flask, FastAPI, Streamlit, Dash, Azure App Service, Render, or an internal server.
