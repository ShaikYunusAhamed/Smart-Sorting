# Smart-Sorting: Transfer Learning for Identifying Rotten Fruits and Vegetables

This project uses Transfer Learning to classify fruits and vegetables as **Fresh** or **Rotten**, then serves a Flask web interface for upload and classification.

## 💻 Tech Stack
- Python, Flask, TensorFlow/Keras, OpenCV
- HTML/CSS (Frontend)

## 📁 Structure
- `/static/uploads`: uploaded images
- `/templates/`: HTML pages
- `healthy_vs_rotten.h5`: trained model
- `app.py`: Flask app script

## 🚀 How to Run
1. Install dependencies: `pip install -r requirements.txt`
2. Run app: `python app.py`
3. Open browser: `http://127.0.0.1:5000`

## 📌 Sample Prediction
Upload an image to get classification result: **Fresh** ✅ or **Rotten** ❌
