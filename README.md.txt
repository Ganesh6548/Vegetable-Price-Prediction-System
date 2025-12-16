🥦 Vegetable Price Prediction System

A machine learning system that predicts vegetable prices based on various factors like season, temperature, and market conditions.

## 📋 Features

- Predict vegetable prices using machine learning
- Train model on historical vegetable market data
- User-friendly command-line interface
- Support for multiple vegetables and conditions
- Save and load trained models

## 🚀 Installation

1. Clone the repository:
```bash
git clone https://github.com/Ganesh6548/Vegetable-Price-Prediction-System.git
cd Vegetable-Price-Prediction-System
Install required packages:

bash
pip install -r requirements.txt
📁 Project Structure
text
Vegetable-Price-Prediction-System/
├── data/                    # Dataset folder
│   └── Vegetable_market.csv
├── models/                  # Saved models
├── src/                     # Source code
│   ├── __init__.py
│   ├── train.py            # Training script
│   ├── predict.py          # Prediction script
│   └── utils.py            # Utility functions
├── tests/                   # Test files
├── main.py                 # Main application
├── requirements.txt        # Dependencies
└── README.md              # This file
🎯 Usage
1. Train the Model
bash
python main.py
Select option 1 to train a new model with the dataset.

2. Make Predictions
bash
python main.py
Select option 2 and enter:

Vegetable name (e.g., tomato, potato, ginger)

Month (e.g., jan, february, march)

Temperature in Celsius

Disaster status (yes/no)

Vegetable condition (fresh/average/scrap)

3. Run Quick Tests
bash
python main.py
Select option 3 to see example predictions.

📊 Dataset
The system uses Vegetable_market.csv which contains historical data with columns:

Vegetable name

Season

Month

Temperature

Disaster occurrence

Vegetable condition

Price per kg

🤖 Model Details
Algorithm: Random Forest Regressor

Features: 6 input features

Performance: ~85% R² score on test data

Output: Predicted price in ₹ per kg

🧪 Example Predictions
Vegetable	Month	Temp	Disaster	Condition	Predicted Price
Tomato	January	15°C	No	Fresh	₹38.75
Potato	April	32°C	No	Fresh	₹25.50
Ginger	January	15°C	Yes	Fresh	₹130.20
🛠️ Requirements
Python 3.7+

pandas

scikit-learn

joblib

numpy

Install all dependencies:

bash
pip install -r requirements.txt
📝 License
MIT License - see LICENSE file for details

🤝 Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

📧 Contact
For questions or feedback, please open an issue on GitHub.

⭐ If you find this project useful, please give it a star!