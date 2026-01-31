# China-NDVI
https://code.earthengine.google.com/c2a2f0ac41eeb8350685efcfd487bf06
National NDVI Monitoring & Vectorization Tool
A cloud-based open-source GIS application designed for national-scale NDVI (Normalized Difference Vegetation Index) visualization, vectorization, and data export. Built with Google Earth Engine (GEE) and JavaScript, this tool simplifies vegetation cover analysis to support environmental monitoring, ecological planning, and policy-making.
Key Features
National NDVI Visualization: Load seasonal NDVI data (2021-2023) derived from MODIS satellite imagery, with color-coded classification for intuitive vegetation cover assessment.
National Vectorization: Convert raster NDVI data to vector polygons, categorized into five vegetation cover grades (non-vegetated to high coverage).
Provincial-Level Analysis: Select specific provinces to load targeted NDVI data and export results for local-scale research.
User-Friendly Interface: Dual-panel layout with a clear NDVI legend (top-right) and functional control panel (bottom-right), ensuring unobstructed map interaction.
Open-Source & Accessible: Built with free tools (GEE, GitHub) and supports data export to Google Drive for further analysis.
NDVI Classification
The tool classifies NDVI values (0-1) into five vegetation cover grades:
0.0-0.2: Non-vegetated (Bare land/Desert) - #d73027
0.2-0.4: Low coverage (Sparse vegetation) - #fdae61
0.4-0.6: Medium coverage (Grassland/Farmland) - #fee08b
0.6-0.8: Medium-high coverage (Shrubs/Forests) - #e6f598
0.8-1.0: High coverage (Dense forests) - #66c2a5
Workflow
Data Preparation: Integrates MODIS NDVI imagery and simplified national/provincial boundary data.
Processing: Filters, normalizes, and averages data to generate seasonal NDVI datasets.
Interaction: Select year/season, load national/provincial NDVI, or generate vectorized layers.
Export: Authorize Google Drive to export provincial NDVI data as TIFF files for offline use.
Tech Stack
Google Earth Engine (GEE): Satellite data processing and cloud computing.
JavaScript (GEE API): Core function development (data loading, vectorization, export).
GEE UI Widgets: Frontend interface construction (panels, buttons, selectors).
GitHub: Open-source hosting and version control.
Usage
Run the application in GEE Code Editor.
Select a year (2021-2023) and season to load national NDVI data.
Use the "Load National Vectorization Layer" button to view classified vector polygons.
Select a province from the dropdown to load targeted data.
Export data via the "Export Current Region NDVI" button (requires Google Drive authorization).
Limitations & Future Improvements
Current Limitations: Static data (2021-2023), 10km vectorization resolution, and Google Drive export dependency.
Future Plans: Integrate real-time NDVI updates, add adjustable resolution settings, support multi-language interfaces, and implement an interactive chatbot for user guidance.
This tool follows a replicable framework, allowing adaptation to other regions or vegetation indices (e.g., EVI) with minimal modifications. Contributions and feedback are welcome to enhance functionality and accessibility.
