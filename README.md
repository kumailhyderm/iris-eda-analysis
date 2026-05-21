**Iris Dataset - Exploratory Data Analysis (EDA)**

A beginner-friendly data analysis project using the classic **Iris dataset**. This notebook walks through loading, exploring, and visualizing the data to uncover patterns across three flower species.



**Project Overview**

The Iris dataset contains 150 samples from three species of iris flowers (**setosa, versicolor, virginica**), with four features measured per sample: sepal length, sepal width, petal length, and petal width.

This project performs:
- Data loading & inspection
- Descriptive statistics
- Visual exploration via multiple chart types



 **Visualizations**

### Sepal Length vs Petal Length
![Scatter Plot](https://raw.githubusercontent.com/kumailhyderm/iris-eda-analysis/main/scatter_plot.png) 

| Chart | Insight |
|---|---|
Scatter Plot – Sepal Length vs Petal Length | Setosa flowers clearly cluster with shorter petals |
Histogram – Sepal Length Distribution | Sepal length is roughly normally distributed |
Box Plot – Petal Length by Species | Versicolor and Virginica show some overlap; Setosa is distinct |



**Tech Stack**

- Python 3.x
- [Pandas](https://pandas.pydata.org/) — data manipulation
- [Matplotlib](https://matplotlib.org/) — base plotting
- [Seaborn](https://seaborn.pydata.org/) — statistical visualizations



 Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/your-username/iris-eda-analysis.git
cd iris-eda-analysis
```

### 2. Install dependencies
```bash
pip install pandas matplotlib seaborn
```

### 3. Run the notebook
```bash
jupyter notebook task1_iris_analysis.ipynb
```


## File Structure

```bash
iris-eda-analysis/
└── task1_iris_analysis.ipynb
```

---

## Dataset

The Iris dataset is built into Seaborn and loaded directly via:
```python
df = sns.load_dataset('iris')
```
Original dataset: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/iris)

---

## Author

**Muhammad Kumail Haider**  
[GitHub](https://github.com/kumailhyderm) · [LinkedIn](https://linkedin.com/in/kumailhyderm)

---

## 📄 License

This project is open-source under the [MIT License](LICENSE).

