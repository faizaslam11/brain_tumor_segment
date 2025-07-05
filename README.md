
## Brain Tumor Segmentation using ResNet + LSTM
### This project implements a brain tumor segmentation model using the BraTS 2020 dataset. It utilizes a combination of ResNet and LSTM for improved spatial and sequential learning.

#### How to Run the Model in Google Colab
##### Step 1: Open the Notebook
- Download and upload the .ipynb file from this repo to Google Colab.

##### Step 2: Mount Google Drive
- The notebook will prompt you to mount your Google Drive. This is used to save checkpoints during training.

##### Step 3: Upload Your Kaggle API Token
-Create a Kaggle account at https://www.kaggle.com if you don’t have one.
- Go to your Kaggle Account Settings and click "Create New API Token".
- A file named kaggle.json will download.
-Upload this file when prompted in the notebook to authenticate and download the dataset.

##### Step 4: Modify Parameters
- Update the following parameters in the notebook as needed:
- Change num_epochs = 30+
  You need to update this in two places
- subset_size = 100+ 
  You need to update this in three place

##### Step 5: Run All Cells
- Run the notebook cells in order.
The notebook will automatically:
- Download and preprocess the BraTS dataset
- Train the model
- Save checkpoints to Google Drive
- Plot training graphs
- Show true vs. predicted segmentation outputs
- Evaluate performance using Dice score, Hausdorff distance, and confusion matrix
###### Output
- Training and validation loss and Dice score plots
- Visual comparison of original, true mask, and predicted segmentation
- Per-class evaluation metrics suitable for research and reporting

