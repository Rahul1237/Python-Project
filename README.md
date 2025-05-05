# AI-Based Medical Diagnosis Assistant

This application provides disease predictions and medical suggestions based on user-input symptoms. It is built using **Streamlit** and supports real-time health feedback, including:

- Disease description
- Suggested precautions
- Recommended medications
- Diet plans
- Workouts

## Folder Structure

```
.
├── medical_predictor_app.py
├── disease_predictor.py
├── Training.csv
├── description.csv
├── precautions_df.csv
├── medications.csv
├── diets.csv
├── workout_df.csv
```

##  Requirements

Install dependencies using:

```bash
pip install streamlit pandas numpy scikit-learn
```

##  How to Run

Use the following command to launch the Streamlit application:

```bash
python -m streamlit run medical_predictor_app.py
```

This will open the app in your browser where you can select symptoms and view tailored recommendations.

##  Notes

- This app is for educational purposes only and not intended for real medical diagnosis.
- Data sources used are simplified CSVs suitable for projects and demonstrations.
