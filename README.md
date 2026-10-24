# Heart Disease Prediction

A Streamlit app that predicts whether heart disease is likely, using a Logistic Regression model trained on the UCI Cleveland Heart Disease dataset.

**Live demo:** https://heart-disease-app-y87trtzrbzgjscvh9dtcwj.streamlit.app/

## Inputs
Age, sex, chest pain type, and maximum heart rate achieved.

## Model
- Logistic Regression (scikit-learn), 80/20 stratified split
- Test accuracy: ~83% (60 test samples)
- Target: any heart disease (0 = none, 1 = present)

## Files
| File | Purpose |
|---|---|
| `app.py` | Streamlit app |
| `heart_model.pkl` | Trained model |
| `heart_disease.ipynb` | Data cleaning, training, evaluation |
| `processed.cleveland.data` | Dataset (UCI Machine Learning Repository) |
| `requirements.txt` | Dependencies |

## Run locally
```bash
pip install -r requirements.txt
streamlit run app.py
```

> Educational project only. Not a medical device and not for diagnosis.
