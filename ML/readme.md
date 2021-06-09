# Paddy Leaf Disease Dataset
The current dataset is constructed by the following open source Paddy Leaf Disease datasets:

* https://www.kaggle.com/shayanriyaz/riceleafs
* https://www.kaggle.com/vbookshelf/rice-leaf-diseases
* https://www.kaggle.com/minhhuy2810/rice-diseases-image-dataset

## Steps to generate the dataset
1. Download kaggle.json to use API for downloading dataset from kaggle (see https://www.kaggle.com/docs/api)
2. Use [Data Preprocessing.ipynb](Data%20Preprocessing.ipynb) to to preprocessing three datasets for multi class classification.
3. Use [EfficientNetB7_Model.ipynb](EfficientNetB7_Model.ipynb) to train the model and save the model
4. (Optional) Send the model to GCP and run the model via VM on cloud to create API for predict paddy leaf images (see https://github.com/Lemon-Drops-Bangkit/Paddy-Leaf-Disease-Detection-API-Cloud)
