# HD_HAR
HD_HAR: Human activity recognition using Hyperdimensional Computing

## Instructions

### Dataset
 - https://www.dropbox.com/s/blxblngsl45vkh6/ucihar.pkl?dl=0

### Background
 - https://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

### Installing prerequisites.
 - pip install -r requirement.txt

### Run the application.
 - python HDC_model.py --app_ ucihar --iter_ 20 --dimension_ 10000

 - Different hyperparameters
    - 1.app_: Training and testing dataset
    -  2.iter_: Number of epochs for retraining
    -   3.dimension_: Dimension of hyper-vector using in HDC model
