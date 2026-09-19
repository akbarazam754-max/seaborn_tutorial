# seaborn_tutorial
**GitHub Repository Description:**  > 🎨 A beginner-friendly Seaborn tutorial covering statistical data visualization, including scatter plots, bar plots, histograms, box plots, heatmaps, pair plots, and more using Python, Pandas, and Matplotlib.
# 🎨 Seaborn Tutorial

Welcome to my **Seaborn Tutorial** repository! 🚀

This repository contains my learning, practice, and examples of **Seaborn**, a Python library used for creating attractive and informative statistical data visualizations.

This is part of my journey toward **Data Science, Machine Learning, and AI**.

---

## 📌 What is Seaborn?

**Seaborn** is a Python data visualization library built on top of **Matplotlib**.

It makes it easier to create statistical graphs and provides better-looking default styles.

Seaborn works especially well with **Pandas DataFrames**.

---

## 📚 Topics Covered

### 1. Introduction to Seaborn

* Installing Seaborn
* Importing Seaborn
* Understanding Seaborn with Matplotlib
* Working with Pandas DataFrames

### 2. Line Plot

* Creating line plots
* Using `x` and `y`
* Adding `hue`
* Customizing plots

### 3. Bar Plot

* Creating bar plots
* Comparing categories
* Using `hue`

### 4. Count Plot

* Counting categorical values
* Visualizing frequency distributions

### 5. Scatter Plot

* Visualizing relationships between variables
* Using `hue`
* Using `size`
* Using `style`

### 6. Histogram

* Understanding data distribution
* Using bins
* Adding KDE

### 7. Box Plot

* Understanding median
* Quartiles
* IQR
* Identifying outliers
* Comparing distributions

### 8. Violin Plot

* Understanding data distribution
* Combining box plot and KDE concepts

### 9. Heatmap

* Creating correlation heatmaps
* Understanding color-based data representation
* Using `pivot()` for structured data

### 10. Pair Plot

* Visualizing relationships between multiple variables
* Understanding pairwise relationships

### 11. Styling and Customization

* Titles
* Labels
* Legends
* Color palettes
* Figure size
* Plot styles

---

## 💻 Basic Example

```python
import seaborn as sns
import matplotlib.pyplot as plt

# Load sample dataset
tips = sns.load_dataset("tips")

# Create a scatter plot
sns.scatterplot(
    data=tips,
    x="total_bill",
    y="tip",
    hue="time"
)

plt.title("Total Bill vs Tip")
plt.show()
```

---

## 📊 Dataset Used

During practice, I work with Seaborn's built-in datasets such as:

* `tips`
* `iris`
* `titanic`
* `penguins`

These datasets are useful for learning data visualization and statistical analysis.

---

## 🛠️ Technologies Used

* **Python**
* **Seaborn**
* **Matplotlib**
* **Pandas**
* **Jupyter Notebook / VS Code**

---

## 🎯 Learning Goals

The main goals of this repository are:

* Learn Seaborn fundamentals
* Create statistical visualizations
* Understand different types of plots
* Practice working with Pandas DataFrames
* Learn how to identify patterns and outliers
* Build strong data visualization skills
* Prepare for Data Science and Machine Learning

---

## 📈 Learning Journey

This repository is part of my learning journey:

**Python → NumPy → Pandas → Matplotlib → Seaborn → SQL → Data Science → Machine Learning → AI**

I will continue adding new examples, exercises, and projects as I improve my skills.

---

## 👨‍💻 Author

**AKBAR AZAM**

Computer Science Student
Interested in **AI, Machine Learning, Data Science & Python**

---

⭐ If you find this repository useful, feel free to explore the code and examples!
