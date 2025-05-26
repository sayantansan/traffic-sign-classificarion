Traffic Sign Classification Web App
This project is a web-based application designed to classify traffic signs using a trained deep learning model. Built with a user-friendly interface, the app allows users to upload images of traffic signs and get instant predictions with labels.

🔍 Overview
Model: CNN trained on the German Traffic Sign Recognition Benchmark (GTSRB) dataset.

Backend: Flask (Python)

Frontend: HTML, CSS, JavaScript

Deployment: Web app interface for real-time traffic sign recognition.

🚀 Features
Upload any traffic sign image and get its classification.

Real-time prediction using a pre-trained deep learning model.

Clean and interactive web UI.

High accuracy on the GTSRB dataset.

🛠️ Technologies Used
Frontend: HTML, CSS, JavaScript

Backend: Python, Flask

Modeling: Keras, TensorFlow

Others: OpenCV, NumPy, PIL

📦 How to Run Locally
Clone the repository:

bash
Copy
Edit
git clone https://github.com/sayantansan/traffic-sign-classificarion.git
cd traffic-sign-classificarion
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the Flask app:

bash
Copy
Edit
python app.py
Open your browser and go to http://127.0.0.1:5000.

🧠 Model Training (Optional)
If you'd like to retrain the model:

Use the GTSRB dataset.

Train using the notebook/script provided in the model_training folder.

Save the trained model as model.h5 in the root directory.

📁 Project Structure
csharp
Copy
Edit
traffic-sign-classificarion/
│
├── static/              # CSS/JS/Images
├── templates/           # HTML templates
├── model.h5             # Trained CNN model
├── app.py               # Flask app
├── requirements.txt     # Python dependencies
└── README.md            # Project documentation
📷 Sample Output

✍️ Author
Sayantan Majee
GitHub • LinkedIn
