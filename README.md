# LSD.a [Large Scale Data Analysis]
Data Analysis for large datasets and other adventures with kluless the computational marine 
scientist

|  ><(((º> | >°)))彡 | ^ ˘ ω ˘ ^ | <コ:彡 | V=(° °)=V | ( ´・ω・)o |

![LSD.a](https://www.google.com/url?sa=i&url=https%3A%2F%2Ftenor.com%2Fsearch%2Flsd-gifs&psig=AOvVaw2TQoiHN5SjCnx0lagDnomU&ust=1692078491280000&source=images&cd=vfe&opi=89978449&ved=0CBEQjRxqFwoTCMjnv92524ADFQAAAAAdAAAAABAE.gif "It's a trip")

# 📸 Image Data Aggregation and Analysis

This repository contains a collection of tools and scripts for aggregating image data and performing 
various analytics on it.

## Overview

The project began with a series of CSV datasets containing image metadata, labels, and various 
environmental attributes. Our primary focus was to aggregate image data based on certain criteria, 
perform data cleaning, and integrate metadata for deeper insights. We also ventured into deriving 
additional columns from existing data and visualized relationships between different columns using 
linear regression models.

## 🌟 Features

### 🧹 Data Cleaning (｡◕‿◕｡)
- **Normalization**: Our tools are designed to standardize datasets by removing specific prefixes. 
This ensures that data from different sources aligns well and can be compared or merged effectively.
- **Handling Missing Values**: The tools can identify and manage missing or incomplete data, 
ensuring that the datasets are comprehensive and reliable.
- **Outlier Detection**: Identify and manage unusual data points that might distort the analysis.

### 🎨 Data Aggregation (✿◠‿◠)
- **Flexible Grouping**: Depending on the analysis needs, images can be grouped in various ways, 
such as in sets of 6 or 60. This flexibility allows for different levels of granularity in the 
analysis.
- **Interval-based Aggregation**: Data can be aggregated based on specific intervals, providing a 
summarized view of larger datasets.

### 🔗 Data Merging (｡♥‿♥｡)
- **Common Column Merging**: Different datasets can be seamlessly merged based on common columns 
like 'Name' and 'filename', ensuring data integrity.
- **Handling Column Variations**: The tools can manage datasets with different column names, 
ensuring they are correctly aligned and merged.

### 📊 Linear Regression Plots (｡•́︿•̀｡)
- **Visual Insights**: These plots provide a visual representation of the relationships between 
different factors, aiding in understanding correlations and trends.
- **Factor Analysis**: Dive deep into specific factors, such as the relationship between %LICO and 
depth, to derive meaningful insights.

### ✨ Additional Data Derivation (｡>﹏<｡)
- **Column Operations**: New columns can be derived based on operations between existing columns. 
For instance, calculating the seabed by summing depth and altitude provides additional data points 
for analysis.
- **Data Transformation**: Transform data into more useful formats or units, enhancing the depth and 
breadth of the analysis.

## Requirements

- Python 3.x
- Pandas
- Matplotlib, Seaborn (for visualization)



