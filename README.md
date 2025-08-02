## Face Recognition using Data Analysis Techniques

This project implements a face recognition system using the ORL face dataset. It applies dimensionality reduction and classification techniques to identify individuals based on facial images.

### Contents

* `ORL/` — contains the face image dataset.
* `facerecognitionLDA.ipynb`  — contain the implementation code.

### Workflow

1. **Feature Extraction**:
   Linear Discriminant Analysis (LDA) is used to reduce dimensionality and maximize class separability.

2. **Classification**:
   The reduced features are evaluated using:

   * Support Vector Machine (SVM)
   * Random Forest
