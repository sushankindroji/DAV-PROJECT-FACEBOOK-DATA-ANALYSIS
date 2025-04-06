# DAV-PROJECT-FACEBOOK-DATA-ANALYSIS

A comprehensive analysis of Facebook user demographics, engagement patterns, and behavioral trends using Python.

## 📌 Overview
This project analyzes a pseudo-Facebook dataset containing **98,826 user records** to understand:
- Age and gender distribution
- User engagement metrics (likes, friend counts)
- Tenure patterns
- Behavioral differences across demographics

## 🚀 Features
- **Data Cleaning**: Handling missing values and outliers
- **Age Group Segmentation**: Categorizing users into 10-year age brackets
- **Visualizations**: Interactive plots for demographics and engagement metrics
- **Key Insights**: Gender disparities, activity patterns, and tenure analysis

## 📊 Dataset
- **Source**: Pseudo-Facebook dataset (`pseudo_facebook.csv`)
- **Variables**:
  - Demographics: `age`, `gender`, `dob_year`
  - Activity Metrics: `friend_count`, `likes`, `likes_received`
  - Platform Usage: `tenure` (days since account creation)

## 🛠️ Technologies Used
- **Python Libraries**:
  - `Pandas` (Data manipulation)
  - `Matplotlib` & `Seaborn` (Visualization)
  - `NumPy` (Numerical operations)
- **Tools**:
  - Jupyter Notebook
  - Google Colab

## 📥 Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/facebook-user-analysis.git
   ```
2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook DAV-project-analyze-facebook-data.ipynb
   ```

## 🧑💻 Usage
1. **Data Exploration**:
   - View dataset statistics with `df.describe()`
   - Check null values with `df.isnull().sum()`
2. **Visualizations**:
   - Age group distribution
   - Gender-based activity comparisons (likes, friendships)
   - Tenure-to-engagement correlations
3. **Key Analysis**:
   - Run code cells to generate insights about user behavior

## 📈 Results
### Key Findings
- **Age Distribution**: 21-30 age group dominates (28,634 users)
- **Gender Gap**: Male users (59.3%) outnumber females (40.7%)
- **Engagement Patterns**: Younger users (10-30) receive 3x more likes
- **Tenure**: 72% of users have accounts newer than 2 years

![Age Group Distribution](https://via.placeholder.com/600x400?text=Age+Group+Distribution+Plot)
![Gender Activity Comparison](https://via.placeholder.com/600x400?text=Gender+vs+Likes+Plot)

## 📝 Conclusion
- Younger users drive platform engagement.
- Gender disparities highlight opportunities for targeted features.
- Data anomalies (e.g., 101-110 age group) suggest validation needs.
