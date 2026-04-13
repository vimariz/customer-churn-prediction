# Customer Churn Prediction

Memprediksi apakah pelanggan dari sebuah agensi pemasaran akan melakukan churn (berhenti menggunakan layanan) menggunakan logistic regression yang dibuat dari awal (from scratch). Termasuk implementasi manual fungsi sigmoid, cost function, dan gradient descent. Model yang telah dilatih kemudian digunakan untuk memprediksi risiko churn pada pelanggan baru.

## Dataset

- - `customer_churn.csv` -- data historis pelanggan dengan fitur: Name, Age, Total_Purchase, Account_Manager, Years, Num_Sites, Onboard_date, Location, Company, Churn
- `new_customers_1.csv` -- data pelanggan baru untuk diprediksi (tanpa label)

## Tech Stack

- pandas, numpy
- matplotlib, seaborn
- scikit-learn (train_test_split, StandardScaler)
- Custom logistic regression (sigmoid, cost function, gradient descent dibuat manual)

## Results

Model logistic regression kustom mencapai akurasi sebesar 88.9% pada data uji.

## How to Run

1. Install dependencies: `pip install pandas numpy matplotlib seaborn scikit-learn`
2. Place `customer_churn.csv` and `new_customers_1.csv` in the project directory.
3. Run `customerChurn.ipynb` from start to finish. Predictions for new customers are displayed at the end.
