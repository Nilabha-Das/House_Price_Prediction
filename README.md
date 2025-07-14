# House Price Prediction 🏠📈

This project predicts house prices in Bengaluru using machine learning. It features a Flask API backend, a web client built with HTML/CSS/JavaScript, and a trained ML model (loaded with pickle) for predictions.

## 📦 Project Structure

```
House_Price_Prediction/
├── client/         # Frontend - HTML, CSS, JavaScript
├── server/         # Backend - Flask API
├── model/          # Pickle model and related files
```

## 🚀 Features

* Predict house prices based on user inputs.
* Flask API to serve the ML model.
* Interactive web interface for end-users.

## 🧠 ML Model

* Dataset: Kaggle Bengaluru House Prices dataset.
* Preprocessing: Outlier removal, feature engineering.
* Algorithm: Linear Regression (or your chosen algorithm).
* Model serialized using `pickle`.

## 💻 Tech Stack

* **Frontend**: HTML, CSS, JavaScript
* **Backend**: Flask (Python)
* **ML**: scikit-learn, pandas, numpy

## 📂 How to Run Locally

1. Clone the repo:

   ```
   git clone https://github.com/Nilabha-Das/House_Price_Prediction.git
   cd House_Price_Prediction
   ```

2. Set up a virtual environment:

   ```
   python -m venv venv
   source venv/bin/activate  # On Windows use venv\Scripts\activate
   ```

3. Install dependencies:

   ```
   pip install -r server/requirements.txt
   ```

4. Start the Flask server:

   ```
   cd server
   python server.py
   ```

5. Open `client/app.html` in your browser.

## 📊 Demo


<img width="1770" height="834" alt="Screenshot 2025-07-14 093154" src="https://github.com/user-attachments/assets/14a58568-74bb-43fb-b9a1-3f7d70dad99f" />

## 📝 License

This project is licensed under the MIT License.

