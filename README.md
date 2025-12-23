# age-estimation-notebook

Short description

# age-estimation-notebook

This repository contains the analysis notebook and a minimal demonstration dataset used to reproduce parts of the modelling pipeline from the published work:

Constantinou, C., Chovalopoulou, M.-E., & Nikita, E. (2023). AgeEst: an open access web application for skeletal age-at-death estimation employing machine learning. Forensic Science International: Reports, 7, 100317. DOI: 10.1016/j.fsir.2023.100317

The models built using this workflow were deployed in the AgeEst web application. App source and deployment details are available at: https://github.com/cconsta1/AgeEst.git

Repository contents (root)
- `age_estimation_notebook.ipynb` — Jupyter notebook used in the analysis
- `age_dataset_sample.csv` — small sample CSV for demonstration only
- `LICENSE` — MIT license

Important notes
- The full Athens Collection dataset used for the published study is NOT included here. The included CSV is a small demo subset only.
- Some cells in the notebook assume a Colab environment (Google Colab helpers and `!pip` install commands). Review installation cells before running locally.

How to run
- Open the notebook in Google Colab (Colab badge included in the notebook) or run locally with Jupyter Lab/Notebook.

Citation
If you use the notebook or the models derived from it, please cite the paper above (DOI: 10.1016/j/fsir.2023.100317).

License
See `LICENSE` for licensing details (MIT).
