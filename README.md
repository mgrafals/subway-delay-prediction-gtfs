# Predicting Subway Delays in New York City Using GTFS Data

This project uses MTA's GTFS static and real-time feeds to build a machine learning pipeline that predicts subway delays across the IRT lines (1–7, GS). Using PySpark and Databricks, the project merges schedule and real-time feeds, engineers features, and trains multiple models including Random Forest, Gradient Boosted Trees, and LSTM.

## Highlights
- Integrated GTFS static & real-time data for subway delay prediction
- Built and evaluated Random Forest, GBT, and LSTM models
- Best model (GBT) achieved:
  - RMSE = 1.434
  - MAE = 0.804

## Technologies
- Python, PySpark, Databricks, TensorFlow, Scikit-learn
- GTFS static: [GTFS Schedule Data](https://rrgtfsfeeds.s3.amazonaws.com/gtfs_supplemented.zip)
- GTFS real-time: [MTA Real-Time Feed](https://api-endpoint.mta.info/Dataservice/mtagtfsfeeds/nyct%2Fgtfs)

## Contents
- `Predicting Subway Delays in New York City.ipynb`: Final notebook
- `README.md`: Project overview

## Research Base
Built using insights from:
- Lapamonpinyo et al. (2022)
- Zhou et al. (2024)
- Sarhani & Voß (2024)

## Visualizations
The notebook includes map and trend-based visualizations for top delay stops and temporal patterns.

---

### Usage
1. Clone this repo
2. Open the notebook in Databricks or Jupyter
3. Set paths to GTFS static/real-time files (external)
