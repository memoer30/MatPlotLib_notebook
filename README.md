# Introduction to Matplotlib

A comprehensive Jupyter notebook tutorial covering the fundamentals of data visualization using Matplotlib, NumPy, and Pandas.

## 📊 Overview

This project provides a hands-on introduction to creating visualizations with Matplotlib, one of Python's most popular plotting libraries. The notebook covers everything from basic concepts to advanced customization techniques, with practical examples using real datasets.

## 📁 Repository Contents

- `introduction_to_matplotlib.ipynb` - Main tutorial notebook with code examples and visualizations
- `car-sales.csv` - Sample dataset for automotive sales analysis
- `heart-disease.csv` - Sample dataset for medical data visualization

## 🎯 Topics Covered

### 0. Matplotlib Concepts
- What is Matplotlib and why use it?
- Anatomy of a Matplotlib figure
- Matplotlib's role in the Python data visualization ecosystem

### 1. Two Ways of Creating Plots
- **pyplot API** - Simple, MATLAB-like interface
- **Object-Oriented (OO) API** - Recommended approach (used throughout this tutorial)
- Understanding the Figure and Axes objects

### 2. Plotting with NumPy Arrays
Learn to create the most common plot types:
- **Line plots** - For continuous data trends
- **Scatter plots** - For relationship visualization
- **Bar charts** - Vertical and horizontal bar plots
- **Histograms** - For data distribution analysis
- **Subplots** - Multiple plots in a single figure

### 3. Plotting with Pandas
- Using the Pandas `plot()` wrapper for quick visualizations
- Plotting DataFrame columns directly
- Time series visualization with date indexing

### 4. Plotting Pandas DataFrames with OO Method
Advanced plotting techniques combining Pandas and Matplotlib's OO interface for:
- Line charts from DataFrame columns
- Scatter plots for correlation analysis
- Bar charts for categorical comparisons
- Histograms for distribution analysis
- Complex subplots with multiple data sources

### 5. Customizing Your Plots
- Setting plot limits and ranges
- Color customization and color maps
- Line styles and markers
- Legends and labels
- Title and axis formatting
- Figure size and DPI settings

### 6. Saving Your Plots
- Exporting plots to various formats (PNG, PDF, SVG, etc.)
- Resolution and quality settings
- Best practices for publication-ready figures

## 🚀 Getting Started

### Prerequisites

```bash
pip install matplotlib numpy pandas jupyter
```

### Running the Notebook

1. Clone this repository
2. Navigate to the project directory
3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook introduction_to_matplotlib.ipynb
   ```

## 📚 Key Concepts

### Matplotlib Workflow

```python
# 0. Import and setup
import matplotlib.pyplot as plt
%matplotlib inline

# 1. Prepare data
x = [1, 2, 3, 4]
y = [11, 22, 33, 44]

# 2. Setup plot
fig, ax = plt.subplots(figsize=(10, 10))

# 3. Plot data
ax.plot(x, y)

# 4. Customize plot
ax.set(title="Sample Plot", xlabel="x-axis", ylabel="y-axis")

# 5. Save & show
fig.savefig("plot.png")
plt.show()
```

## 📈 Example Visualizations

This notebook includes practical examples such as:
- Nut butter price comparisons using bar charts
- Normal distribution visualizations with histograms
- Time series data with line plots
- Car sales data analysis
- Heart disease data exploration

## 🛠️ Technologies Used

- **Python 3.x**
- **Matplotlib** - Core plotting library
- **NumPy** - Numerical computing
- **Pandas** - Data manipulation and analysis
- **Jupyter Notebook** - Interactive development environment

## 📖 Learning Outcomes

After completing this tutorial, you will be able to:
- Understand the structure of Matplotlib figures and axes
- Create various types of plots using both NumPy arrays and Pandas DataFrames
- Apply the Object-Oriented API for robust and maintainable visualizations
- Customize plots with colors, styles, and labels
- Create complex multi-panel figures with subplots
- Save publication-quality figures in various formats

## 🤝 Contributing

Feel free to fork this repository and submit pull requests for improvements or additional examples.

## 📝 License

This project is open source and available for educational purposes.

## 🔗 Additional Resources

- [Matplotlib Official Documentation](https://matplotlib.org/)
- [Matplotlib Gallery](https://matplotlib.org/stable/gallery/index.html)
- [Matplotlib Tutorials](https://matplotlib.org/stable/tutorials/index.html)
- [Pandas Visualization Guide](https://pandas.pydata.org/docs/user_guide/visualization.html)

## 👤 Author

Created as an educational resource for learning data visualization with Python.

---

**Note**: This notebook is designed to be code-focused with hands-on examples. The best way to learn is by running the cells and experimenting with the code yourself!
