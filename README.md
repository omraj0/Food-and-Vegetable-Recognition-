# 🍎 Fruits & Vegetables Recognition 🍊🥦

![TensorFlow](https://raw.githubusercontent.com/devicons/devicon/master/icons/tensorflow/tensorflow-original.svg) ![Python](https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg) ![Keras](https://upload.wikimedia.org/wikipedia/commons/a/a4/Keras_logo.svg)

## 📌 Overview
The **Fruits & Vegetables Recognition** project is a Deep Learning model built using **Python, TensorFlow, Keras, and CNN**, trained on **12,840 images** to classify over **36 types** of fruits and vegetables with **93% accuracy**. It helps in automating fresh produce identification for applications in supermarkets, agriculture, and health monitoring.

## 🚀 Features
✅ **36-class classification** of fruits & vegetables 🍏🍇🥕  
✅ **Convolutional Neural Network (CNN)** for image recognition 🧠  
✅ **Trained on 12,840 labeled images** for accurate results 📸  
✅ **Achieved 93% accuracy** with rigorous validation ✅  
✅ **Built using Python, TensorFlow, and Keras** 🐍  
✅ **Runs on Google Colab for easy training and execution** 💻  

## 🛠️ Technologies Used
- **Python** 🐍
- **TensorFlow** 🔶
- **Keras** 🔬
- **CNN (Convolutional Neural Network)** 🧠
- **Google Colab** 🖥️
- **NumPy & Pandas** 📊
- **Matplotlib & Seaborn** 📈

## 📂 Dataset
The dataset consists of **12,840 images** of **fruits and vegetables**, categorized into **36 classes**. The images were preprocessed, normalized, and augmented to improve model generalization.

## ⚙️ Installation & Setup
Follow these steps to install and run the project locally:
```bash
# Clone the repository
git clone https://github.com/yourusername/fruits-vegetables-recognition.git
cd fruits-vegetables-recognition

# Install required dependencies
pip install tensorflow keras numpy pandas matplotlib seaborn

# Run the Jupyter Notebook
jupyter notebook
```

## 🔄 Model Training
To train the CNN model on the dataset:
```python
from tensorflow.keras.models import Sequential
from tensorflow.keras.layers import Conv2D, MaxPooling2D, Flatten, Dense

# Define the CNN model
model = Sequential([
    Conv2D(32, (3,3), activation='relu', input_shape=(64, 64, 3)),
    MaxPooling2D(2,2),
    Conv2D(64, (3,3), activation='relu'),
    MaxPooling2D(2,2),
    Flatten(),
    Dense(128, activation='relu'),
    Dense(36, activation='softmax')
])

# Compile the model
model.compile(optimizer='adam', loss='categorical_crossentropy', metrics=['accuracy'])

# Train the model
model.fit(train_data, epochs=20, validation_data=valid_data)
```

## 📊 Results
- **Accuracy Achieved:** 🎯 **93%**
- **Dataset Size:** 📸 **12,840 images**
- **Total Classes:** 🍏🥕 **36 Fruits & Vegetables**
- **Training Time:** ⏳ ~30 minutes on Google Colab

## 📖 Usage
1. Upload an image of a fruit or vegetable.
2. The model processes the image and predicts the class.
3. The output includes the class name and confidence score.

## 🤝 Contributing
Contributions are welcome! To contribute:
```bash
# Fork the repository
git fork https://github.com/yourusername/fruits-vegetables-recognition.git

# Create a new branch
git checkout -b feature/your-feature

# Commit your changes
git commit -m "Added new feature"

# Push to the branch
git push origin feature/your-feature

# Open a Pull Request
```

## 📜 License
This project is licensed under the **MIT License**.

## 📫 Contact
📧 **Email**: [omraj010@gmail.com](mailto:omraj010@gmail.com) ✉️  
🌐 **Portfolio**: [Visit Portfolio](https://omraj0.github.io/) 🌍  
