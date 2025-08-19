🚀 Machine Learning Deployment with Flask

Project ini berisi implementasi machine learning dengan pipeline training model (dalam Jupyter Notebook) dan deployment API menggunakan Flask.

📂 Struktur Project

test1.ipynb → Notebook berisi data preprocessing, training model, dan evaluasi.

testing_deploy.py → Script Flask untuk deployment model.

gbr_model.joblib → Model yang sudah dilatih (disimpan dengan joblib).

data/ → Folder berisi dataset (tidak diunggah di repo ini).

⚙️ Teknologi yang Digunakan

Python 3.x

Pandas, NumPy, Scikit-learn (untuk preprocessing & training model)

Joblib (untuk menyimpan model)

Flask (untuk membuat REST API)

📊 Notebook Training Model

File test1.ipynb berisi:

Data loading & preprocessing

Exploratory Data Analysis (EDA)

Training model (Gradient Boosting Regressor)

Evaluasi model

Export model ke gbr_model.joblib