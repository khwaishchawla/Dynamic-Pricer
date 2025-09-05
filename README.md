# Dynamic-Pricer: Uber Fare Prediction with Machine Learning

An ML-based project to predict Uber fares dynamically using geospatial, temporal, and trip-related features.
This model helps optimize ride pricing by learning patterns from historical data.

🚀 Features

Cleans and preprocesses ride data (distance, pickup/drop location, time, etc.)

Trains ML models (Random Forest, etc.) for fare prediction

Evaluates models with metrics like RMSE & R² Score

Provides visualization of actual vs predicted fares

Easy to extend with new datasets

🛠️ Tech Stack

Language: Python 3.x

Libraries: Pandas, NumPy, scikit-learn, Matplotlib, Seaborn

Models: Random Forest, (optionally XGBoost, Linear Regression)

Tools: Jupyter Notebook



⚙️ Installation

Clone the repo and install dependencies:

git clone https://github.com/<khwaishchawla>/Dynamic-Pricer.git
cd Dynamic-Pricer
pip install -r requirements.txt

▶️ Usage

Run the model training:

python src/train_model.py --data data/sample.csv


Make predictions:

python src/predict.py --input data/test_sample.csv --output predictions.csv


Or explore via Jupyter Notebook:

jupyter notebook notebooks/DynamicPricer.ipynb



🤝 Contributing

Contributions are welcome! Please fork this repo and submit a pull request.
For major changes, open an issue first to discuss what you’d like to change.

