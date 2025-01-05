# mnist-digit-recognizer
This project explores the Kaggle Digit Recognizer challenge, which involves building a model to classify handwritten digits (0-9) from the MNIST dataset. The goal is to preprocess the data, train a convolutional neural network (CNN), and achieve high accuracy on unseen test data.

Technologies Used
	•	Python: Primary programming language.
	•	PyTorch: Deep learning framework for building and training the CNN.
	•	Pandas: For data manipulation and preprocessing.
	•	NumPy: For numerical computations.
	•	Matplotlib: For visualizing data and training results.
	•	Kaggle Dataset: MNIST dataset in CSV format.

Key Learnings
	1.	Data Preprocessing:
	•	Flattened image data from CSV was reshaped into 28x28 grayscale images for model input.
	•	Applied transformations like ToTensor() to prepare the data for training.
	2.	Custom Dataset Implementation:
	•	Built a PyTorch Dataset class to handle CSV-based input, ensuring compatibility with DataLoader.
	3.	CNN Architecture:
	•	Designed a CNN with convolutional, pooling, and fully connected layers to classify digits effectively.
	4.	Batch Dimension Handling:
	•	Learned the importance of maintaining the correct input shape (batch size, channels, height, width) for CNNs.
	5.	Evaluation and Predictions:
	•	Implemented a custom evaluation loop to generate predictions on test data while avoiding common shape-related errors.
	6.	Model Optimization:
	•	Experimented with techniques like batch normalization and learning rate adjustments to improve model performance.
	7.	Debugging and Error Handling:
	•	Resolved issues with input dimensions and missing labels in test datasets.
	8.	Deployment Consideration:
	•	Prepared the model for predicting unseen data, ensuring scalability and future integration possibilities.

Summary

This project provided hands-on experience with deep learning concepts, data preprocessing, and debugging PyTorch-based pipelines. It also reinforced the importance of handling real-world challenges like incomplete datasets and compatibility issues during model development.