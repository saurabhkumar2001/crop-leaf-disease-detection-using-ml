# 🌿 Crop Disease Detection System

![Home Page](home_page.jpeg)

---

## 🧪 Requirements

Make sure you have the following dependencies installed:

```txt
tensorflow==2.10.0  
scikit-learn==1.3.0  
numpy==1.24.3  
matplotlib==3.7.2  
seaborn==0.13.0  
pandas==2.1.0  
streamlit  
librosa==0.10.1

##To install all dependencies:
pip install -r requirements.txt

🚀 Project Overview
The Crop Disease Detection System is an AI-powered web application built using Streamlit and TensorFlow. It helps in detecting diseases in plant leaves by analyzing uploaded images. The system is trained on real-world crop disease datasets and aims to assist farmers in taking early action against infections to minimize yield loss.
⚙️ How It Works
Upload an Image
On the "Disease Recognition" page, upload a plant leaf image that shows possible symptoms of disease.

Automated Analysis
The image is processed using a trained deep learning model (CNN) to detect and classify the disease.

Get Results
The system displays the prediction result along with the name of the disease and possible next steps.

✅ Why Choose This System?
🤖 Accurate predictions using a custom CNN model

📷 User-friendly interface built with Streamlit

🧠 Trained model included with visualization of training history

🧪 Tested on real-world dataset with clear train, test, and validation split

🌱 Supports sustainable farming

🌐 App Preview

📁 Folder Structure

CropDiseaseDetectionSystem/
├── test/                          # Test dataset (leaf images)
├── train/                         # Training dataset
├── valid/                         # Validation dataset
├── main.py                        # Streamlit app file
├── requirements.txt               # Dependencies
├── test_plant_disease.py          # Script for testing prediction
├── train_plant_disease.py         # Model training script
├── trained_model.keras            # Saved trained model
├── training_history.png           # Model accuracy/loss graph
├── home_page.jpeg                 # Homepage image
└── main_website.jpg               # App screenshot


🧪 How to Run the Project

1 Clone the repository:
git clone https://github.com/your-username/crop-disease-detection.git
cd crop-disease-detection
2 Install all dependencies:
Edit
pip install -r requirements.txt
3 Launch the Streamlit app:
streamlit run main.py

