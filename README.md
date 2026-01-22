

Developed an LSTM Autoencoder–based anomaly detection system for stock price analysis.

Used historical Alphabet Inc. (Google) closing price data from 2004 to 2020.

Assumed training data contains no anomalies to learn normal price behavior.

Applied StandardScaler for data normalization.

Created 30-day time-series sequences for model training.

Defined anomaly threshold using reconstruction error (MAE) on training data.

Detected abnormal price movements in unseen test data.

Visualized anomalies using Plotly and Matplotlib.

🛠️ Tools & Technologies

Python
TensorFlow / Keras
Pandas, NumPy
Scikit-learn
Plotly, Matplotlib
Jupyter Notebook

📊 Key Outcome
->Successfully identified significant deviations in stock prices as anomalies.

->Provided an interpretable visualization of detected anomalies over time.
