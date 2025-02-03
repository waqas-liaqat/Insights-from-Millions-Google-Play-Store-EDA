# Google Play Store EDA

## Project Overview
This project conducts an in-depth **Exploratory Data Analysis (EDA)** of the Google Play Store dataset, uncovering key insights into app trends, downloads, ratings, pricing models, and category-wise distributions. The dataset contains over **2.3 million** records and **24 features**, making it a large-scale analysis of mobile applications.

## 📂 Folder Structure
The project is structured as follows:
```
📂 Google-Playstore-EDA  
│  
├── 📂 data                 # Raw and processed data  
│   ├── raw_data.csv        # Original dataset  
│   ├── cleaned_data.csv    # Cleaned dataset after preprocessing  
│   ├── data_dictionary.txt # Dataset column descriptions  
│  
├── 📂 notebooks            # Jupyter Notebooks  
│   ├── 01_data_cleaning.ipynb  # Data cleaning and preprocessing  
│   ├── 02_exploratory_analysis.ipynb  # EDA and visualizations  
│   ├── 03_feature_engineering.ipynb  # Feature extraction & transformation  
│   ├── 04_insights_conclusions.ipynb  # Key findings and recommendations  
│  
├── 📂 reports              # Reports and documentation  
│   ├── eda_summary.pdf     # PDF report of EDA  
│   ├── insights.md         # Key findings and insights  
│  
├── 📂 images               # Visualizations and plots  
│   ├── rating_vs_installs.png  
│   ├── top_app_categories.png  
│   ├── correlation_matrix.png  
│  
├── 📂 scripts              # Python scripts for automation  
│   ├── clean_data.py       # Script for data cleaning  
│   ├── eda_plots.py        # Script for generating plots  
│  
├── .gitignore              # Ignore unnecessary files  
├── README.md               # Project documentation  
├── requirements.txt        # List of dependencies  
```

## 📊 Key Insights
### 1️⃣ **App Ratings & Downloads**
- Apps with **higher downloads generally have better ratings**.
- **No strong correlation** found between ratings and downloads for lesser-known apps.

### 2️⃣ **Free vs. Paid Apps**
- **Free apps dominate** both in quantity and download volume.
- **Paid apps do not necessarily have higher ratings.**

### 3️⃣ **Most Popular App Categories**
- **Top 5 by Number of Apps:**
  - Education
  - Music & Audio
  - Tools
  - Business
  - Entertainment
- **Top 5 by Downloads:**
  - Tools
  - Communication
  - Productivity
  - Photography
  - Video Players & Editors

### 4️⃣ **App Size & Popularity**
- **Apps under 200MB** tend to have more downloads.
- Larger apps usually belong to **gaming and entertainment categories**.

### 5️⃣ **Content Ratings & Install Base**
- **Apps rated "Everyone"** have the highest number of installs.
- The **"Teen"** category also has significant popularity.

### 6️⃣ **App Release Trends**
- Most apps were **released in 2020**.
- However, apps from **2015 have the highest total downloads**.
- App age **does not strongly influence download numbers**.

## 🛠️ Technologies Used
- **Python 3.12.0**
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
- **Jupyter Notebook** for data exploration and visualization

## 🔥 How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/waqas-liaqat/waqas-liaqat-Insights-from-Millions-app-Google-Play-Store-EDA.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Google-Playstore-EDA
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

## 📬 Contact
- **Author:** Muhammad Waqas  
- **Email:** waqasliaqat630@gmail.com  
- **GitHub:** [GitHub Profile](https://github.com/waqas-liaqat)  
- **LinkedIn:** [LinkedIn Profile](https://www.linkedin.com/in/muhammad-waqas-liaqat/)  

---
⭐ If you like this project, please give it a star on GitHub! 🚀

