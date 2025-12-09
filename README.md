# CS_GO_Project-Using-ML
This project focuses on building a machine learning model to predict the winner of a round in Counter-Strike: Global Offensive (CS:GO) based on game snapshot data. It explores data preprocessing, visualization, feature engineering, and classification models to determine which team (Terrorists or Counter-Terrorists) is more likely to win a round.

🎯 Problem Statement

The objective of this project is to analyze CS:GO round snapshot data and use machine learning algorithms to classify which team wins a round. The dataset includes features such as:

Player positions

Equipment values

Bomb status

Weapon types

Team-level stats

These variables are used to build a predictive model identifying the round winner.

🕹 About CS:GO

CS:GO (Counter-Strike: Global Offensive) is a competitive first-person shooter featuring two teams:

Terrorists (T)

Counter-Terrorists (CT)

Winning a round depends on strategies involving:

Economy management

Map control

Utility usage

Team coordination

This makes CS:GO a great dataset for real-world machine learning prediction tasks.

📂 Dataset

The project uses the dataset:

csgo_round_snapshots.csv


This dataset contains round-by-round snapshot details, including:

Player locations

Equipment values

Health

Armor

Bomb state

Team-level aggregated features

🧪 Technologies Used

Python

NumPy, Pandas – Data cleaning & manipulation

Matplotlib, Seaborn – Data visualization

Scikit-learn – Machine learning modeling

📊 Project Workflow
✔ 1. Importing Required Libraries

The notebook loads essential libraries such as NumPy, Pandas, Matplotlib, and Seaborn.

✔ 2. Loading the Dataset

The dataset is read using:

df = pd.read_csv('csgo_round_snapshots.csv')

✔ 3. Exploratory Data Analysis (EDA)

The EDA section visualizes:

Win distribution

Equipment values

Heatmaps

Bomb statuses

Player positions

✔ 4. Data Preprocessing

Includes:

Handling missing values

Encoding categorical variables

Dropping redundant columns

Scaling numeric features

✔ 5. Model Building

Machine learning models explored may include:

Logistic Regression

Random Forest

Decision Trees

Gradient Boosting

Models are evaluated on accuracy and classification metrics.

✔ 6. Final Prediction

The best model is selected and used to predict the winning team for each round.

🚀 Future Improvements

Hyperparameter optimization

Feature selection using SHAP

Deployment as a web app

Integration with real-time CS:GO APIs

📁 Project Structure
├── CS_GO_Project.ipynb
├── csgo_round_snapshots.csv
└── README.md

🙌 Contributions

Contributions are welcome!
Feel free to open issues or submit pull requests.

📜 License

This project is licensed under the MIT License.
