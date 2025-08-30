# Plant 🌱 Disease Detection 🔍

This project applies deep learning and Convolutional Neural Networks (CNNs) to identify and classify plant diseases from leaf images. The aim is to provide farmers and agricultural specialists with a reliable tool for quick diagnosis, helping reduce crop losses through timely action.

[**Demo**](https://plant-disease-detection-live.streamlit.app/)


---

## Project Layout 📂

Key components of the project include:

* **Plant\_Disease\_Detection.ipynb** – Notebook containing the model development and training workflow.
* **main\_app.py** – Streamlit application for real-time plant disease predictions.
* **plant\_disease\_model.h5** – Saved weights of the trained model.
* **requirements.txt** – List of required Python packages.

---

## Setup Instructions 🚀

To run the application locally:

1. **Download the project**

```bash
git clone https://github.com/Solanki-Jatin/plant-disease-detection.git```

2. **Navigate to the directory**

```bash
cd Plant-Disease-Detection
```

3. **Install dependencies**

```bash
pip install -r requirements.txt
```

4. **Launch the Streamlit application**

```bash
streamlit run main_app.py
```

---

# Usage 🌿  

Once the app is running, open it in your browser to upload plant leaf images and get predictions.  

---

## Model Overview 🧠

The model was built and trained in the `Plant_Disease_Detection.ipynb` notebook using a CNN-based architecture.
Trained weights are stored in `plant_disease_model.h5` for fast inference without retraining.

---

## Web Application 🌐

The Streamlit interface (`main_app.py`) enables users to interact with the model seamlessly, uploading images and viewing real-time predictions on plant health.

---

## Dependencies 🛠️

* keras==2.8.0
* numpy==1.21.4
* streamlit==1.18.0
* opencv-python-headless==4.5.3
* tensorflow==2.7.0
