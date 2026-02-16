# Dashboard File Documentation

This folder contains the main Power BI dashboard file used in the Sustainable Development Goals analytics project.

---

## File

sdg_dashboard.pbix

This is the fully interactive Power BI report analysing SDG-related indicators across South America from 2013 to 2023.

---

## Software Requirements

To open and interact with the dashboard you will need:

- Power BI Desktop (latest version recommended)
- Windows operating system

Download Power BI Desktop:
https://powerbi.microsoft.com/desktop/

---

## Dashboard Features

The report includes:

- Interactive country filtering (Brazil, Colombia, Peru)
- Time-series visualisations (2013–2023)
- Education completion analysis
- Unemployment trend monitoring
- GDP growth analysis
- Economic relationship modelling (scatter plot with regression trend line)
- Accessibility-optimised colour theme

---

## Accessibility Design

The dashboard supports inclusive visualisation through a colour-blind safe palette based on the Okabe–Ito design standard.

The theme file is located in:

../theme/okabe-ito-theme.json

This theme can be re-applied or modified within Power BI Desktop.

---

## Data Model Notes

Data has been:

- Cleaned and structured prior to visualisation
- Modelled to support time-series comparison
- Organised by country and year
- Prepared for interactive filtering

All metrics are aggregated at country level.

---

## File Usage

1. Download sdg_dashboard.pbix
2. Open using Power BI Desktop
3. Use slicers and visuals to explore indicators
4. Switch between standard and accessible viewing modes if required

---

## Exported Versions

Static versions of the dashboard are available in:

../exports/

These include:

- PDF version of the dashboard
- Screenshot previews

These are intended for quick viewing without Power BI.

---

## Purpose of This Folder

This folder contains the working Power BI dashboard file separate from exports, theme configuration, and documentation.
This structure reflects professional business intelligence repository organisation.
