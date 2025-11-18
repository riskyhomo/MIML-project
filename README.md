# MIML Project - Machine Learning in Materials Informatics

## Overview
This project applies machine learning techniques to materials science data analysis. Developed during internship at Bhabha Atomic Research Centre (BARC), this work explores predictive modeling for material properties.

## Project Structure

### Dataset
- `Final_Dataset.csv` - Processed dataset containing material features and target properties
- `W[010].txt`, `W[100].txt` - Crystallographic orientation data files

### Code
- `Graph_code.py` - Main Python script for data visualization and analysis

### Visualizations
- `Actual_vs_predicted_Sample_Index.png` - Model predictions plotted against sample indices
- `Actual_vs_predicted_Scatter.png` - Scatter plot comparing actual vs predicted values
- `Correlation_Heatmap.png` - Feature correlation matrix visualization
- `Feature_importance.png` - Relative importance of features in the model

### Documentation
- `MLMI_MiniProject_report.docx` - Detailed project report with methodology and results

## Key Features
- Machine learning model for material property prediction
- Feature engineering and correlation analysis
- Comprehensive visualization of model performance
- Analysis of crystallographic orientation effects

## Technologies Used
- Python
- Machine Learning libraries (scikit-learn, etc.)
- Data visualization (matplotlib, seaborn)
- Materials informatics domain knowledge

## Results
The model demonstrates predictive capability for material properties. Detailed results and analysis are available in the project report.

## Installation
```bash
# Clone the repository
git clone https://github.com/riskyhomo/MIML-project.git

# Install required packages
pip install numpy pandas matplotlib seaborn scikit-learn
```

## Usage
```python
# Run the visualization code
python Graph_code.py
```
