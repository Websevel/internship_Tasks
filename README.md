# internship_Tasks

# Iris Dataset EDA

## 📌 Objective
The goal of this project is to learn how to load, inspect, and visualize a dataset to understand patterns and distributions. We use the famous Iris flower dataset for exploration.

---

## 📂 Dataset Used
- **Name**: Iris Dataset
- **Source**: Built-in from `seaborn` library
- **Features**:
  - `sepal_length`
  - `sepal_width`
  - `petal_length`
  - `petal_width`
  - `species` (class label)

---

## 🧪 Tasks Performed
1. **Data Loading & Inspection** using `pandas`
   - Shape, columns, head of the dataset
   - Data type info and descriptive statistics

2. **Visualization** using `matplotlib` and `seaborn`
   - **Scatter Plot**: Petal length vs width with species hue
   - **Histogram**: Sepal length distribution
   - **Box Plots**: Identify outliers in each numeric column

---

## 📈 Key Insights
- Each species forms a distinct cluster in petal dimensions.
- Sepal width has a wider spread and visible outliers.
- Petal features offer better separation between species than sepal features.

---

## 🛠️ Libraries Used
- `pandas`
- `matplotlib`
- `seaborn`

---

## ✅ Conclusion
Exploratory Data Analysis helped in understanding how well the features differentiate between flower species. These insights can guide model selection in future classification tasks.
