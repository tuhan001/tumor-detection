# Brain-Tumor-Detection-Using-Deep-Learning-MRI-Images-Detection-Using-Computer-Vision



# 🧠 Brain Tumor Detection using Deep Learning (MRI Images)

This project is a **Flask web application** that uses a trained deep learning model to detect and classify brain tumors from MRI images.  
The model was trained using TensorFlow/Keras and can classify MRI scans into the following categories:

- **Pituitary Tumor**
- **Glioma**
- **Meningioma**
- **No Tumor**

---

## 🚀 Features
- Upload an MRI scan through the web interface
- Predict tumor type with **confidence score**
- Displays the uploaded image alongside the prediction
- Built with **Flask**, **TensorFlow/Keras**, and **HTML templates**

---

## 📂 Project Structure
```
Brain-Tumor-Detection-Using-Deep-Learning-MRI-Images-Detection-Using-Computer-Vision/
│
├── main.py                # Flask application
├── requirements.txt       # Python dependencies
├── models/
│   └── model.h5           # Pre-trained Keras model
├── templates/
│   └── index.html         # Frontend HTML template
├── uploads/               # Uploaded MRI images (auto-created)
└── README.md              # Project documentation
```

---

## ⚙️ Installation & Setup
you need to run this project. first of all you run the idymb file on colab,
then downlode the h5 data model and create a folder name model, 
then html file replace on template then use for thouse system for your oprateing system

### 1. Clone this repository
```bash
git clone <your-repo-url>
cd Brain-Tumor-Detection-Using-Deep-Learning-MRI-Images-Detection-Using-Computer-Vision
```

### 2. Create a virtual environment (Python 3.11 recommended)
```powershell
py -3.11 -m venv venv
```

### 3. Activate the environment
```powershell
.\venv\Scripts\activate
```

### 4. Install dependencies
```powershell
pip install -r requirements.txt
```

### 5. Ensure the model exists
Place your trained model at:
```
models/model.h5
```

### 6. Run the Flask app
```powershell
python main.py
```

---

## 🌐 Usage
- Open your browser and go to: **http://127.0.0.1:5000/**
- Upload an MRI scan (`.jpg`, `.jpeg`, `.png`, `.bmp`, `.tif`)
- Get prediction result with confidence score  
- Example result:  
  ```
  Tumor: Glioma (Confidence: 97.42%)
  ```

---

## 🛠️ Tech Stack
- **Python 3.11**
- **Flask 3.1**
- **TensorFlow 2.18 / Keras 3.7**
- **NumPy / h5py / Pillow**
- **HTML (Jinja2 templates)**

---

## ⚠️ Notes
- This is a **research/demo project** — not for medical use.
- Predictions should **not** be considered as a medical diagnosis.
- Use only for **educational purposes**.

---

## 👨‍💻 Author
Developed by **[Your Name]**  
Feel free to fork and improve the project 🚀



## For Linux User
# 1. Go to your project folder
cd "/path/to/Brain-Tumor-Detection-Using-Deep-Learning-MRI-Images-Detection-Using-Computer-Vision"

# 2. Create a virtual environment (Python 3.11 recommended)
python3.11 -m venv venv

# 3. Activate the environment
source venv/bin/activate

# 4. Install dependencies
pip install -r requirements.txt

# 5. Make sure templates folder exists
mkdir -p templates

# 6. Move HTML into templates folder (if still outside)
mv index.html templates/index.html

# 7. Ensure model exists
# (Your trained model must be inside ./models/model.h5)

# 8. Run the Flask app
python main.py

