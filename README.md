# 🧠 Customer Churn Prediction App

This is a **deep learning-based web app** built using **Streamlit** to predict whether a customer is likely to churn. It uses an **Artificial Neural Network (ANN)** with:

- **Adam optimizer**
- **ReLU activation** in the hidden layers
- **Sigmoid activation** in the output layer

> ✅ Built with TensorFlow, trained on structured customer data, and deployed as an interactive Streamlit app.

---

## 🚀 Live Demo

👉 [Click here to open the app]([https://your-streamlit-app-link-here](https://ann-classification-churn-2potsfwfqdeouow5otkm3z.streamlit.app/)])

---

## 📊 Tech Stack

| Component         | Tool/Library      |
|------------------|-------------------|
| Frontend UI       | Streamlit         |
| Deep Learning     | TensorFlow/Keras  |
| Data Preprocessing| scikit-learn      |
| Model File        | `model.h5`        |
| Encoders/Scaler   | `pickle`          |

---

## 🧠 Model Architecture

- **Input Layer:** 12 features (after encoding)
- **Hidden Layers:** Dense layers with **ReLU**
- **Output Layer:** 1 neuron with **Sigmoid**
- **Optimizer:** Adam
- **Loss Function:** Binary Crossentropy
- **Use Case:** Binary Classification (churn or not)

---

## 📂 File Structure

ann-classification-churn/
│
├── app.py                      # Streamlit app code
├── model.h5                    # Trained ANN model
├── label_encoder_pickle.pkl    # LabelEncoder for Gender
├── ohe_pickle.pkl              # OneHotEncoder for Geography
├── Scaled_param.pkl            # StandardScaler for feature scaling
├── requirements.txt            # Project dependencies
├── runtime.txt                 # Python version for Streamlit Cloud
└── README.md                   # Project documentation

---

## 🧪 How to Run Locally

1. **Clone the repo**
   ```bash
   git clone https://github.com/nvdpsingh/ANN-Classification-Churn.git
   cd ann-classification-churn

	2.	Create and activate a virtual environment

python3 -m venv venv
source venv/bin/activate       # On Windows: venv\Scripts\activate


	3.	Install the dependencies

pip install -r requirements.txt


	4.	Run the app

streamlit run app.py



⸻

🧾 Sample Inputs

Feature	Type	Example
Geography	Categorical	France
Gender	Categorical	Female
Age	Numeric	35
Credit Score	Numeric	650
Balance	Numeric	35000
Estimated Salary	Numeric	50000
Tenure	Numeric	5
Num of Products	Numeric	2
Has Credit Card	Binary	1
Is Active Member	Binary	1


⸻

📈 Output

The model returns a churn probability:
	•	If > 0.5 → The customer is likely to churn
	•	If ≤ 0.5 → The customer is not likely to churn

⸻

💡 Future Improvements
	•	Add model explainability (SHAP / LIME)
	•	Deploy with Docker or Hugging Face
	•	Improve ANN with hyperparameter tuning
	•	Add user input validation

⸻

📬 Contact

Feel free to connect:
	•	GitHub: nvdpsingh
	•	LinkedIn: [Your LinkedIn](https://www.linkedin.com/in/navdeep-singh-398494b3/)
	•	Email: navdeepsinghdhangar@gmail.com

⸻

⭐ If you like this project, give it a ⭐ on GitHub!
