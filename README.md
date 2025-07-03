# ✈️ Flight Price Prediction using Python & Machine Learning
This project aims to predict flight ticket prices based on various features such as airline, source, destination, number of stops, duration, and more. The model is trained using historical flight data and deployed through a web interface built with HTML and Tailwind CSS.

# 📁 Project Structure
bash
Copy
Edit
Flight_Price_Prediction/
│
├── Flight_Price_Prediction_Using_Python.ipynb   # Jupyter notebook for model building
├── flight.csv                                    # Dataset used for training
├── model.pkl                                     # Trained model (Pickle file)
│
├── index.html                                    # Frontend UI
├── package.json / tailwind.config.js / vite.config.js # Frontend configs
│
├── app.py (optional if using Flask/Streamlit)    # Backend for prediction (if used)
└── README.md                                     # Project overview
# 🚀 Features
Cleaned and preprocessed dataset.

Exploratory Data Analysis (EDA) with visual insights.

Feature engineering (duration conversion, date-time extraction).

Model training using machine learning (e.g., Random Forest, XGBoost).

Evaluation using RMSE, MAE.

Web interface to input flight details and get predicted price.

# 🧠 Technologies Used
Python (pandas, numpy, scikit-learn, matplotlib, seaborn)

Jupyter Notebook

Machine Learning Algorithms (Random Forest, XGBoost)

Frontend: HTML, Tailwind CSS, Vite

Backend: Flask or Streamlit (depending on your implementation)

Model Serialization: Pickle (model.pkl)

# 📊 Dataset
The dataset flight.csv contains historical flight data with features such as:

Airline

Source & Destination

Date of Journey

Number of Stops

Duration

Additional Info

Price (Target)

📈 Model Training
Data Preprocessing: Handling missing values, encoding categorical variables.

Feature Engineering: Extracting hours, minutes from time; calculating journey duration.

Model Used: RandomForestRegressor (with hyperparameter tuning).

Evaluation Metrics: MAE, MSE, RMSE

# 🌐 Web App (Frontend)
Developed using HTML, Tailwind CSS, and Vite.

User can input flight details and get predicted price using the trained ML model.

🔧 How to Run the Project
1. Clone the repository
bash
Copy
Edit
git clone https://github.com/your-username/Flight_Price_Prediction.git
cd Flight_Price_Prediction
2. Install Python dependencies
bash
Copy
Edit
pip install -r requirements.txt
Or install manually:

bash
Copy
Edit
pip install pandas numpy scikit-learn matplotlib seaborn flask
3. Run the backend (Flask or Streamlit)
bash
Copy
Edit
python app.py
4. Run frontend (if using Vite)
bash
Copy
Edit
npm install
npm run dev
📷 Screenshots
Add screenshots of the web interface here (input form and prediction result).

# ✅ Future Enhancements
Deploy on Render, Netlify or Heroku

Add user authentication

Improve UI/UX using React

🙌 Acknowledgements
Dataset Source: [Mention Kaggle or other]

Tailwind CSS Docs

Scikit-learn Documentation

👨‍💻 Author
Ayush Guha
GitHub: Ayush9227
