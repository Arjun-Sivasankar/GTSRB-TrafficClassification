# GTSRB Traffic Sign Classification

Convolutional neural network for German traffic sign recognition on the GTSRB dataset, built as a course project in Advanced Methods in Data Analytics.

| File | What it does |
|---|---|
| `AMDA_Project.ipynb` | Data preparation, the model definition, training and evaluation |
| `predictions.csv` | Predictions written out for submission |

The interesting part of this dataset is not the accuracy on the training distribution. Traffic sign crops vary wildly in scale, brightness and viewpoint, and the class distribution is heavily skewed, so the work sits in augmentation, class balancing and per-class error analysis rather than in the architecture.

## Running it

Open `AMDA_Project.ipynb` in Jupyter. It expects the GTSRB training images and the label CSV in the working directory.
