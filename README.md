# 🌿 Plant Disease Prediction using Deep Learning

A robust Convolutional Neural Network (CNN)-based deep learning model for accurate identification and classification of plant diseases from leaf images. This project leverages powerful image processing and pattern recognition techniques to help farmers and agricultural professionals take timely corrective actions to improve crop health.

We use the [PlantVillage Dataset](https://www.kaggle.com/datasets/emmarex/plantdisease) from Kaggle — a publicly available, high-quality image dataset of healthy and infected crop leaves.



## 🚀 Project Highlights

- 🔍 **Disease Detection**: Classifies multiple plant diseases with high accuracy using CNN.
- 🧠 **Deep Learning Architecture**: Built from scratch using TensorFlow/Keras.
- 📊 **Training Pipeline**: Includes model training, evaluation, and visualization.
- 🖼️ **Image-Based Input**: Works with real-time leaf images for diagnosis.
- 📁 **Well-Structured Repository**: Cleanly organized for easy understanding and extension.

## 🧩 Tech Stack

- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Matplotlib
- scikit-learn

## 📂 Directory Structure
📁 plant-disease-prediction/
├── 📁 dataset/
      ├── 📄 requirements.txt
      ├── 📁 app/
├── 📁 model_training_notebook/
      ├── 📄 plant_disease_prediction.ipynb
└── 📄 README.md


## 🧪 Dataset

The dataset consists of a diverse set of high-resolution leaf images labeled with disease names. It has been preprocessed and augmented for better generalization.

📌 Dataset Source: [PlantVillage Dataset on Kaggle](https://www.kaggle.com/datasets/emmarex/plantdisease)



## 🏗️ How the Model Works

1. **Image Preprocessing** – Resize, normalize, and augment images.
2. **CNN Architecture** – Custom model with Conv2D, MaxPooling, Dropout, and Dense layers.
3. **Training** – Uses categorical cross-entropy loss and Adam optimizer.
4. **Evaluation** – Accuracy, confusion matrix, and visual predictions.

---

## 🧠 Model Architecture Snapshot

Conv2D ➝ ReLU ➝ MaxPooling2D ➝ Dropout ➝
Conv2D ➝ ReLU ➝ MaxPooling2D ➝ Dropout ➝
Flatten ➝ Dense ➝ Softmax




## 🛠️ Installation & Usage

```bash
# Clone the repository
git clone [Plant Dieases](https://github.com/himanshi2744/plant-disease-prediction.git)
cd plant-disease-prediction-main

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook plant_disease_prediction.ipynb
```

## 📈 Results

- Achieved **high validation accuracy** across multiple disease categories.
- Real-time predictions possible with minimal latency.
- Visualizations for training/validation accuracy and loss included.

## 🖼️ Sample Predictions

> Here are a few samples from the test set predicted by the model:

| Input Image | Predicted Disease        |
|-------------|---------------------------|
| 🍃 Leaf #1   | Tomato Mosaic Virus       |
| 🍃 Leaf #2   | Potato Late Blight        |




## 📌 Future Improvements

- 🔄 Integrate Transfer Learning (e.g., ResNet, EfficientNet)
- 🌐 Add a Web/Mobile interface for user interaction
- 📲 Create a mobile-friendly app for field detection
- 🛰️ Use drone/satellite imagery for large-scale farm scans


## 🤝 Contributions

Pull requests, suggestions, and improvements are welcome! Feel free to fork the repo, open an issue, or submit a PR.



## 📜 License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.



## 🙌 Acknowledgements

- The open-source deep learning and computer vision community
- Public contributors of plant disease datasets
- TensorFlow/Keras for seamless experimentation

## 🔗 Connect with the Maintainers

- GitHub: [Husain](https://github.com/Byteers)
- GitHub: [Himanshi](https://github.com/himanshi2744)

- LinkedIn: [Husain](https://www.linkedin.com/in/husainkmahuda/)
- LinkedIn: [Himanshi](https://www.linkedin.com/in/himanshi-yaduvanshi-803929345/)
