# Plant Disease Prediction 🌱

This project aims to predict plant diseases using images of plant leaves. It utilizes a Convolutional Neural Network (CNN) architecture and provides a web-based interface for users to upload leaf images for disease diagnosis.

## Features
- **Architecture**: Convolutional Neural Network (CNN)
- **Dataset**: New Plant Disease Dataset (from Kaggle)
- **Classes**: 
  - 38 total classes: 
    - 26 unique plant diseases 
    - 12 healthy plants
  - Covers 14 different plant species.
- **Web Interface**: Built using Streamlit to allow users to upload leaf images for disease detection.
- **Model File**: The trained model is saved as a `.h5` file.

## How It Works
1. The user uploads an image of a plant leaf through the web interface.
2. The image is pre-processed and passed through the trained CNN model.
3. The model predicts the disease (or healthy state) of the plant leaf.

## Technologies Used
- **Python**: Programming language.
- **Keras / TensorFlow**: For building and training the CNN model.
- **Streamlit**: For building the web-based user interface.
- **OpenCV**: For image pre-processing.
- **NumPy, Pandas**: For data manipulation.
- **Matplotlib, Seaborn**: For visualizing results.

