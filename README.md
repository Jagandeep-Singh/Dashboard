
# 🛳️ **Titanic Data Dashboard Report**

This report outlines a stepwise approach to analyzing Titanic passenger data. It describes the process from raw data acquisition to dashboard creation, highlighting the filters, visualizations, insights, and final conclusions.

---

## 🔗 **Raw Data**

- **Source**: The original dataset was obtained in CSV format.  
  - 📂 **[Titanic-Original.csv](https://github.com/Jagandeep-Singh/Titanic/blob/main/Titanic-Original.csv)**  
- **Overview**: This dataset contains information about passengers aboard the Titanic, including demographic details, ticket information, survival status, and embarkation points.

---

## 🛠️ **Data Cleaning**

- **Script Used**: The raw data was cleaned and prepared for analysis using a Python script.  
  - 📜 **[Titanic_data_cleaning.ipynb](https://github.com/Jagandeep-Singh/Titanic/blob/main/Titanic_data_cleaning.ipynb)**  

### **Cleaning Steps**:
1. Removed duplicates and irrelevant columns.  
2. Handled missing values in columns like age and fare by imputing medians or means.  
3. Standardized column names and formats for consistency.  
4. Created new derived columns, such as family size, for additional insights.  

- **Output File**:  
  - 📂 **[Titanic_Cleaned.csv](https://github.com/Jagandeep-Singh/Titanic/blob/main/Titanic_Cleaned.csv)**  

---

## 📊 **Step 3: Dashboard Creation**

### **Filters Applied**  
The dashboard allows users to refine the data using the following filters:  
- **Gender**: Male/Female  
- **Survival Status**: Deceased/Survived  

### **Visualizations Used**  

#### 1️⃣ **Line Chart**  
- **Purpose**: Analyze ticket class distribution against average fares.  
- **Axes**:  
  - X-Axis: Passenger ID  
  - Y-Axis: Average Fare  
- **Legend**: Ticket Class (1, 2, 3)  

#### 🍩 **Donut Chart**  
- **Purpose**: Visualize passenger distribution by embarkation point.  
- **Segments**:  
  - Southampton: 🚢 646 passengers (72.5%)  
  - Cherbourg: 🌍 168 passengers (18.86%)  
  - Queenstown: 🏞️ 77 passengers (8.64%)  

---

## 🔍 **Step 4: Insights Drawn**

### **Demographic Patterns**
- **Total Passengers**: 891  
- **Average Age**: 30 years  
- **Average Fare**: $32.20  

### **Key Insights**
1. **Embarkation Points**:  
   - Passengers from **Southampton** dominate the SibSp category, suggesting more family group travels from this point.  
2. **Family Size**:  
   - Ticket number **382652** has the largest family size for passengers embarked at **Queenstown**.  

3. **Ticket Class and Fare**:  
   - Higher ticket classes (Class 1) exhibit higher average fares, aligning with luxury offerings.

---

## 🌟 **Step 5: Conclusion**

The Titanic dashboard provides a comprehensive, interactive exploration of passenger data. By applying filters, users can uncover nuanced insights into survival rates, fare distribution, and demographic characteristics. This project demonstrates:  
1. The influence of embarkation points on passenger demographics.  
2. The correlation between ticket class and fare prices.  
3. The usefulness of data cleaning in enhancing analysis accuracy.  

---

## ✨ **Explore the Resources**

- **Interactive Dashboard**: [Titanic Dashboard](https://app.powerbi.com/links/fTxyKr0d92?ctid=af7f165a-b051-4c11-8e3f-ad9d5dec1d42&pbi_source=linkShare)  
- **Original Data**: [Titanic-Original.csv](https://github.com/Jagandeep-Singh/Titanic/blob/main/Titanic-Original.csv)  
- **Python Script**: [Titanic_data_cleaning.ipynb](https://github.com/Jagandeep-Singh/Titanic/blob/main/Titanic_data_cleaning.ipynb)  
- **Cleaned Data**: [Titanic_Cleaned.csv](https://github.com/Jagandeep-Singh/Titanic/blob/main/Titanic_Cleaned.csv)  

Let us know how we can improve this report or dashboard! 🚀
