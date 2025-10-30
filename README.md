# 🌸 Exploratory Data Analysis (EDA) on Iris Dataset

This project performs **Exploratory Data Analysis (EDA)** on the classic **Iris flower dataset** using Python.  
The goal is to clean, analyze, visualize, and understand the dataset’s patterns before applying Machine Learning models.

---

## 📊 Dataset Overview
The dataset contains **150 rows × 5 columns**:
- SepalLengthCm  
- SepalWidthCm  
- PetalLengthCm  
- PetalWidthCm  
- Species  

Each row represents a flower observation with its measurements and class.

---

## 🧹 Steps Performed
1. **Data Cleaning**
   - Checked shape, datatypes, missing values, duplicates  
   - Removed duplicates and corrected formatting  

2. **Descriptive Statistics**
   - Calculated Mean, Median, Mode, Min, Max, Variance, and Standard Deviation  

3. **Outlier Detection**
   - Used IQR and Z-Score methods to identify outliers  

4. **Visualization**
   - Histograms and Boxplots  
   - Pairplots with `hue='Species'`  
   - Correlation Heatmap  
   - Scatter and Distribution plots  

5. **Feature Engineering**
   - Scaling and normalization (MinMaxScaler, StandardScaler)  
   - Encoding categorical variables (LabelEncoder, One-Hot Encoding)  

6. **Dimensionality Reduction**
   - Applied **PCA (Principal Component Analysis)** for 2D visualization  
   - PC1 and PC2 together explained ~96% variance  

---

## 🔍 Key Findings
- Dataset is **clean**, with no missing values.  
- **PetalLengthCm** and **PetalWidthCm** are the most influential features for species separation.  
- PCA confirmed clear species clustering in 2D space.  
- Data is ready for classification model building.

---

## 🧠 Tools & Libraries
- **Python**
- **Pandas, NumPy**
- **Matplotlib, Seaborn**
- **Scikit-learn**
- **Google Colab**
- **GitHub**

---

## 📈 Visualization Samples
*(Insert screenshots of your plots if you want)*  
- Pairplot (with hue)  
- Correlation Heatmap  
- PCA Scatter Plot  

---

## 🏁 Conclusion
EDA helped in understanding the dataset structure, feature relationships, and outliers.  
These insights can guide model selection and improve classification accuracy.

---

## 👨‍💻 Author
**Ratnadip Ganesh Doke**  
📧 [ratnadipdoke1712@gmail.com]  
💻 [GitHub Profile](https://github.com/your-username)
