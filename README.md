# 🍎 Fruits & Vegetables Recognition 🍊🥦

Fruits & Vegetables Recognition is a Deep Learning project that classifies over **36 types** of fruits and vegetables using a **Convolutional Neural Network (CNN)**. The model achieves **93% accuracy** by training on **12,840 images**. 

## 🚀 Features
- ✅ Recognizes 36+ categories of fruits and vegetables
- ✅ Trained on **12,840 images** with high accuracy
- ✅ **CNN-based architecture** using TensorFlow & Keras
- ✅ **Data Augmentation** for better generalization
- ✅ **Google Colab** used for model training
- ✅ **Fast & Accurate Predictions**

## 🔗 Live Demo & Repository
- 📂 **GitHub Repo**: [Fruits & Vegetables Recognition](https://github.com/omraj0/Fruits-and-Vegetables-Recognition)

## 🛠️ Installation & Setup
To run the project locally, follow these steps:

```bash
# Clone the repository
git clone https://github.com/omraj0/Fruits-and-Vegetables-Recognition.git
cd Fruits-and-Vegetables-Recognition

# Create and activate a virtual environment (Optional but recommended)
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate

# Install required dependencies
pip install -r requirements.txt

# Run the model training script
python train.py

# To make predictions using the trained model
python predict.py --image test_image.jpg
```

## 🧠 Model Architecture
The CNN model consists of:
- 🏗️ **2 Convolutional Layers** (ReLU activation, MaxPooling)
- 🎯 **Fully Connected Dense Layers**
- 🔢 **Softmax Layer** for multi-class classification
- 🔄 **Adam Optimizer** for efficient training
- 📊 **Categorical Crossentropy Loss**

## 📊 Results & Performance
- **Training Accuracy**: ~93%
- **Dataset**: 12,840 labeled images
- **Evaluation**: High precision and recall on test data

## 🤖 Usage
### Train the Model 🏋️‍♂️
```bash
python train.py
```
### Predict on a New Image 🖼️
```bash
python predict.py --image test_image.jpg
```

## 🤝 Contributing
Contributions are welcome! Follow these steps:
1. **Fork the repository**
   ```bash
   git fork https://github.com/omraj0/Fruits-and-Vegetables-Recognition.git
   ```
2. **Create a new branch**
   ```bash
   git checkout -b feature/your-feature
   ```
3. **Commit and push your changes**
   ```bash
   git commit -m "Add new feature"
   git push origin feature/your-feature
   ```
4. **Create a Pull Request**

## 📄 License
This project is licensed under the **MIT License**.

## 📫 Contact
📧 **Email**: [omraj010@gmail.com](mailto:omraj010@gmail.com) ✉️  
🌐 **Portfolio**: [Visit Portfolio](https://omraj0.github.io/) 🌍  
