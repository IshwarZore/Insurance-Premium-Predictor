# Insurance Premium Predictor

## 📌 Project Overview
This project is a **Health Insurance Premium Prediction** app built using **Streamlit** and **Machine Learning**. It predicts the insurance premium cost based on user inputs such as age, BMI, smoking habits, and other health-related factors. The machine learning models used for predictions were trained on real-world insurance data.

### 🔗 Live Demo
🚀 [Try the app on Streamlit](https://ishwar-zore-premium-predictor.streamlit.app/)

### 📂 GitHub Repository
📌 [View the source code on GitHub](https://github.com/IshwarZore/Insurance-Premium-Predictor/tree/master)

---

## 🏗️ Features
✅ User-friendly interface built with **Streamlit**  
✅ Predicts insurance premium based on user inputs  
✅ Trained **ML models** for different age groups  
✅ Scalable and easy to deploy  

---

## 🛠️ Installation and Setup
To run the project locally, follow these steps:

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/IshwarZore/Insurance-Premium-Predictor.git
cd Insurance-Premium-Predictor/app
```

### 2️⃣ Install Dependencies
Ensure you have Python installed (preferably **Python 3.10**). Then, install the required dependencies:
```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Streamlit App
```bash
streamlit run main.py
```
The app should now be accessible at `http://localhost:8501` in your browser.

---

## 📊 Machine Learning Model
This project uses **Scikit-Learn** and **XGBoost** to train models on health insurance data. The models are stored in the `artifacts/` directory and loaded during inference. The pipeline includes:
- **Data Preprocessing:** Handling missing values, encoding categorical variables, feature scaling.
- **Model Training:** Different models for young individuals and the rest of the population.
- **Model Storage:** Trained models are saved as `.joblib` files for easy deployment.

---

## 🚀 Deployment
This application is deployed on **Streamlit Cloud** for easy accessibility. To deploy your own version:
1. Push the latest code to a **GitHub repository**.
2. Go to [Streamlit Cloud](https://streamlit.io/cloud) and link your repository.
3. Configure dependencies using `requirements.txt`.
4. Deploy and enjoy your live app!

---

## 🤝 Contributing
Contributions are welcome! If you have suggestions or find any issues, feel free to:
- Open a **GitHub Issue** 📝
- Create a **Pull Request** 🔀

---

## 📜 License
This project is licensed under the **MIT License**.

---

## 📧 Contact
🔹 **Ishwar Zore**  
🔹 GitHub: [@IshwarZore](https://github.com/IshwarZore)  
🔹 Email: ishwar.zore@gmail.com  

