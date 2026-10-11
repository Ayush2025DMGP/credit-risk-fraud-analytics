# Credit Risk and Fraud Analytics - Trimester 1 Project

This is a learning project built with synthetic data only. No real customer or bank data is used.

## Files
- `Credit_Risk_EDA_Trimester1.ipynb`: full project, synthetic data generator, EDA, plots, probability/statistics, baseline logistic regression, linear algebra example, expected-loss illustration, and risk recommendations.
- `data/application_data.csv`: current loan applications and simulated outcome.
- `data/previous_application.csv`: synthetic historical applications.
- `data/repayment_history.csv`: synthetic post-loan instalment history.
- `data/transactions.csv`: synthetic transaction data for fraud-pattern analysis.
- `data/data_dictionary.csv`: descriptions of important fields.
- `data/sample_scored_applications.csv`: small sample from the test-set scores.
- `figures/`: charts created by the notebook, also used in the PDF report.
- `Credit_Risk_Banking_Stakeholder_Report.pdf`: summary for hypothetical business, operations, risk, and IT stakeholders.

## Run
Open `Credit_Risk_EDA_Trimester1.ipynb` in Jupyter or Google Colab and run all cells. The first generator cell recreates the CSV data with a fixed random seed. The notebook uses common beginner-friendly libraries: NumPy, Pandas, Matplotlib, Seaborn, SciPy, and scikit-learn.

## Important limits
All labels and results are simulated. The model is a baseline exercise, not suitable for real lending or fraud decisions. The 45% LGD and 20% manual-review threshold are assumptions for illustration only.
