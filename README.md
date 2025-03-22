# 📊 Supply Chain Analytics with PySpark & MongoDB

### 🔹 **Project Overview**
- **Objective:** Develop a **Supply Chain Analytics system** to predict product prices using **PySpark ML**.  
- **Technologies Used:**  
  - **Data Storage:** MongoDB  
  - **Data Processing:** PySpark  
  - **Machine Learning:** PySpark ML for price prediction  
  - **Database:** MongoDB for storing both raw and predicted data  

---

### 🔹 **Key Features**
✅ **Data Ingestion:**  
- Stores **raw supply chain data** in **MongoDB**.  
- Handles large-scale data efficiently using **PySpark**.  

✅ **ML Model for Price Prediction:**  
- Builds a **regression model** using **PySpark ML**.  
- Performs data preprocessing, feature engineering, and training on distributed data.  

✅ **Prediction Data Storage:**  
- Stores the **predicted prices** back into **MongoDB**.  
- Enables easy retrieval and analysis of forecasted prices.  

---

### 🔹 **Architecture Flow**
1️⃣ **Data Storage:**  
   - Raw supply chain data stored in **MongoDB**.  
2️⃣ **Data Processing with PySpark:**  
   - ETL and transformation performed using **PySpark DataFrames**.  
3️⃣ **ML Model:**  
   - **PySpark ML** regression model predicts product prices.  
4️⃣ **Prediction Storage:**  
   - Stores the **predicted prices** back into MongoDB.