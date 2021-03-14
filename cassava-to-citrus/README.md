# cassava_model
---

1. **cassava_leaf_disease_classification.ipynb** is an ensemble of InceptionV3 and Xception model on the cassava dataset from [competetion](https://www.kaggle.com/c/cassava-leaf-disease-classification). The test accuracy is in ~86%. The notebook was trained as a kaggle notebook with data loaded from the competetion.

2. **transfer_Learning_cassava_model_to_citrus.ipynb** uses transfer learning to train cassava model's head on citrus dataset. The reason to use this appraoch was extremly small dataset for citrus leaves. This approach made sense to be used because there were similarity between symptoms of diseases in cassav leaves and citrus leaves. The dataset is avaible in [kaggle](https://www.kaggle.com/dtrilsbeek/citrus-leaves-prepared). To notebook was trained in google colab and uses google drive to load data.



 
