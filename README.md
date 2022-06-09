# Project: Data Mining - Recommender Systems
### Course: DSC 291: Numerical Linear Algebra
### Instructor: Dr. Tsui-wei Weng

#### Instructions:
* Ensure that the following libraries are installed in python 3 environment:
  - scikit-learn
  - tensorflow
  - keras
  - surprise
  - pickle
  - pandas
  - numpy
  - matplotlib
  - gzip
  - json
  - math

* Import the dataset file: 'beeradvocate.json.gz' and the pickle files: 'train.infer' and 'test.infer' into the same directory as the .ipynb notebooks from the drive: https://drive.google.com/drive/folders/18gxZwG9pdgh4avjine5I5QllV8elSrXQ?usp=sharing
* Open collaborative_filtering_memory_item.ipynb and run all the cells of the notebook.
* Open collaborative_filtering_model_MF.ipynb and run all the cells of the notebook.
* Open beer_recommender_system.ipynb and run all the cells of the notebook.

#### Results:
| Method | MAE** | MSE | RMSE |
| --- | --- | --- | --- |
| Baseline | 0.108 | 0.1413 | 0.3759 |
| Item Based Memory | 0.6825 | 0.4921 | 0.7015 |
| SVD | 0.0918 | 0.0149 | 0.1220 |
| SOTA | 0.0947 | 0.1241 | 0.3522 |
