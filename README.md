# cancer-detection
University of Colorado, Boulder DTSA 5511: Introduction to Deep Learning
Mini project - Kaggle competition

This project is part of the Kaggle competition (https://www.kaggle.com/competitions/histopathologic-cancer-detection/overview) that consists of creating and training a model to accurately predict the likelihood that an image of a pathology scan contains a tumor. The final model used transfer learning to leverage the MobileNetV2 model and add layers after it. Due to limited GPU resources, several measures were taken to reduce training time as much as posisble without sacrificing performance. A final model was chosen out of 3 with various hyperparameters tuned. This resulted in a validation AUC of 92%.