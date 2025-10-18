# EfficientNetB3 Food Classification with Similar-Class Handling

A reproducible pipeline for classifying Indian food images using **EfficientNetB3**, with enhanced data augmentation and focused fine-tuning for commonly confused classes. The pipeline includes Test-Time Augmentation (TTA), simple ensembling, calibrated confidences, and comprehensive analysis tools (confusion matrix, ROC/PR curves, etc.).

## Features
- **EfficientNetB3 Backbone**: High performance with a regularized head for classification.
- **Aggressive Data Augmentation**: Tuned for small inter-class differences to boost model robustness.
- **Similar-Class Aware Weighting**: Targeted fine-tuning for classes that are commonly confused with each other.
- **Test-Time Augmentation (TTA)**: For improved predictions by leveraging augmented versions of input images.
- **Ensembling**: Simple ensemble averaging for final predictions.
- **Comprehensive Metrics**: Includes Top-K accuracy, confusion matrix, ROC curves, and Precision-Recall (PR) curves for detailed evaluation.

## Dataset
The dataset used for training and evaluation is the **Indian Food Images Dataset** available on Kaggle. It contains images of various Indian dishes, making it ideal for food classification tasks.  
[Link to Dataset](https://www.kaggle.com/datasets/iamsouravbanerjee/indian-food-images-dataset)
