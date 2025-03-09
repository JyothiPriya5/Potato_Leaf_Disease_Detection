# 🍃 Potato Leaf Disease Detection  

This project is a **Potato Leaf Disease Detection** system that uses **Convolutional Neural Networks (CNN)** to identify different diseases affecting potato leaves from an image. The model can predict diseases like **Early Blight** and **Late Blight** with high accuracy.  

---

## 📸 Snapshots  

### 🔹 Upload Interface  
The user can upload an image of a potato leaf through the interface to get a prediction.  

![WhatsApp Image 2025-03-08 at 22 33 44_bc144f75](https://github.com/user-attachments/assets/3c0cc05b-bd01-482f-8545-26bd6cbc8cd1)
 

### 🔹 Prediction Result  
The result displays the uploaded image and the predicted disease.  

![WhatsApp Image 2025-03-08 at 22 34 30_8d551fdb](https://github.com/user-attachments/assets/e793cdb0-f554-47c4-b612-84ce5d62daa1)

---

## 🏗️ Project Structure 
- ├── app.py 
- ├── templates/
- │ ├── index.html
- │ └── result.html 
- ├── static/uploads
- ├── model/potato_model.h5
- ├── requirements.txt # Dependencies
- └── README.md
---

## 🖥️ Technologies Used  
- **Python**  
- **TensorFlow/Keras**  
- **OpenCV**  
- **Flask**  
- **HTML/CSS**  

---

## 📂 How to Run the Project  
1. **Clone the Repository**  
```bash
git clone https://github.com/yourusername/potato-leaf-disease-detection.git

Create and Activate a Virtual Environment
```bash
python -m venv venv  
source venv/bin/activate   # Linux/MacOS  
venv\Scripts\activate      # Windows  

