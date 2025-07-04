# Solar Flare & CME Forecasting Using LSTM

This project uses LSTM-based deep learning to forecast critical solar weather variables such as **Solar Wind Plasma Speed** and **BZ (GSE) Magnetic Field** from NASA's OMNIWeb dataset.

## Objectives
- Predict precursors to solar flares and coronal mass ejections (CMEs)
- Time-series modeling of solar plasma and magnetic field behavior
- Support early warning systems for space weather

## Dataset
- Source: [NASA OMNIWeb](https://omniweb.gsfc.nasa.gov/)
- Features:
  - Scalar B, nT
  - BZ, nT (GSE)
  - SW Proton Density, N/cm³
  - SW Plasma Speed, km/s
  - Kp Index
  - R (Sunspot Number)

## Techniques Used
- Data Cleaning, Parsing, Feature Engineering
- LSTM Neural Networks (TensorFlow/Keras)
- MinMax Scaling, Windowed Time Series
- Model Evaluation, Visualization

## Key Outputs (Saved in /Assets)
- Training & Validation Loss
- Predicted vs Actual values (Scaled & Real Units)
- Zoomed View of Final 100 Days

## Future Extensions
- Forecast actual flare/CME events
- Combine with image-based solar data (from SOHO/SDO)
- Deploy with live feeds for near-real-time alerts

## Author
- **Sai Sarat Chandra**  
*Data Scientist | Solar Weather Modeling | Time Series & Deep Learning Enthusiast*

## Project Focus:  
- Applied Data Science for Space Weather Forecasting  
- Real-time prediction of solar activity drivers using LSTM  
- End-to-end ML workflow design, visualization, and model deployment readiness
