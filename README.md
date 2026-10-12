# COVID-19 Chest X-ray Detection

A deep learning pipeline that classifies chest X-ray images as COVID-19 positive or negative, built as a university Neural Networks project.

🔗 **Live demo:** https://covid-19-x-ray-intelligence-analysis-btpkkqnrdjk7r9sa9re8ns.streamlit.app/

## Dataset
**COVIDx CXR-4** (Kaggle: `andyczhao/covidx-cxr2`), about 31 GB of chest X-rays. Train: 67,863 | Validation: 8,473 | Test: 8,482.

## Approach
- Data pipeline with resizing, normalization, class balancing and augmentation
- Baseline model and custom CNNs
- Transfer learning with DenseNet121 and VGG16
- Grad-CAM heatmaps for explainability
- Streamlit web app for real-time inference

## Tech Stack
Python, TensorFlow/Keras, scikit-learn, pandas, Matplotlib, Streamlit

## Author
Abanoub Rezk Gad: [LinkedIn](https://linkedin.com/in/abanoub-rezk)
