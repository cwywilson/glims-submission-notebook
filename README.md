[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/cwywilson/glims-submission-notebook/HEAD?labpath=glims_submission_notebook.ipynb)

## Overview
This repository contains a Jupyter notebook—**Prepare glacier outlines + centre-lines for submission to GLIMS**—that:

1. Repairs geometry and re-projects glacier outlines (1960 & 2023) and centre-lines.
2. Writes GLIMS-compliant Shapefiles ready for upload.
3. Logs processing steps to ease reproducibility.

📄 **Official guidelines:** [Submitting Data to GLIMS (PDF, 2020-02-06)](http://www.glims.org/MapsAndDocs/submitting_data_to_glims_2020-02-06.pdf)
<!-- GLIMS logo -->
<p align="center">
  <img src="https://www.glims.org/MapsAndDocs/glims_logo_smooth_small.png"
       alt="GLIMS – Global Land Ice Measurements from Space" width="240"/>
</p>
---

## Requirements
Create the conda environment and install dependencies with:

```bash
conda env create -f environment.yml
```

This provides Python 3.10 and all packages used in the notebook.
