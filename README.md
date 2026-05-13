Brain Tumor Classification using Deep Learning (CNN) 🧠🔬

This project focuses on the automated detection and classification of brain tumors from MRI images using Convolutional Neural Networks (CNN).

The model is designed to classify images into four distinct categories: Glioma, Meningioma, Pituitary, and No Tumor.

📊 Performance

HighlightsAccuracy:Achieved a high test accuracy of 98.6%. Generalization: Strong performance across all metrics with a 0.9861 macro F1-score. Robustness: High AUC values for all classes, as demonstrated by the ROC curves.

🛠️ Model ArchitectureThe model uses a Sequential CNN approach with the following key components:

6 Convolutional Layers: Progressing from 64 to 512 filters to extract hierarchical features. Batch Normalization: Applied after each convolution for faster convergence and stability. Regularization: Used Dropout (0.25) and Early Stopping to prevent overfitting. Optimizer: Adam optimizer with a learning rate reduction strategy (ReduceLROnPlateau).

🧪 Tech Stack Framework: TensorFlow / Keras. Computer Vision: OpenCV for image preprocessing and resizing (128x128). Data Visualization: Matplotlib & Seaborn for plotting training history, Confusion Matrix, and ROC curves. Environment: Google Colab.

📈 Results Overview Confusion Matrix: Shows near-perfect classification, with only minor misclassifications in the meningioma class. Training History: Loss and Accuracy curves indicate a stable learning process without significant overfitting. Classification Report: Detailed precision and recall scores per class are provided to ensure diagnostic reliability.

📂 Dataset StructureThe project uses an MRI dataset organized as follows: Training: 5,368 images. Validation: 945 images. Testing: 720 images.
