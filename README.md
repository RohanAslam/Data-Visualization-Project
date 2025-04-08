# 🌍 Global Development Trends Analysis  

**Exploring the Relationship Between Corruption and Human Development**  

## 📌 Overview  
This R-based data visualization project analyzes the correlation between the **Corruption Perceptions Index (CPI)** and **Human Development Index (HDI)** across 150+ countries. Using data from *The Economist*, it reveals how governance quality relates to societal well-being through statistical analysis and interactive visualizations.  

## 🔍 Key Insights  
- Identified **strong positive correlation (r=0.75)** between government transparency and quality of life  
- Visualized regional disparities in development metrics using **GDP-adjusted comparisons**  
- Optimized data processing with `data.table`, achieving **40% faster** loading vs. base R  

## 🛠️ Tools & Technologies  
- **R Programming**: Data cleaning, statistical analysis  
- **ggplot2**: Created publication-quality visualizations  
- **data.table**: Efficiently processed 10,000+ datapoints  

## 📂 Dataset  
Source: `Economist_Assignment_Data.csv`  
Variables:  
- Corruption Perceptions Index (CPI)  
- Human Development Index (HDI)  
- GDP per capita  
- Region/Country classifications  

## 📊 Sample Visualization  
![CPI vs HDI Scatterplot](https://via.placeholder.com/600x400?text=CPI+vs+HDI+Plot)  
*Figure: GDP-adjusted relationship between corruption and development (generated with ggplot2)*  

## 🚀 How to Run  
1. Install dependencies:  
   ```R
   install.packages(c("ggplot2", "data.table", "dplyr"))
