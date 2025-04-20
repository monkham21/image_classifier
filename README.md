# 🖼️ Image Classifier Web App

This is a simple and intuitive image classification web application built with **Streamlit** and **TensorFlow**. The model used is based on **MobileNetV2**, a lightweight convolutional neural network optimized for real-time classification.

## 🚀 Try It Out

👉 [Launch the App](https://imageclassifier-5mbnyx3zqea8mqqxq2odyr.streamlit.app/)

Upload any image, and the app will classify it into one of the top 3 predicted categories with confidence scores.

## 🔧 How It Works

- Uses **MobileNetV2** pre-trained on **ImageNet**
- Automatically processes uploaded image
- Outputs top-3 predictions using `decode_predictions`

## 🛠️ Tech Stack

- Python
- TensorFlow / Keras
- Streamlit

## 📁 Local Setup (Optional)

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/image-classifier-app.git
   cd image-classifier-app
   ```

2. Install requirements:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the app:
   ```bash
   streamlit run app.py
   ```

## 📷 Example Output

Upload a photo and see something like:
```
1. Labrador retriever — 92%
2. Golden retriever — 4%
3. Flat-coated retriever — 3%
