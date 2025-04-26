# 🌱 Crop Recommendation System using Machine Learning

A modern, web-based crop recommendation system built using a Random Forest classifier and deployed with Flask. Given soil and environmental conditions, it intelligently recommends the most suitable crop to cultivate. Powered by a trained machine learning model and wrapped in a beautiful, animated interface.

---

## 🔍 Problem Statement

Farmers often struggle to choose the most appropriate crop based on soil nutrients, temperature, humidity, pH, and rainfall. This project addresses that by predicting the optimal crop using a trained ML model based on real-world agricultural data.

---

## 🧠 Tech Stack

- **Machine Learning:** Random Forest Classifier
- **Preprocessing:** MinMaxScaler
- **Frontend:** Tailwind CSS + HTML + Lottie animations
- **Backend:** Python Flask
- **Deployment:** Localhost (can be hosted on Render/Heroku)

---

## 📦 Dataset

- Dataset: `Crop_recommendation.csv`
- Features:
  - `N` - Nitrogen
  - `P` - Phosphorus
  - `K` - Potassium
  - `temperature` (°C)
  - `humidity` (%)
  - `ph`
  - `rainfall` (mm)
- Target: `label` (Recommended Crop)

---

## 🚀 How It Works

1. User inputs values for N, P, K, temperature, humidity, pH, and rainfall.
2. Input is scaled using `MinMaxScaler`.
3. Scaled values are fed to a Random Forest model.
4. The most suitable crop is predicted and shown on screen.

---

## 📁 Project Structure

```
crop-recommendation/
├── app.py                  # Flask backend
├── rf_crop_model.pkl       # Trained RandomForest model
├── minmax_scaler.pkl       # Saved MinMaxScaler
└── templates/
    └── index.html          # Frontend interface
```

---

## 🛠️ How to Run Locally

1. Clone the repo:

   ```bash
   git clone https://github.com/yourusername/crop-recommendation.git
   cd crop-recommendation
   ```

2. Install dependencies:

   ```bash
   pip install flask joblib numpy scikit-learn
   ```

3. Run the app:

   ```bash
   python app.py
   ```

4. Open in browser:

   ```
   http://127.0.0.1:5000/
   ```

---

## 🎨 Frontend Preview

> Features a clean layout, pastel color palette, animated Lottie graphics, and responsive design using Tailwind CSS.

---

## 📸 Screenshots

*Add screenshots of your web UI here!*

---

## 📌 Future Improvements

- Add prediction confidence scores
- Suggest top 3 crops based on probabilities
- Host the app online (Render/Heroku)
- Add dark mode & mobile PWA support

---

## 🤝 Contributions

Contributions, issues and feature requests are welcome!\
Feel free to check the [issues page](https://github.com/yourusername/crop-recommendation/issues).

---

## 📜 License

This project is licensed under the MIT License.

---

## 👩‍💻 Made with ❤️ by Tanmay 

