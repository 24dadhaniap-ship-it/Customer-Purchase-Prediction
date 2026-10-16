# Customer Purchase Prediction (E-Commerce)

All four models - Logistic Regression, Decision Tree, KNN and SVM - are implemented **from scratch with NumPy**
in `scratch_ml.py` (no scikit-learn in the models, training script or app).

| File | Purpose |
|---|---|
| `scratch_ml.py` | From-scratch preprocessing, metrics, 4 models, cross-validated tuning |
| `train_models.py` | Trains + tunes all models, saves `.pkl` artifacts (run: `python train_models.py`) |
| `app.py` | Streamlit app (run: `streamlit run app.py`) |
| `ML_PROJECT (2).ipynb` | Full analysis: EDA, models, tuning, evaluation, sklearn correctness check |
| `online_shoppers_intention.csv` | Dataset (12,330 sessions) |

Re-run `python train_models.py` after any change to the models; keep `scratch_ml.py` in the same folder as `app.py`.
