# Building and Analyzing Unit Hydrograph

This notebook explains how to derive a DEM-based unit hydrograph and how we can analyze the generated hydrograph directly with Python, to interpret the rising limb, peak flow and recession limb that are valuable to deepen our understanding of a flow in a channel.

## Tools & Technologies

- Python (Jupyter Notebook)
- [GRASS GIS](https://grass.osgeo.org/) (via `grass.jupyter` and scripting interface)
- Digital Elevation Model (DEM)
- Hydrologic Modeling module within GRASS

## Project Structure

```bash
unit-hydrograph/
├── dataset/
├── notebooks/
├── references/ 
├── results/                    
├── README.md             
