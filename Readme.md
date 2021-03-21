# 50.039 Deep Learning Small Project

Noorbakht Khan 1003827
<br/>
Ong Li-Chang 1003328
<br/>
Richard Pung 1003523

As part of our 50.039 Deep Learning Small Project, we are tasked to design a deep learning model, whose task is to assist with the
diagnosis of pneumonia, for COVID and non-COVID cases, by using X-ray images of patients.

We implemented two model architectures. The first is a multi-class classifier architecture in the multiclass_small_project_dataset_dataloader.ipynb file while the second consists of two stacked binary classifiers implemented in the binary_small_project_dataset_dataloader.ipynb file.

Both of the notebook files consists of a Simple and Complex CNN model which differs in the number of convolutional layers that we trained.

## Model names and explanation

### Multi-class Classifier Models:

1. `complex_model_multiclass.pth` --> pre-trained complex CNN model for Normal vs Infected COVID vs Non-infected COVID labels.

### Binary Classifier Models:

1. `complex_model1.pth` --> pre-trained complex CNN model for Normal vs Infected labels.
2. `complexmodel_2.pth` --> pre-trained complex CNN model for Infected COVID vs Non-infected COVID labels.

## Re-train model from scratch

To re-train the whole model from scratch for the multi-class classifier, run all the cells in the multiclass_small_project_dataset_dataloader.ipynb file.

To re-train the whole model from scratch for the two stacked binary classifiers, run all the cells in the binary_small_project_dataset_dataloader.ipynb file.

## Recreate exact trained model
