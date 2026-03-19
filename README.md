#  Wine Data Analysis & Feature Scaling using Python

##  Project Overview

This project demonstrates **Exploratory Data Analysis (EDA)** and **Feature Scaling** on a Wine dataset using Python libraries like Pandas, Seaborn, and Scikit-learn.

The main goal is to:

* Understand data distribution
* Visualize relationships between features
* Apply normalization using MinMaxScaler
* Compare data before and after scaling

---

##  Dataset

* Dataset used: `Wine.csv`
* Selected columns:

  * `Alcohol`
  * `Malic_Acid`
  * `Customer_Segment` (Target variable)

---

##  Technologies Used

* Python 
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

---

##  Exploratory Data Analysis (EDA)

The following visualizations are performed:

* Histogram with KDE for **Alcohol** and **Malic_Acid**
* KDE plots for feature distribution
* Scatter plots to show relationship between features
* Color-coded scatter plots based on customer segments

---

##  Data Preprocessing

### Train-Test Split

* 80% Training data
* 20% Testing data
* Random state: 2

### Feature Scaling

* Applied **MinMaxScaler** to normalize features
* Scaling range: 0 to 1

---

##  Steps Performed

1. Load dataset using Pandas
2. Select relevant columns
3. Perform statistical summary (`describe()`)
4. Visualize distributions using Seaborn
5. Split dataset into training and testing sets
6. Apply MinMax Scaling
7. Convert scaled data back to DataFrame
8. Compare:

   * Before vs After scaling (scatter plots)
   * Before vs After scaling (KDE plots)

---

##  Results & Observations

* Feature scaling transforms data into a uniform range [0,1]
* Helps improve performance of machine learning models
* Visualizations clearly show:

  * Original data spread
  * Normalized data distribution

---

##  How to Run the Project

1. Clone the repository:

```bash
https://github.com/uvmahesh/Normalization-in-Machine-Learning.git
```

2. Navigate to the project folder:

```bash
cd wine-data-analysis
```

3. Install required libraries:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

4. Run the script:

```bash
python wine.ipynb
```

---

##  Output

* Histograms and KDE plots
* Scatter plots (before & after scaling)
* Feature distribution comparison

---

##  Key Learning

* Importance of data visualization
* Understanding feature distribution
* Why normalization is required in ML
* Hands-on use of MinMaxScaler


---
