# ✈️ Airline Passenger Forecasting with LSTM

This project uses a **PyTorch LSTM (Long Short-Term Memory)** model to predict the number of airline passengers based on historical monthly data (`AirPassengers.csv`).

It includes:
- 📈 Feature engineering (seasonality encoding using sin/cos transformations)
- ⚙️ Scaling
- 🔁 Sequence modeling
- 🏋️ Model training
- 🔮 Forecasting the next 12 months
- 📊 Visualizations

---

## 📂 Project Structure

- `air_passenger_forecast_lstm.py` — Main Python script containing:
  - Data preprocessing
  - Model building (LSTM)
  - Model training
  - Evaluation & Visualization
  - Future forecasting

- `AirPassengers.csv` — Dataset containing monthly passenger counts (1950–1960).

---

## 🚀 How to Run

**Clone the repository:**

```bash
git clone https://github.com/your-username/air-passenger-forecast.git
cd air-passenger-forecast

**Install required Python libraries:**

bash
pip install torch pandas numpy matplotlib scikit-learn


**Run the script:**

bash
python air_passenger_forecast_lstm.py


The script will:
- Train the model
- Visualize the actual vs predicted values
- Forecast passenger numbers for the next 12 months

---

## 📊 Output Example

- 📉 Plot comparing **actual** and **predicted** passengers
- 🔮 Forecast plot for the **next 12 months** (shown in red dashed line)

---

## 📚 Techniques Used

- Time Series Forecasting
- Sequence Modeling with LSTM
- Feature Engineering (seasonality using sine and cosine)
- Min-Max Scaling
- PyTorch Deep Learning
- Matplotlib Visualization

---

## ✨ Future Improvements

- 🔧 Hyperparameter tuning for better accuracy
- 📅 Adding more features (holidays, events)
- 🛑 Implement early stopping during training
- 📦 Export trained model for deployment

---
