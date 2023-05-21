# Dashboard for Fraud Detections on Streamlit
This is a simple example app for fraud detections that can run on [Streamlit](https://streamlit.io/).

## Abstract
Suppose that we deal with a transaction dataset to create a ML model to predict fraudulent transactions. Then we evaluate such predictions based on a threshold as well as the costs that can occur in each case of true/false positives/negatives. The evaluation is performed using a custom function in `eval.py`. On [Streamlit](https://streamlit.io/), we can freely toggle those parameters to display the overview of the results and the total cost on a dashboard. Here in the CSV file `error_df.csv`, the vaulues of the target variable and the corresponding predictions are given. We run Streamlit on the command line by
```bash
 streamlit run app.py
```

## Installation
For [Streamlit](https://streamlit.io/), run
```bash
pip install streamlit
```

For other packages, we imported the basic `numpy`, `pandas`, and `sklearn`.

## References
