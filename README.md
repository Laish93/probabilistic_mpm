# Probabilistic mineral prospectivity modelling with TAGI, BNNs, and MC Dropout

This repository contains the code and resources for the article "Probabilistic mineral prospectivity modelling with tractable approximate Gaussian inference."

# Installation

To reproduce the results presented in the paper, please follow these steps:

  1. We used Git LFS to store the data used in this study.
       * Download and install Git LFS from the official website: https://git-lfs.github.com
       * After installing, run the following command in the terminal to initialize Git LFS:
         ```git lfs install```
         
  2. Clone the repository
       * Clone this repository, and Git LFS will automatically detect the pointer file and download the large ```data.zip``` file during this process. This may take some time.
    
         ```git clone https://github.com/Laish93/probabilistic_mpm.git```
    
  3. Install dependencies
       * Install all the required Python libraries listed in the provided ```requirements.txt``` file.

## 📦 Python Dependencies

Below are the main Python libraries used in this project:

| Category | Library | Link |
|-----------|----------|------|
| Machine Learning | numpy | [https://pypi.org/project/numpy](https://pypi.org/project/numpy) |
| Machine Learning | pandas | [https://pypi.org/project/pandas](https://pypi.org/project/pandas) |
| Machine Learning | scikit-learn | [https://pypi.org/project/scikit-learn](https://pypi.org/project/scikit-learn) |
| Machine Learning | torch | [https://pypi.org/project/torch](https://pypi.org/project/torch) |
| Geospatial | geopandas | [https://pypi.org/project/geopandas](https://pypi.org/project/geopandas) |
| Geospatial | shapely | [https://pypi.org/project/shapely](https://pypi.org/project/shapely) |
| Data Augmentation | imbalanced-learn | [https://pypi.org/project/imbalanced-learn](https://pypi.org/project/imbalanced-learn) |
| Bayesian Deep Learning | bayesian-torch | [https://pypi.org/project/bayesian-torch](https://pypi.org/project/bayesian-torch) |
| Bayesian Deep Learning | pytagi | [https://pypi.org/project/pytagi](https://pypi.org/project/pytagi) |
| Utilities | matplotlib | [https://pypi.org/project/matplotlib](https://pypi.org/project/matplotlib) |
| Utilities | tqdm | [https://pypi.org/project/tqdm](https://pypi.org/project/tqdm) |
| Utilities | psutil | [https://pypi.org/project/psutil](https://pypi.org/project/psutil) |
| Utilities | fire | [https://pypi.org/project/fire](https://pypi.org/project/fire) |
