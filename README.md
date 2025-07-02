# Recurrent Neural Network (RNN) for Wind‑Speed Prediction

This project uses experimental data collected in May 2019 in a 10 × 5 wind tunnel with single hot‑wire anemometry under a tripped‑Reynolds‑number boundary layer to develop a model for predicting wind‑speed measurements.

## Repository Contents

- **[RNN_Wind.ipynb](./RNN_Wind.ipynb)**  
  Jupyter Notebook containing the full source code: data preprocessing (sliding window), Keras LSTM model, training and evaluation.

- **Dataset**  
  **[hot_wire_data.mat](./resource/asnlib/publicdata/hot_wire_data.mat)**  — training data file

  ## Usage

1. Clone this repository.  
2. Ensure your Python environment has TensorFlow/Keras, NumPy, SciPy (for loading `.mat`) installed.  
3. Open and run **[RNN_Wind.ipynb](./RNN_Wind.ipynb)** to reproduce preprocessing, model training, and test‑set evaluation (MAPE < 10%).  
