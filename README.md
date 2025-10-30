# Habit-pattern-predictor
A machine learning project that predicts next-day productivity based on personal habit patterns — such as sleep duration, screen time, steps, and mood.   It includes a gamified dashboard that awards badges for healthy habits and provides behavioral improvement suggestions.

habit-pattern-predictor/
|-- src/
| |-- main.py
| |-- model.py
| |-- utils.py
|
|-- data/
| |-- sample_data.csv
|
|-- requirements.txt
|-- README.md


# Habit Pattern Predictor (Gamified)
Predict daily productivity from habit data. Includes synthetic data
generator, Linear Regression model, and a gamified Streamlit interface.
## Run locally
1. Create virtualenv
```bash
python -m venv venv
source venv/bin/activate # or venv\\Scripts\\activate on Windows
pip install -r requirements.txt
2. Run Streamlit
streamlit run src/main.py
