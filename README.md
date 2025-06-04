## ✅ `README.md` for **Lab 2: Students Performance in Exams**

```markdown
# 📊 Students Performance in Exams - Data Preprocessing & Visualization

This project involves preprocessing and visualizing student exam performance data using Python and popular libraries like Pandas and Seaborn.

---

## 📌 Objective

Perform the following tasks on the dataset:
- Remove low-variance features
- Handle missing values
- Remove outliers
- Visualize feature relationships

---

## 📂 Dataset

- **Name**: Students Performance in Exams  
- **Source**: [Kaggle Dataset Link](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)

---

## 🧪 Preprocessing Steps

1. **Load** the dataset
2. **Remove constant features** using VarianceThreshold (cut-off = 0.5)
3. **Handle missing values**:
   - Numerical: replace with **mean**
   - Categorical: replace with **mode**
4. **Remove outliers** from at least two numerical columns using the **IQR method**

---

## 📈 Visualizations

1. **Pairplot** to explore numerical variable relationships  
2. **Heatmap** to visualize correlations between scores

---

## 📝 Observations

- **Pairplot**: Shows positive correlation between math, reading, and writing scores.
- **Heatmap**: Highest correlation observed between **reading** and **writing** scores.

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🧠 How to Run

1. Clone the repository:
```bash
git clone https://github.com/your-username/students-performance-analysis.git
cd students-performance-analysis
