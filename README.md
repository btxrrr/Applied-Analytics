# Applied Analytics Module / 应用分析模块

This repository contains assignments and projects for the Applied Analytics module. The assignments involve clustering analysis and text analysis using various Python libraries and techniques.

该仓库包含应用分析模块的作业和项目。这些作业涉及使用各种Python库和技术进行聚类分析和文本分析。

## Assignment 1: Clustering Analysis / 作业1：聚类分析

### Problem Statement / 问题陈述
Objective / 目标:
- Cluster analysis is used to split a group of observations into subsets of similar observations. 
  聚类分析用于将一组观测值分成相似观测值的子集。
- Use the provided dataset to create smaller subsets (clusters) based on similar characteristics.
  使用提供的数据集根据相似特征创建较小的子集（聚类）。
- Use Python libraries (e.g., Jupyter Notebook) to perform clustering and create visualizations.
  使用Python库（例如，Jupyter Notebook）进行聚类并创建可视化。
- Summarize and interpret the clusters, providing insights on key factors affecting used car sales, pricing, and demand.
  总结和解释聚类，提供有关影响二手车销售、定价和需求的关键因素的见解。

### Dataset / 数据集
- The dataset contains 2059 used car profiles based on past transactions.
  数据集包含2059个基于过去交易的二手车档案。
- Features include: Make, Model, Price, Year, Kilometer, Fuel Type, Transmission, Color, Owner, Seller Type, Engine (Cc), Max Power, Max Torque, Drivetrain, Length, Width, Height, Seating Capacity, and Fuel Tank Capacity.
  特征包括：制造商、型号、价格、年份、公里数、燃料类型、传动方式、颜色、车主、卖家类型、引擎（排量）、最大功率、最大扭矩、驱动方式、长度、宽度、高度、座位数和油箱容量。

### Suggested Tasks / 建议任务
#### Step 1 – Clustering and Visualization of Numerical Data / 第一步 – 数值数据的聚类和可视化
- Perform data exploration and descriptive analysis (e.g., info(), describe(), histograms, boxplots).
  进行数据探索和描述性分析（例如，info()、describe()、直方图、箱线图）。
- Handle missing values and outliers appropriately.
  适当地处理缺失值和异常值。
- Prepare numerical data for clustering (e.g., scaling).
  准备用于聚类的数值数据（例如，缩放）。
- Build two clustering models: K-means and Hierarchical.
  构建两个聚类模型：K-means和层次聚类。
- Determine the optimal number of clusters using metrics like SSE and Silhouette Scores.
  使用SSE和轮廓系数等指标确定最佳聚类数。
- Visualize the clusters using tools like Matplotlib.
  使用Matplotlib等工具可视化聚类。
- Compare and select the preferred model for further exploration.
  比较并选择首选模型以进行进一步探索。
## Assignment 2: Text Analysis / 作业2：文本分析

### Problem Statement / 问题陈述
Objective / 目标:
- Solve various text analysis problems using Python.
  使用Python解决各种文本分析问题。
- Use a subset of a Reddit dataset with 5000 articles across 5 labels: 'soccer', 'snowboarding', 'triathlon', 'judo', and 'surfing'.
  使用包含5000篇文章的Reddit数据集子集，这些文章分为5个标签：“足球”、“滑雪板”、“铁人三项”、“柔道”和“冲浪”。

### Dataset / 数据集
- Columns: text (Reddit post), category (label).
  列：文本（Reddit帖子）、类别（标签）。

### Suggested Tasks / 建议任务
#### Step 1 – Text Data Preprocessing / 第一步 – 文本数据预处理
- Download the dataset (reddit_5.csv).
  下载数据集（reddit_5.csv）。
- Cleanse the text data using modules like NLTK and Regular Expressions.
  使用NLTK和正则表达式等模块清理文本数据。
- Transform the text data using Bag of Words and TF-IDF techniques.
  使用词袋和TF-IDF技术转换文本数据。

#### Step 2 – Text Data Understanding / 第二步 – 文本数据理解
- Extract keywords using the TF-IDF matrix.
  使用TF-IDF矩阵提取关键词。
- Analyze the keywords using Association Rule Mining and other methods like WordCloud.
  使用关联规则挖掘和WordCloud等其他方法分析关键词。

#### Step 3 – Summarize the Findings / 第三步 – 总结发现
- Summarize the work and provide suggestions for further improvements.
  总结工作并提供进一步改进的建议。

## How to Use / 使用方法
1. Clone the repository:
```
git clone https://github.com/btxrrr/Applied-Analytics.git
```

## Assignment 1 / 作业1
1. Navigate to the Assignment1_Clustering directory and explore the notebooks:
```
cd Assignment1_Clustering/Notebooks
```
2. Open the Jupyter Notebooks Clustering_KMeans.ipynb and Clustering_Hierarchical.ipynb to see the clustering analysis.
   打开Jupyter笔记本 Clustering_KMeans.ipynb 和 Clustering_Hierarchical.ipynb 以查看聚类分析。

## Assignment 2 / 作业2
1. Navigate to the Assignment2_TextAnalysis directory and explore the notebooks:
```
cd Assignment2_TextAnalysis/Notebooks
```
2. Open the Jupyter Notebooks Text_Preprocessing.ipynb and Text_Analysis.ipynb to see the text analysis.
   打开Jupyter笔记本 Text_Preprocessing.ipynb 和 Text_Analysis.ipynb 以查看文本分析。
