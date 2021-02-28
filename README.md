# Mined-Hackathon-Submission

Library and tools: Keras, Numpy and Pillow

Dataset for Alzheimer: https://www.kaggle.com/tourist55/alzheimers-dataset-4-class-of-images
Dataset for Skin Disease as provided by Sponsors and more data added from our side.

AI Architecture: Siamese Network with a CNN based vector generator, E-mixup augmentation for images and an MLP for classification
Methedology: Images undergo Histogram equalization to avoid biases, 8000 Pairs are obtained from the training set for the Siamese Network which train the CNN vector generator for similarity learning, the obtained embeddings are augmented by using E-Mixup and fed into an MLP for categorical classification

Steps for Execution:

1. First run the backend file
2. Then Run the given frontend file
3. In frontend saved model is already given in the directory.
4. After running front end in last it will give address so copy that and paste it in browser.
