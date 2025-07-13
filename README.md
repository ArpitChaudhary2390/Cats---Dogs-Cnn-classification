# Image Classification of Cats and Dogs using CNN

This project implements a Convolutional Neural Network (CNN) using TensorFlow/Keras to classify images of cats and dogs.

---

## 📂 Dataset
- Dataset: `cats_vs_dogs` from TensorFlow Datasets
- Images automatically resized to 128x128
- Corrupted images were skipped during loading

---

## 🧠 Model Architecture
- Conv2D (32 filters) + MaxPooling2D
- Conv2D (64 filters) + MaxPooling2D
- Conv2D (128 filters) + MaxPooling2D
- Flatten + Dense (128 units) + Dropout
- Output Layer with Sigmoid activation (Binary Classification)

---

## 🏋️ Training Details
- Optimizer: Adam
- Loss Function: Binary Crossentropy
- Epochs: 5
- Final Validation Accuracy: ~77%
- Model trained and tested using Google Colab

---

## 🖼️ Output & Prediction
- Accuracy and Loss graphs plotted using Matplotlib
- Custom prediction function provided for testing with new images

---

## 🛠️ Technologies Used
- Python
- TensorFlow / Keras
- Google Colab
- Matplotlib
- TensorFlow Datasets

---

## 📁 Files Included
- `Cats_vs_Dogs_CNN_Project.ipynb` – Main project notebook
- `CNN_Cats_vs_Dogs_Presentation.pptx` – PowerPoint presentation
- `CNN_Cats_vs_Dogs_Report.docx` – Detailed project report
- `cat_dog_cnn_model.h5` – Trained model (optional)

---

## 👤 Author
**Arpit Chaudhary**  
B.Tech CSE
Batch 3 (AI)  
Moradabad Institute of Technology

---

## 🔗 References
- https://www.tensorflow.org/
- https://www.tensorflow.org/datasets/catalog/cats_vs_dogs
- https://keras.io/
- ## 📎 Downloads

- 📝 [Download Report](Image_Classification_Report%281%29.docx)
- 📊 [Download Presentation](Image%20Classification%20of%20Cats%20and%20Dogs.pptx)
