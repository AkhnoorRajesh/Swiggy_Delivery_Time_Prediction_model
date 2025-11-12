🛵 Swiggy Delivery Time Prediction Model

Project Overview

The Swiggy Delivery Time Prediction model is a Machine Learning project that predicts the estimated delivery time for Swiggy food orders based on several real-world factors such as weather, traffic, order type, and delivery distance.

The project also includes an interactive Streamlit web app that allows users to input order details and get instant predictions for delivery time.

🧠 Features

* Predicts delivery time in minutes using trained regression model

* Interactive web interface built using Streamlit

* Supports user inputs for multiple delivery-related parameters

* Visualizes delivery time prediction results dynamically

* Includes Jupyter notebook for model training and data preprocessing


🧩 Tech Stack

Component	Technology
Programming Language	Python
Web Framework	Streamlit
Machine Learning	Scikit-learn
Data Handling	Pandas, NumPy
Model Storage	Pickle
Notebook Environment	Jupyter Notebook


📂 Project Structure
Swiggy_Delivery_Time_Prediction_Model/
│
├── app.py                               # Streamlit app for prediction
├── model.pkl                            # Trained ML model file
├── swiggy_data.csv                      # Dataset used for training
├── Swiggy Delivery Time Prediction.ipynb # Jupyter notebook for analysis & training
└── README.md                            # Project documentation



⚙️ Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/your-username/Swiggy_Delivery_Time_Prediction_Model.git
cd Swiggy_Delivery_Time_Prediction_Model

2️⃣ Create and activate virtual environment (optional but recommended)
python -m venv venv
venv\Scripts\activate     # On Windows
source venv/bin/activate  # On Mac/Linux

3️⃣ Install dependencies
pip install -r requirements.txt


If you don’t have a requirements.txt, you can create one using:

pip freeze > requirements.txt

4️⃣ Run the Streamlit app
streamlit run app.py




🧾 Input Features
* Feature	Description
* Age	Age of the delivery person
* Ratings	Average customer rating
* Weather	Weather condition during delivery
* Traffic	Traffic intensity level
* Vehicle Condition	Condition of the delivery vehicle
* Type of Order	Type of food order (Snack, Meal, etc.)
* Multiple Deliveries	Number of deliveries made together
* Festival	Indicates if delivery is during festival
* City Type	Urban/Suburban classification
* Distance	Distance between restaurant and customer



🎯 Model Objective

To accurately estimate the delivery time using regression-based machine learning algorithms and help improve delivery efficiency for online food platforms.



🚀 Future Enhancements

Integrate Google Maps API for real-time distance and traffic data



👨‍💻 Author

Akhnoor Rajesh
AI/ML Developer | Data Science Enthusiast 
📧 akhnoorajesh@gmail.com
🔗 LinkedIn Profil : www.linkedin.com/in/akhnoor-rajesh-bb2b13285 
