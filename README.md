# Breast Cancer Classifier
This project consists of a series of models for classifying breast cancer mammograms as malignant or benign. The models are trained on a subset of the DDSM dataset of mammogram images and their corresponding labels. The models are split into two categories, with a notebook for each category, CNN-based models, and Vision Transformer-based models. The reason for this split is the different libraries required for training, and evaluating the models, that would otherwise conflict with each other.
1. The notebooks are pre-run, however, if the user wishes to reproduce the results, they must spin up a virtual environment through ```conda``` or ```venv```.
2. For each notebook, an appropriate list of requirements is provided in the `requirements.txt` file, which may be installed via the ```pip install -r requirements.txt``` command.
3. Additionally, the dataset must be downloaded from [Kaggle](https://www.kaggle.com/datasets/skooch/ddsm-mammography/data), and placed within a folder named ```data``` at the root of the repository.
4. Once the appropriate prerequisites are satisfied, the notebooks can be run by invoking ```jupyter notebook .```.
