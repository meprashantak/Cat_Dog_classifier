
## Cat & Dog Classifier 🐶🐱

A deep learning project that classifies images of cats and dogs using a Convolutional Neural Network (CNN).  
This repository includes the trained model and a web application for uploading images and getting predictions.

---

## 📁 Project Structure

```

Cat_Dog_classifier/
├── static/
├── templates/
├── uploads/
├── Cat-Dog Classifier.ipynb
├── app.py
├── cats_dogs_model2.keras
├── requirements.txt
└── README.md

````

- **static/** — Static files for the web app (CSS/Images/Scripts)  
- **templates/** — HTML templates for the Flask web UI  
- **uploads/** — Stores user-uploaded images for prediction  
- **Cat-Dog Classifier.ipynb** — Jupyter notebook for training/testing  
- **app.py** — Flask app for running the web interface  
- **cats_dogs_model2.keras** — Trained CNN model  
- **requirements.txt** — Python dependencies  

---

##  Getting Started

### ✅ 1. Clone the Repository
```bash
git clone https://github.com/meprashantak/Cat_Dog_classifier.git
cd Cat_Dog_classifier
````

### ✅ 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### ✅ (Optional) Create Virtual Environment

```bash
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows
```

---

## ▶️ Run the Web Application

```bash
python app.py
```

Then open your browser and go to:

```
http://127.0.0.1:5000/
```

Upload an image of a **cat or dog**, and the model will return the prediction 🐱🐶

---

##  Model Details

* **Model Type:** CNN (Convolutional Neural Network)
* **Framework:** TensorFlow/Keras
* **Model File:** `cats_dogs_model2.keras`
* **Notebook:** `Cat-Dog Classifier.ipynb` (contains training and evaluation code)

---

##  Requirements

Install all dependencies using:

```bash
pip install -r requirements.txt
```

---

## 👨‍💻 Author

**Prashant Kuchanure**
GitHub: [meprashantak](https://github.com/meprashantak)

---

## ⭐ Support

If you find this project helpful, please ⭐ the repository!

---



