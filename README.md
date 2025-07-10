# MNIST Digit Classification 🎯

This project trains machine learning models on the MNIST handwritten digit dataset using:
- **SGDClassifier** (with hinge loss)
- **RandomForestClassifier**

It also deploys a **Gradio app** that lets you draw digits and predicts them.

## 📊 Features
- Loads & preprocesses MNIST dataset
- Trains SGD and Random Forest models
- Evaluates with confusion matrix & classification report
- Error analysis
- Gradio web app for real-time digit recognition

## 🚀 How to run
```bash
pip install -r requirements.txt
python app/gradio_app.py
