# Data Science in Practice Cookiecutter Template
A cookiecutter template for a Python data science project, which creates a logical project structure with sections for data, notebooks, source code, and publications/reports, as below.

```
├── LICENSE
├── Makefile           <- Makefile with commands like `make data` or `make train`
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── processed      <- The final, canonical data sets for modeling.
│   ├── final          <- Final data ready for export.
│   └── raw            <- The original, immutable data dump.
│
├── docs               <- A default Sphinx project; see sphinx-doc.org for details
│
├── notebooks          <- Jupyter notebooks.
│   ├── prep           <- Notebooks used for cleaning, preparing and wrangling data.
│   ├── analysis       <- Core analysis notebooks.
│   └── final          <- Clean, final notebooks.
│
├── pubs               <- Analysis reports/publications
│   ├── tex            <- .tex files for pubs.
│   ├── figs           <- Pub/report figures.
│   └── data           <- Backup data associated with figs/tables in pubs.
│
├── environment.yaml   <- Environment specification/dependencies to help reproducibility.
│                         Generated with `conda env export > environmet.yaml`
│
├── src                <- Source code for use in this project.
│   ├── __init__.py    <- Makes src a Python module
│   │
│   ├── data           <- Scripts to download or generate data
│   ├── helpers        <- Other helper code.
│   └── viz            <- Visualisation/graphing code.
```
