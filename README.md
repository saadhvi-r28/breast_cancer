Link for dataset: https://www.kaggle.com/datasets/aryashah2k/breast-ultrasound-images-dataset

A machine learning model that can distinguish between malignant (cancerous) and benign (non-cancerous) tumours based on various features extracted from medical data. The primary objective is to create a model that can assist medical professionals in making more informed decisions about cancer diagnoses.

The dataset is loaded into a Pandas Data Frame and labelled, with malignant tumours represented as 1 and benign tumours as 0. Features and target variables are separated, preparing the data for model training.

The dataset is divided into training (70%) and testing (30%) sets using the train test split function from scikit-learn.

Decision Tree Classifier (DTC) is chosen as the machine learning model for this task. The model is trained on the standardized training data.

The model's performance is assessed using accuracy as the primary evaluation metric. A confusion matrix is also generated to visualize the model's classification performance.
