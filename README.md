# End-to-End-Deep-Learning-Project-Chicken-Disease

## 🧠 Overview  
This project is an **end-to-end deep learning pipeline** for detecting **chicken diseases** from images.  
It covers the complete workflow — from dataset storage in AWS S3 to model training and deployment on AWS EC2 with a simple HTML frontend.

The goal of this project was to build a fully functional deep learning solution using AWS cloud integration.

---

## 🚀 Key Features  
- 🐔 Image-based **chicken disease classification**
- 🧠 Custom **CNN model** trained on ~200 images  
- ☁️ Dataset stored in **AWS S3 Bucket**
- 💻 Deployed on **AWS EC2 instance** using **Flask**
- 🌐 Simple **HTML frontend** for user interaction
- 🔁 End-to-End data to deployment workflow

---

---

## ⚙️ Tech Stack  
- **Language:** Python  
- **Frameworks:** TensorFlow / Keras, Flask  
- **Frontend:** HTML, CSS  
- **Cloud:** AWS S3 (data storage), AWS EC2 (deployment)  
- **Version Control:** Git & GitHub  

---


### Workflows

1. Update config.yaml
2. Update params.yaml
3. Update the entity
4. Update the configuration manager in src config
5. Update the components
6. Update the pipeline
7. Update the main.py
8. Update the app.py

### How to run?

#### STEPS:

Clone the repository

```base
https://github.com/mkador/End-to-End-Deep-Learning-Project-Chicken-Disease.git
```

### STEP 01- Create a conda environment after opening the repository

conda create -n cnncls python=3.8 -y
conda activate cnncls

### STEP 02- install the requirements

pip install -r requirements.txt

### Export the environment

export AWS_ACCESS_KEY_ID="YOUR_ACCESS_KEY_ID"
export AWS_SECRET_ACCESS_KEY="YOUR_SECRET_ACCESS_KEY"
