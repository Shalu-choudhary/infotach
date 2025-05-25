AI Powered task management system ---> This focused on automating task priority prediction and workload balancing using Machine Learning. The application processes task-related data, performs exploratory data analysis (EDA), applies NLP preprocessing, and builds a classification model to predict task priority. Additionally, it integrates workload balancing using an ML-based approach.
🚀 Features

- ✅ Synthetic task dataset generation (similar to Jira/Trello tasks)
- 🔍 Exploratory Data Analysis (EDA) & cleaning
- 🧹 NLP preprocessing on task descriptions
- 🌲 Priority prediction using Random Forest
- ⚖️ Workload balancing logic using ML
- 🧪 Hyperparameter tuning using GridSearchCV
- 💾 Model saved using `joblib`
- 🌐 Streamlit app for project interaction

- 🛠 Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- NLTK (for text preprocessing)
- Streamlit
- Joblib (for model saving)

## How to Run the Dashboard
### Using the Python Script (`app.py`)

1. Make sure you have Python installed .
2. Install Streamlit if you haven't already:

   ```bash
   pip install streamlit

3. Run Streamlit app with this command:
  streamlit run app.py
