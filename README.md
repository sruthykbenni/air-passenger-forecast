<p align="center">
  <img src="https://images.unsplash.com/photo-1549880184-7c39e45b3f07?ixlib=rb-4.0.3&auto=format&fit=crop&w=1350&q=80" alt="Air Travel Banner" width="800"/>
</p>

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
