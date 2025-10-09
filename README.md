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
    
  4. Unzip the data
       * This will create the ```data/``` directory with all the necessary ```.gpkg``` and ```.pt``` files.
    
       **Optional:** The ```data.zip``` file contains both the raw ```datacube_mpm.gpkg``` file and the final preprocessed PyTorch tensor files. Therefore, running the first script ```0 - prepare_dataset.ipynb``` is optional. If you wish to skip it, please use the following pre-processed data to run the Bayesian mpm models directly.

     
     ```data/dataset_train.pt```
     ```data/mineral_train.pt```
     ```data/dataset_test.pt```
     ```data/mineral_test.pt```
     ```data/scaler.pkl```


     
## 📦 Python dependencies listed in the ```requirement.txt```

Below are the main Python libraries used in this project:

| Category | Library | Link |
|-----------|----------|------|
| Core | numpy | [https://pypi.org/project/numpy](https://pypi.org/project/numpy) |
| Core | pandas | [https://pypi.org/project/pandas](https://pypi.org/project/pandas) |
| Core | scikit-learn | [https://pypi.org/project/scikit-learn](https://pypi.org/project/scikit-learn) |
| Core | torch | [https://pytorch.org/get-started/locally/#windows-prerequisites](https://pytorch.org/get-started/locally/#windows-prerequisites) |
| Geospatial | geopandas | [https://pypi.org/project/geopandas](https://pypi.org/project/geopandas) |
| Geospatial | shapely | [https://pypi.org/project/shapely](https://pypi.org/project/shapely) |
| Data augmentation | imbalanced-learn | [https://pypi.org/project/imbalanced-learn](https://pypi.org/project/imbalanced-learn) |
| Bayesian deep learning | bayesian-torch | [https://pypi.org/project/bayesian-torch](https://pypi.org/project/bayesian-torch) |
| Bayesian deep learning | pytagi | [https://github.com/lhnguyen102/cuTAGI](https://github.com/lhnguyen102/cuTAGI) |
| Utilities | matplotlib | [https://pypi.org/project/matplotlib](https://pypi.org/project/matplotlib) |
| Utilities | tqdm | [https://pypi.org/project/tqdm](https://pypi.org/project/tqdm) |
| Utilities | psutil | [https://pypi.org/project/psutil](https://pypi.org/project/psutil) |
| Utilities | fire | [https://pypi.org/project/fire](https://pypi.org/project/fire) |
