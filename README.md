# 🎓 Student Success Predictor

A **machine learning-powered Streamlit web app** that predicts whether a student is likely to succeed academically based on their personal, financial, and academic background.

---

## 🚀 Live Demo

👉 [Click here to try the app](https://your-app-name.streamlit.app)  
*Replace with your actual Streamlit Cloud link*

---

## 📦 Features

- 🔍 Predict student success using multiple ML models: KNN, Decision Tree, and Random Forest  
- 🔁 Option to compare all models using majority voting  
- 🧑‍💻 Interactive UI with user-friendly inputs  
- 🎉 Visual feedback (balloons, snow, emoji) based on prediction result  

---

## 🧠 Models Used

### ✅ K-Nearest Neighbors (KNN)  
### 🌲 Decision Tree  
### 🌳 Random Forest

All models are pre-trained and saved as `.pkl` files using `joblib`.

---

## 🛠️ How to Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/hassan3208/Student_dropout_model.git
cd Student_dropout_model
2. Create and activate a virtual environment (optional but recommended)
bash
Copy
Edit
python -m venv venv
venv\Scripts\activate  # On Windows
3. Install the requirements
bash
Copy
Edit
pip install -r requirements.txt
4. Run the app
bash
Copy
Edit
streamlit run app.py
🗂️ Folder Structure
plaintext
Copy
Edit
Student_dropout_model/
├── app.py                  # Main Streamlit application
├── knn_model.pkl           # Pre-trained KNN model
├── tree_model.pkl          # Pre-trained Decision Tree model
├── rf_model.pkl            # Pre-trained Random Forest model
├── requirements.txt        # List of required Python packages
└── README.md               # Project documentation
📊 Input Features
Age, gender, marital status, international student status

Course and application mode

Parent education and occupation

Financial aid, debt, tuition payment status

Academic performance in 1st and 2nd semesters

💡 Inspiration
This project aims to help educational institutions identify students at risk of dropping out or failing, enabling early intervention and support.

📬 Contact
Made with ❤️ by Hassan Imran
Feel free to open issues or contribute via pull requests.
