# HMNIST

HAM10000 dataset or HMNISt dataset contains 10K skin cancer localization images along with the patient data providing their
metadata as well as classification for the cancer. The dataset was brought from https://www.kaggle.com/kmader/skin-cancer-mnist-ham10000/home. Given the dataset, I use both images and metadata with CNN/DNN combined model to predict cancer type based on 
the patient's skin cancer image and their demographics like age. The Jupyter notebook contains the code for keras model and
EDA / data processing to generate predctions. Overall, the model achieved 76%~78% accuracy without hyperparameter tuning. The next goal
for updating this repository is to improve the accuracy to 80% threshold.
Note that a full example is hosted on Google Colab with the link below.

### Google Colab link
hmnist: https://drive.google.com/open?id=19uGorOaoA1oaZfUadQr-7sQOoYPj5FFZ
