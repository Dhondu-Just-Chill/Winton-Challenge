# Winton Stock Market Challenge

This repository documents my daily progress on the [Winton Kaggle Challenge](https://www.kaggle.com/c/the-winton-stock-market-challenge).  
The goal of this project is to explore, experiment, and develop predictive models for stock market returns using the provided dataset.

---

## 📂 Project Structure
- `notebooks/` – Jupyter notebooks for EDA, feature engineering, and experiments
- `src/` – Python scripts with reusable code (data loading, preprocessing, models)
- `logs/` – Daily progress notes (research diary style)
- `reports/` – Results, plots, and write-ups
- `data/` – Local data storage (ignored in git, see below)

---

## 📊 Dataset
Due to size limits, the dataset is **not included** in this repo.  
To download it:

```bash
kaggle competitions download -c the-winton-stock-market-challenge -p data/
unzip data/the-winton-stock-market-challenge.zip -d data/
