# 🦋 Butterfly Species Classifier

A Flask web application that uses a trained VGG16 deep learning model to classify butterfly species from uploaded images.

---

## 📁 Project Structure

project/
│
├── static/ # Static files (CSS, JS, Images)
├── templates/ # HTML templates
├── vgg16_butterfly_model.h5 (⚠️ NOT INCLUDED — download below)
├── app.py # Flask application
├── requirements.txt # Python dependencies
└── README.md # Project description


---

## 🚀 Getting Started

### 1. Clone the repository

git clone https://github.com/mujeebshaik04/butterfly-classifier.git
cd butterfly-classifier

2. Install requirements

pip install -r requirements.txt


3. Download the Trained Model (VGG16)
⚠️ The .h5 model file is too large to be stored on GitHub.

**📥 Download from Google Drive:**
Download vgg16_butterfly_model.h5

📌 Place the downloaded file in the root of the project folder

**🖼️ How It Works**
User uploads an image of a butterfly.

The image is preprocessed and passed to a VGG16-based model.

The model predicts the butterfly species.

The prediction is displayed on the results page.

**▶️ Running the App**

python app.py

Then open http://127.0.0.1:5000/ in your browser.

**🧠 Model Info**
Architecture: VGG16

Framework: TensorFlow / Keras

Input size: 224x224

Classes: Multiple butterfly species

Accuracy: ~90% (test set)

**👨‍💻 Team Information**
**Team ID**: LTVIP0225TMID42172
**Team Members**:

Y. Sai Greeshma (Leader)

Shaik Abdul Mujeeb

Shaik Mohammad Abdullah

S. Mabu Subani




✅ Replace the Google Drive link (`https://drive.google.com/file/d/1UMMDZsszA46wbrMah8b4otEAbgjr-K3M/view?usp=sharing`) with your actual shareable link.

Let me know if you want a downloadable version or to include screenshots too.
