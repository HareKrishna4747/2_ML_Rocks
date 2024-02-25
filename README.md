# 🌟 Pulmonary Edema Detection Project 🌟 
This project aims to detect the presence of Pulmonary Edema in Chest X-Ray images using a robust Convolutional Neural Network (CNN). Pulmonary Edema is a critical medical condition where fluid accumulates in the lungs, causing breathing difficulties and respiratory issues.

# 📸 Dataset
The dataset comprises Chest X-Ray images from two distinct sources:

Pulmonary Edema Images

📁 Dataset/Pulmonary_Edema

🏷️ Label: Positive (1)

Normal Lung Images

📁 Dataset/normal

🏷️ Label: Negative (0)

# 🚀 Data Preprocessing and Augmentation
Images undergo a meticulous preprocessing pipeline, which includes:

Resize images to (224, 224) pixels
Normalize pixel values to the range [0, 1]
To enhance the dataset, we employ the TensorFlow ImageDataGenerator, introducing valuable variations.

# 🧠 Model Architecture
The CNN model showcases a powerful architecture:

Convolutional layer (32 filters, 3x3 kernel, ReLU activation)
MaxPooling layer
Convolutional layer (64 filters, 3x3 kernel, ReLU activation)
MaxPooling layer
Flatten layer
Dense layer (128 units, ReLU activation)
Dropout layer (50% dropout rate)
Output layer (1 unit, sigmoid activation)
The model is fueled by the Adam optimizer and binary crossentropy loss for precise binary classification.

# 🏋️‍♀️ Training
The model undergoes rigorous training on a unified dataset, consisting of both original and augmented images. The dataset is thoughtfully shuffled, and training unfolds with a specified batch size and a defined number of epochs.

# 🎯 Model Accuracy
The model boasts an impressive accuracy rate, ensuring reliable and precise results in distinguishing between Pulmonary Edema and normal lung conditions. Our model has undergone rigorous training on a dataset, combining original images with augmented variations.

Feel free to explore and adapt the code for your specific use case. If you encounter any issues or have questions, please refer to the documentation or open an issue. Let's empower the world with Pulmonary Edema detection! 💪🔍
