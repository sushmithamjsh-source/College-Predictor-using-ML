# College Predictor using ML

A Flask web app that predicts a suitable engineering college from COMEDK data, using a Random Forest classifier (scikit-learn).

## Project structure

```
Codes/
  app.py                  # Flask web app
  model.py                # Trains the model and saves model.pkl
  COMEDKLIST - final.csv  # Dataset
  templates/              # index.html (input form), result.html (prediction)
Project report.docx       # Project report
flask activation.mp4      # Demo of running the app
```

## How to run

```bash
cd Codes
pip install -r requirements.txt
python model.py   # generates model.pkl (not stored in the repo because of its size)
python app.py
```

Then open http://127.0.0.1:5000 in your browser.
