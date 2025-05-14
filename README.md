## Overview
This repository contains a Jupyter notebook—**Prepare glacier outlines + centre-lines for submission to GLIMS**—that:

1. Repairs geometry and re-projects glacier outlines (1958 & 2023) and centre-lines.
2. Writes GLIMS-compliant Shapefiles ready for upload.
3. Logs processing steps to ease reproducibility.

## Requirements
Python ≥3.9 with `geopandas`, `shapely`, and `fiona`.  
Run `pip install -r requirements.txt` if you add one.

## Usage
```bash
jupyter notebook "GLIMS format for submitting.ipynb"
