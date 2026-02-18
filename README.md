📊 Google Play Store App Rating Analysis & Prediction

📌 Project Overview

This project analyses real-world Google Play Store application data and builds a machine learning model to predict app ratings based on different app features such as installs, reviews, category, price, and size.

The goal of this project is to demonstrate practical Data Analysis, Data Cleaning, and Machine Learning skills that are commonly required in Data Analyst and Data Science internships.

---

🎯 Objectives

- Clean and preprocess messy real-world dataset
- Perform exploratory data analysis (EDA)
- Identify trends in Play Store apps
- Build a machine learning model to predict app ratings
- Extract business insights useful for app developers

---

🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn
- Jupyter Notebook / VS Code

---

📂 Dataset

The dataset contains information about Google Play Store applications including:

- App Name
- Category
- Rating
- Reviews
- Size
- Number of Installs
- Type (Free/Paid)
- Price
- Content Rating
- Genres
- Android Version

---

⚙️ Project Workflow

1️⃣ Data Cleaning

- Removed invalid records
- Handled missing values
- Converted installs, reviews, and price into numeric format
- Standardized app size values

2️⃣ Exploratory Data Analysis

- Top app categories
- Rating distribution
- Relationship between installs and ratings
- Free vs Paid app comparison

3️⃣ Machine Learning

- Encoded categorical variables
- Split dataset into training and testing data
- Trained a Random Forest Regressor
- Evaluated performance using:
  - Mean Squared Error (MSE)
  - R² Score

---

📈 Results

The model successfully learned patterns between app features and ratings.
Key factors influencing ratings include:

- Number of Reviews
- Install Count
- App Category
- App Size

---

💡 Business Insights

- Highly installed apps generally maintain stable ratings.
- Free apps dominate the Play Store ecosystem.
- Certain categories consistently receive higher user ratings.

---

🚀 How to Run the Project

1. Clone Repository

git clone https://github.com/your-username/playstore-rating-project.git

2. Install Dependencies

pip install -r requirements.txt

3. Run Program

python playstore_analysis.py

---

📷 Sample Output

- Dataset summary
- Category insights
- Model accuracy metrics
- Feature importance ranking

---

🎓 Learning Outcomes

Through this project, I learned:

- Handling real-world messy datasets
- Data preprocessing techniques
- Feature engineering basics
- Building and evaluating ML models
- Converting analysis into actionable insights

---

👨‍💻 Author

Mohamed Arrshin
B.Sc Data Science Student
Chennai, India

---

⭐ Future Improvements

- Deploy model using Streamlit dashboard
- Add real-time prediction interface
- Perform sentiment analysis on app reviews

---

📜 License

This project is created for educational and portfolio purposes.
