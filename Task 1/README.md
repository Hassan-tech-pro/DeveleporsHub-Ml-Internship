# Task 1: Exploring and Visualizing the Iris Dataset

## 📋 Task Objective
Learn how to load, inspect, and visualize a dataset to understand data trends and distributions using Python's most popular data analysis libraries.

## 📊 Dataset Used
**Iris Dataset**
- **Source**: Seaborn library (UCI ML Repository)
- **Samples**: 150 iris flower observations
- **Features**: 4 numeric attributes
  - Sepal Length (cm)
  - Sepal Width (cm)
  - Petal Length (cm)
  - Petal Width (cm)
- **Target**: 3 iris species (Setosa, Versicolor, Virginica)

## 🛠️ Skills Demonstrated
✅ **Data Loading & Inspection**: Using pandas to load and explore datasets  
✅ **Descriptive Statistics**: `.info()` and `.describe()` methods for data overview  
✅ **Scatter Plots**: Visualizing relationships between feature pairs  
✅ **Histograms**: Analyzing feature value distributions  
✅ **Box Plots**: Identifying outliers and data spread  
✅ **Data Visualization**: Using matplotlib and seaborn for compelling visualizations  

## 📁 Project Structure
```
DevHub/
├── Task 1/
│   ├── DevHub_ml_task1.ipynb      # Main notebook with all analysis
│   └── README.md                  # This file
```

## 🚀 Getting Started

### Prerequisites
```bash
pip install pandas seaborn matplotlib numpy
```

### Running the Notebook
1. Open `DevHub_ml_task1.ipynb` in Jupyter Notebook or JupyterLab
2. Execute cells sequentially from top to bottom
3. View interactive visualizations and statistical outputs

## 📈 Key Findings

### Dataset Characteristics
1. **Data Completeness**: No missing values (150 × 4 features)
2. **Feature Ranges**:
   - Sepal Length: 4.3-7.9 cm
   - Sepal Width: 2.0-4.4 cm
   - Petal Length: 1.0-6.9 cm
   - Petal Width: 0.1-2.5 cm

### Distribution Insights
- **Sepal Width**: Normal distribution centered around 3.0 cm
- **Petal Length**: Bimodal distribution indicating distinct species characteristics
- **Outliers**: Minimal outliers detected in box plots, confirming data quality

### Feature Relationships
- Strong positive correlation between petal measurements (length-width relationship)
- Sepal measurements show weaker correlation patterns

## 📚 Libraries Used
- **pandas**: Data manipulation and analysis
- **seaborn**: Statistical data visualization
- **matplotlib**: Comprehensive plotting library
- **numpy**: Numerical computing

## ✨ Code Quality
- Clean, modular code structure
- Comprehensive comments explaining each step
- Proper use of docstrings and section headers
- Consistent formatting and style
- Descriptive variable and plot names

## 🔍 Visualizations Included
1. **Scatter Plots**: Sepal and Petal feature relationships
2. **Histograms**: Distribution of sepal width and petal length
3. **Box Plots**: Comprehensive outlier analysis across all features

## 📝 Next Steps
- Perform species-specific analysis (compare iris varieties)
- Conduct correlation analysis between features
- Apply machine learning classifications (e.g., KNN, SVM, Decision Trees)
- Feature engineering and selection
- Build predictive models for species classification

## 🤝 Contributing
This is a learning project for an AI/ML internship. Feel free to fork and extend!

---
**Created**: April 2026  
**Task Level**: Beginner  
**Status**: ✅ Complete
