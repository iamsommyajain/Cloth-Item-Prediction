# 🧥 Cloth-Item-Prediction  

This project leverages the **Fashion MNIST dataset** to train a **Convolutional Neural Network (CNN) model**, achieving an impressive **95.7% accuracy** in classifying clothing items. The trained model is seamlessly integrated into a **Streamlit web application**, providing an interactive and user-friendly interface for real-time predictions.  

To ensure scalability and ease of deployment, the application is containerized using **Docker**, enabling it to run efficiently across different environments.  

---

## 🚀 Features  
✅ **Deep Learning Model** – A CNN trained on the Fashion MNIST dataset for high-accuracy predictions.  
✅ **Interactive Web App** – A lightweight, responsive interface built with Streamlit for easy user interaction.  
✅ **Dockerized Deployment** – The application is containerized for seamless deployment across different environments.  

---

## 🛠️ How It Works  
1️⃣ **Upload an Image** – Users can upload an image of a clothing item.  
2️⃣ **Preprocessing** – The image is resized, converted to grayscale, and normalized.  
3️⃣ **Prediction** – The trained CNN model classifies the item into one of 10 categories.  
4️⃣ **Output** – The predicted class is displayed along with the confidence score.  

---

## 📦 Installation & Setup  

### 1️⃣ Clone the Repository  
```sh
git clone https://github.com/iamsommyajain/Cloth-Item-Prediction.git
cd Cloth-Item-Prediction
```
### 2️⃣ Installing Dependencies 
```sh
pip install -r requirements.txt
```
### 3️⃣ Run the Streamlit App
```sh
streamlit run app/main.py
```
### 4️⃣ Run with Docker
```sh
docker build -t fashion_classifier_app:v1.0 .
docker run -p 80:80 fashion_classifier_app:v1.0
```
---

## 🤝 Contributing  
Contributions are welcome! If you find a bug or want to improve the model, feel free to open an issue or submit a pull request.  

---

## 📜 License  
This project is licensed under the **MIT License**.  

---

## 🔗 Connect  
📧 **Email:** [sommyajain2005@gmail.com](mailto:sommyajain2005@gmail.com)  
🌍 **GitHub:** [@iamsommyajain](https://github.com/iamsommyajain)  
