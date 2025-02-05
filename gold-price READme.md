# Gold Price Prediction using LSTM

## Overview
This project builds a deep learning model using LSTM (Long Short-Term Memory) networks to forecast gold prices. The model is trained on historical gold price data and deployed as a **Streamlit web app** for real-time predictions.

## Features
✅ Forecast gold prices for the next **1-30 days**
✅ Interactive Streamlit web app
✅ Uses **LSTM model** for time series prediction
✅ Data normalization with **MinMaxScaler**
✅ Visualization of predicted trends

## Technologies Used
- Python
- TensorFlow/Keras
- Streamlit
- Pandas & NumPy
- Scikit-learn
- Matplotlib

## Installation
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/gold-price-prediction.git
cd gold-price-prediction
```

### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Streamlit App
```bash
streamlit run app.py
```

## Model Training
- The model is built using an **LSTM-based neural network**.
- Data is preprocessed using **MinMaxScaler** to normalize prices.
- The model predicts future gold prices based on past values.

## Usage
- Open the Streamlit web app.
- Select the number of days ahead for prediction.
- Click **"Predict Price"** to see the forecast.

## Example Prediction
```bash
Predicted Gold Price in 7 days: $1923.45
```

## Future Enhancements
🚀 Integrate additional economic indicators (USD Index, Inflation Rate, etc.)
📈 Improve accuracy with hybrid models (LSTM + XGBoost)
🌐 Deploy to a cloud server (AWS/GCP/Heroku)

## Author
- **Your Name**  
- LinkedIn: [Your Profile](https://linkedin.com/in/your-profile)
- GitHub: [Your GitHub](https://github.com/your-username)

---
### ⭐ Star this repo if you found it useful! ⭐

