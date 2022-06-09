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

| Method             | MAE           | RMSE          | MSE           |
| ------------------ | ------------- | ------------- | ------------- |
| Baseline           | 0.108         | 0.3759        | 0.1413        |
| Item Based Memory  | 0.6825        | 0.7015        | 0.4921        |
| SVD                | 0.0918        | 0.1220        | 0.0149        |
| SOTA               | 0.0947        | 0.3522        | 0.1241        |

* All the miscellaneous illustrations are projected in the notebook themselves.
