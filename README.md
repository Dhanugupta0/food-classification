# 🍔 Food Classification using CNN

This project is a deep learning model that classifies images of food into **101 categories**.  
It uses **Convolutional Neural Networks (CNNs)** trained on a dataset of food images.  

---

## 📂 Project Structure
├── main.ipynb # Jupyter Notebook with model training
├── food_c101_n1000_r384x384x3.h5 # (Optional) Preprocessed dataset
├── README.md # Project documentation
└── requirements.txt # Dependencies (TensorFlow, NumPy, etc.)

yaml
Copy
Edit

---

## 📊 Dataset
- Dataset: **Food-101** (small subset used here).
- Shape: `(1000, 384, 384, 3)` images.
- Labels: `101` food categories.

⚠️ Note: Large dataset files (like `.h5`) are not uploaded here due to GitHub’s file size limits.  
You can download the dataset from [Food-101 Dataset](https://data.vision.ee.ethz.ch/cvl/datasets_extra/food-101/).

---

## 🚀 Model
- Framework: **TensorFlow / Keras**
- Architecture: **CNN (Conv2D, MaxPooling, Dense layers)**
- Loss: `categorical_crossentropy`
- Optimizer: `adam`
- Metrics: `accuracy`

---

## 🔧 Installation
Clone this repository and install dependencies:

```bash
git clone https://github.com/YOUR_USERNAME/food-classification.git
cd food-classification
pip install -r requirements.txt
