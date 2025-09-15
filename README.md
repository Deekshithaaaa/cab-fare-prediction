# cab-fare-prediction

Cab Fare Prediction

Project Overview:
Developing a machine learning pipeline to predict cab fares using open-source NYC taxi trip data.
The project demonstrates data cleaning, exploratory analysis, feature engineering, and regression modeling in Python.
Work is documented in Jupyter Notebooks and version-controlled via GitHub for reproducibility.

Tech Stack:
Python 3.10
Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn
Tools: Jupyter Notebook, Git/GitHub, Anaconda

Project Structure:
cab-fare-prediction/
│── data/
│   └── train_sample_50k.csv   # sampled dataset
│── notebooks/
│   └── cab_fare_EDA.ipynb     # main analysis notebook
│── README.md

Dataset:
Source: Kaggle – NYC Taxi Fare Prediction
Original size: ~55M rows (10GB)
Sample used for analysis: 50,000 random rows (train_sample_50k.csv)

Setup Instructions:
Clone this repo:
git clone https://github.com/Deekshithaaaa/cab-fare-prediction.git
cd cab-fare-prediction

Create & activate conda environment:
conda create -n cabfare python=3.10 -y
conda activate cabfare


Install dependencies:
conda install -c conda-forge pandas numpy matplotlib seaborn scikit-learn jupyterlab -y

Launch Jupyter Notebook:
jupyter lab

Deliverables:
* Week 1 – Environment setup, dataset sampling, GitHub repo initialized
* Week 2 – Data Cleaning & Basic EDA
* Week 3 – Feature Engineering
* Week 4 – Model Building (Baseline)
* Week 5 – Model Improvement & Evaluation
* Week 6 – Advanced Visualizations & Insights
* Week 7 – Final Model + GitHub polish
* Week 8 – Final Presentation

Author:
Deekshitha
Mentor: Shraddha Shahane (Dream Venture Labs)
