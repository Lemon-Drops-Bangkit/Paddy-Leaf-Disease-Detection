# Paddy Leaf Disease Dataset
The current dataset is constructed by the following open source Paddy Leaf Disease datasets:

* https://www.kaggle.com/shayanriyaz/riceleafs
* https://www.kaggle.com/vbookshelf/rice-leaf-diseases
* https://www.kaggle.com/minhhuy2810/rice-diseases-image-dataset

## Steps to generate the dataset
1. Download the datasets listed above
2. Use [Splitting Dataset.ipynb](Splitting%20Dataset.ipynb) to split train/validation dataset on rice-leaf-diseases and rice-diseases-image-dataset/LabelledRice before handling.
3. Use [Data Preprocessing.ipynb](Data%20Preprocessing.ipynb) to to combine the three datasets for multi class classification.