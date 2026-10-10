# Predicting Offensive Play-Calling & Success in the NFL

## Overview
This project uses NFL play-by-play data from 2009–2016 to analyze offensive play-calling and predict play success using machine learning.

## Research Questions
- Can we predict whether an offense will run or pass?
- What factors contribute most to successful offensive plays?
- Do teams consistently choose the play with the highest predicted probability of success?

## Tools
- Python
- pandas and NumPy
- seaborn and Matplotlib
- scikit-learn
- Logistic Regression
- Random Forest
- GridSearchCV

## Results
- **Play Prediction:** Random Forest achieved approximately 67% accuracy when predicting run versus pass.
- **Play Success:** Models achieved approximately 58–59% accuracy when predicting whether a play would have positive Expected Points Added (EPA).
- **Play Recommendations:** The recommended play type matched the actual play approximately 48% of the time.

## Conclusion
The results suggest that game situations and other variables can help predict offensive play-calling. However, predicting play success is more difficult, showing the challenges of modeling football outcomes.

## Dataset
NFL Play-by-Play (2009–2016), obtained from Kaggle.
https://www.kaggle.com/datasets/maxhorowitz/nflplaybyplay2009to2016?resource=download&select=NFL+Play+by+Play+2009-2016+%28v3%29.csv

## Author
Gracie Lovell
