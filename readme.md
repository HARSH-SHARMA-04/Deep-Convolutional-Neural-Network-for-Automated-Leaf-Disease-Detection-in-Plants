# Plant Leaf Disease Prediction 

A machine learning pipeline to detect plant leaf diseases using CNNs, trained in Google Colab and deployed via Streamlit.

---

## 🚀 Features
- Preprocess & visualize leaf images
- Data normalization, one‑hot encode & class imbalance checks
- Train/validation/test split
- Build, compile & train CNN; plot accuracy and loss
- Make predictions & visualize results
- Deploy interactive app with **Streamlit**

---

## 📁 Project Structure
/
├── Plant_Leaf_Disease_Prediction.ipynb
├── dataset/
├── plant_disease_model.h5
└── main_app.py


## ⚙️ Getting Started

### 1. Generate the Model
1. Extract zipped contents into a `Plant‑Leaf‑Disease‑Prediction` folder in Google Drive  
2. Upload notebook and dataset into that folder  
3. Open `Plant_Leaf_Disease_Prediction.ipynb` in Google Colab and run end-to-end  
4. `plant_disease_model.h5` is saved under `Model/` in your Drive

### 2. Run the Streamlit App
1. Download `plant_disease_model.h5` to your local machine  
2. Place it alongside `main_app.py` in one folder  
3. Install dependencies:
   ```bash
   pip install pipreqs
   pipreqs .
   pip install -r requirements.txt
Launch the app:

streamlit run main_app.py
🧠 How It Works
Mount Drive and load image dataset

Resize and normalize images into NumPy arrays

Visualize and inspect class imbalance

One‑hot encode labels and split into train, validation, and test sets

Define CNN architecture, compile, and train model

Visualize learning curves: accuracy and loss per epoch

Predict on test data and display results using labels visualization

Serve model via interactive Streamlit interface

🎯 Motivation
Enables accessible, end-to-end plant disease detection—from raw images to inference—ideal for educational and real-world IoT/field use.

🧰 Tech Stack
Python (NumPy, pandas)

TensorFlow / Keras

Matplotlib / Seaborn for visualization

Streamlit for deployment

