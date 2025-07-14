 Zomato Data Analysis Project

This project explores Zomato’s restaurant data through a detailed process of cleaning, exploratory data analysis (EDA), and insight generation. The aim is to understand restaurant trends, customer preferences, and how different variables influence ratings and behavior, which can help restaurants and food aggregators make smarter, data-driven decisions.

---

 Objectives

- Clean and preprocess Zomato's restaurant dataset for analysis
- Explore key trends related to restaurant types, services, and customer behavior
- Generate actionable insights using visual and statistical exploration
- Identify potential business strategies based on user preferences and platform dynamics

---

 Tools & Technologies Used

- Python: `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`
- Jupyter Notebook: For EDA and visualization
- Excel: For quick validation and filtering
- Power BI : For creating interactive dashboards

---

 Files & Structure
Zomato-Data-Analysis
├── Zomato_EDA.ipynb # Main notebook with data cleaning and EDA
├── cleaned_zomato_data.csv # Preprocessed, cleaned dataset
├── visuals/ # Exported plots and charts
├── dashboard.pbix # Power BI dashboard 
└── README.md # Project documentation


---

 Key Insights

- ✅ **Most restaurants fall under the 'Dining' category**, making it the dominant service model in the dataset.
- ✅ **Dining restaurants receive the highest number of votes**, indicating stronger customer engagement for dine-in experiences.
- ✅ **Ratings for most restaurants lie between 3.5 and 4.0**, suggesting a high level of satisfaction but room for improvement.
- ✅ **The majority of couple orders are around ₹300**, pointing toward a common budget preference in casual dining.
- ✅ **Offline orders tend to receive lower ratings compared to online delivery**, indicating customer preference for digital convenience and consistent service.
- ✅ **Various types of restaurants were identified**, including cafes, dessert parlors, quick bites, and fine dining establishments.

---

 Data Cleaning Highlights

- Removed nulls, duplicates, and inconsistencies in ratings, votes, and cost fields
- Standardized column headers and string formatting
- Converted categorical and currency columns for analysis compatibility
- Filtered out unrated or zero-vote restaurants to focus on active businesses

---

 Visualizations

Some of the key visualizations created:
- Bar Chart: Count of restaurants by type
- Histogram: Distribution of ratings
- Boxplot: Cost for two vs rating across restaurant types

---

