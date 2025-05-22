# Algerian Forest Fire ML Model

This project predicts the **Fire Weather Index (FWI)** using regression models trained on the Algerian Forest Fires Dataset.

## Project Structure

- `notebooks/`: Contains data exploration and model training Jupyter notebooks.
- `application.py`: Flask app to make predictions via web interface.
- `templates/`: HTML templates for the Flask app.
- `requirments.txt`: Python dependencies.

## ML Models Used
- RidgeCV
- Lasso
- ElasticNet

## Setup Instructions

```bash
# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate

# Install dependencies
pip install -r requirments.txt
