# Finance Loan Approval Prediction App 📊💳

This is a **Machine Learning-powered Loan Approval Prediction App** built with **FastAPI** and deployed on **Render**.  
It allows users (e.g., clients, loan officers, or businesses) to input financial details and instantly receive a prediction on whether a loan application is **Approved ✅** or **Not Approved ❌**.

---

## 🚀 Deployment

This app is currently deployed on **Render**.  
👉 **[Click here to try it live](https://finance-ml-deployment.onrender.com)**  

---

## 🧑‍💻 How It Works
1. Users enter their details (e.g., loan amount, income, credit history, interest rate, etc.) on the web form.
2. The input is validated on both frontend (HTML/JS) and backend (FastAPI).
3. The ML model processes the input and predicts whether the loan is **Approved** or **Not Approved**.
4. The result is displayed instantly on the user interface.

---

## 🔗 Learn More About the Model (Backend)
The machine learning model behind this app was built and explained in detail in a separate repository.  
👉 [Check the Model Training & Data Science Process](https://github.com/Freddy-Apaka/Finance_Prediction_model)

This backend repository covers:
- Data preprocessing
- Feature engineering
- Model training & evaluation
- Saving the trained model (`model.pkl`)

---

## ⚙️ Local Development

If you want to run this app locally:

```bash
# Clone the repo
git clone https://github.com/Freddy-Apaka/ml_finance_render_deployment.git
cd ml_finance_render_deployment

# Create virtual environment (optional)
python -m venv venv
source venv/bin/activate   # (Linux/Mac)
venv\Scripts\activate      # (Windows)

# Install dependencies
pip install -r requirements.txt

# Run FastAPI app
uvicorn app.main:app --reload
Now open your browser at: http://127.0.0.1:8000

📂 Tech Stack

- FastAPI (Backend API + Templating)
- Scikit-learn (Machine Learning model)
- Joblib (Model persistence)
- Pandas & NumPy (Data handling)
- Jinja2 (Frontend templates)
- Render (Deployment)

📜 License

This project is open-source and free to use.
Feel free to fork and adapt it for your own loan prediction or financial ML applications.
