# Traffic Sign Classification
## Files Submitted
### Submission Files
>  The project submission includes all required files.

- Ipython notebook with code
- HTML output of the code
- A writeup report (either pdf or markdown)

## Dataset Exploration
### Dataset Summary
> The submission includes a basic summary of the data set.

Dataset contained three different datasets:

- **train.p ->** this file contains the dataset, which is used for training a neural network model.
- **valid.p ->** this dataset is used for validating the model trough training steps.
- **test.p ->** after the training step this dataset is used to test the trained model.
### Exploratory Visualization
>The submission includes an exploratory visualization on the dataset.

As we can see in executed source code.
````
Number of training examples = 34799
Number of testing examples = 12630
Image data shape = (32, 32, 3)
Number of classes = 43
````

**Note:** the number of classes is 43 because the train, validate and test dataset only contain 43 different German traffic signs.
For this project we use only two columns of datasets: features and labels
- Features: contains the images (32x32x3)

Labels: contains the Id of traffic sign
Each row of features a row in labels which determines the traffic sign classification.


<!--stackedit_data:
eyJoaXN0b3J5IjpbNTM4Mzc4OTA3LC02OTc5Njk1NTAsMTQzOT
E0ODA3M119
-->