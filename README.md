# 🐱🐶 Smart Cat vs Dog Image Classifier

An accurate **Cat vs Dog image classification web app** built using **TensorFlow, MobileNetV2, and Gradio**.  
The system uses a pretrained ImageNet model to identify whether an uploaded image contains a **cat or a dog**, without training a custom dataset.

---

## 🚀 Features

- Upload an image and get instant prediction
- Uses **MobileNetV2 pretrained on ImageNet**
- Confidence-based decision logic
- Clean and interactive **Gradio web interface**
- No dataset training required
- Lightweight and fast inference

---

## 🧠 How It Works

1. The user uploads an image
2. Image is resized and preprocessed
3. MobileNetV2 predicts top ImageNet classes
4. Predictions are grouped into **Cat** or **Dog**
5. Final decision is made based on confidence score

---

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- MobileNetV2 (Pretrained Model)
- NumPy
- Pillow (PIL)
- Gradio

---

## 📂 Project Structure

cat-dog-classifier-gradio/
│
├── app.py # Main application file
├── README.md # Project documentation
└── requirements.txt # Required Python libraries




## ▶️ How to Run the Project

### 1️⃣ Clone the Repository

git clone https://github.com/your-username/cat-dog-classifier-gradio.git
cd cat-dog-classifier-gradio

2️⃣ Install Dependencies
pip install -r requirements.txt

3️⃣ Run the Application
python app.py


The Gradio app will open in your browser.

📦 requirements.txt
tensorflow
gradio
numpy
pillow

🧪 Sample Output

<img width="1920" height="1020" alt="Screenshot 2026-01-29 185258" src="https://github.com/user-attachments/assets/b303d4be-5439-4589-a18d-3f8600be2928" />
<img width="1920" height="1020" alt="Screenshot 2026-01-29 185408" src="https://github.com/user-attachments/assets/c6911aba-12ac-41c1-801b-dec4297939c4" />


🌟 Use Cases

Beginner-friendly computer vision project

AI/ML portfolio project

Understanding pretrained CNN models

Image classification demos

📌 Future Improvements

Add custom-trained model

Support more animal categories

Show prediction probabilities

Deploy on Hugging Face Spaces

👩‍💻 Author

Pratiksha Chavan
Engineering Student | Python & AI Enthusiast

⭐ If you like this project, don’t forget to star the repository!
