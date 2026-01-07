# ITSOLERA AI Data Science Internship – Task 02

## 📌 Task Objective

The goal of this task was to explore and visualize a dataset using Python’s pandas, matplotlib, and seaborn libraries. The objective included reading the dataset, summarizing its structure, and creating visualizations to understand relationships, distributions, and potential outliers in the data.

The dataset used for this task is the **Iris Dataset**, a classic dataset commonly used for machine learning and exploratory data analysis.

---

## 🛠️ My Approach

1. **Loaded the Dataset**
   - Imported the Iris dataset either from a local CSV file or directly using `seaborn.load_dataset('iris')`.

2. **Data Inspection**
   - Used basic pandas methods such as `.shape`, `.columns`, `.head()`, `.info()`, and `.describe()` to understand the structure and summary statistics of the dataset.

3. **Visualization**
   - Created visualizations with `matplotlib` and `seaborn` to analyze the dataset:
     - **Scatter Plot**: To observe the relationships between pairs of features.
     - **Histogram**: To examine the distribution of individual features.
     - **Box Plot**: To detect the spread of values and identify possible outliers.
    

---

## 📊 Results and Insights

- **Dataset Overview**
  - The Iris dataset contains **150 records** with **5 columns** (4 numeric features and a species label).
  - All values are numeric except for the `species` label.
  - No missing values were found in the dataset.

- **Visual Insights**
  - **Scatter plots** showed clear relationships between certain feature pairs and indicated that different species tend to cluster in distinct regions.
  - **Histograms** helped reveal the distribution patterns of measurements like sepal length and petal length, showing differences in frequency across values.
  - **Box plots** highlighted the spread of features and helped identify potential outliers across different species groups.

- **Overall Insight**
  - The visualizations confirmed that certain features (e.g., petal length and petal width) are strong indicators for differentiating species, which could be useful in classification tasks.

---

## 📁 Included Files

- `task2.ipynb` – Jupyter Notebook containing all the code, visualizations, and conclusions from this task.

---

## 📌 Tools Used

- Python (pandas, NumPy)
- matplotlib
- seaborn
