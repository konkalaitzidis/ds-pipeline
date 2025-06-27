# DS Pipeline

A backbone data science pipeline for structured data analysis and modeling, demonstrated on the Titanic dataset. This project provides a reproducible workflow for data loading, exploratory data analysis (EDA), preprocessing, modeling, and evaluation.

## Features
- Data loading and preview
- Exploratory Data Analysis (EDA)
- Data preprocessing (handling missing values, encoding, scaling)
- Model training and evaluation (Random Forest example)
- Visualization of distributions and relationships
- Jupyter notebook for step-by-step workflow

## Project Structure
- `notebooks/pipeline.ipynb`: Main notebook with the full pipeline
- `requirements.txt`: List of Python dependencies
- `data/`: (Optional) Place your own datasets here

## Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/konkalaitzidis/ds-pipeline.git
   cd ds-pipeline
   ```
2. Create and activate a virtual environment:
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
Open the main notebook:
```bash
jupyter notebook notebooks/pipeline.ipynb
```
Follow the steps in the notebook to:
- Load and explore the Titanic dataset (or your own data)
- Perform EDA and visualize key insights
- Preprocess data and train a model
- Evaluate and interpret results

## Dependencies
Key packages:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- jupyter

See `requirements.txt` for the full list and versions.

## License
See `license.txt` for details. 