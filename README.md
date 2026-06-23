# PropIQ — House Price Prediction Platform

PropIQ is a full-stack Machine Learning web application that predicts residential property prices in Hyderabad. The platform utilizes an advanced gradient-boosted regression model (XGBoost) served via a Flask REST API and paired with a modern, responsive user interface.

🚀 **Live Website:**  https://kushal-1609.github.io/PROPIQ/
🧠 **Production API:** https://propiq-go62.onrender.com

---

## 🖥️ Core Features
* **Dynamic Price Prediction:** Instant real-time valuation based on area size, location, property age, formatting, and structural features.
* **Engineered Frontend:** A clean, modern UI featuring client-side input validation, dynamic range updates, and explicit error handling.
* **Robust Backend Architecture:** A production-grade Flask API protected with Cross-Origin Resource Sharing (CORS) and deployed on cloud infrastructure.
* **Advanced ML Pipeline:** Powered by an XGBoost regressor, utilizing a custom scikit-learn preprocessing pipeline (StandardScaler and OneHotEncoder).

---

## 🏗️ System Architecture

1. **Frontend:** Single-page user interface built with HTML5, CSS3 (variables, modern grid/flexbox system), and native asynchronous JavaScript (`Fetch API`).
2. **Backend Engine:** Flask REST API accepting structured JSON payloads via `POST /predict`.
3. **Machine Learning Artifact:** Pre-compiled serialized pipeline (`final_ultimate.pkl`) ensuring high-throughput, low-latency predictions.

---

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3, JavaScript (ES6+)
* **Backend Framework:** Python, Flask, Gunicorn
* **Machine Learning:** XGBoost, Scikit-Learn, Pandas, NumPy, Joblib
* **Deployment:** Render (API Engine), GitHub Pages (Static Hosting)

---

## 🚀 Local Installation & Setup

To run the backend server locally on your machine:

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/Kushal-1609/PROPIQ.git](https://github.com/Kushal-1609/PROPIQ.git)
   cd PROPIQ
