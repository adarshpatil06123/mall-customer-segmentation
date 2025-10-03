# Mall Customer Segmentation using K-Means Clustering

A comprehensive data science project that applies K-Means clustering to segment mall customers based on their annual income and spending behavior.

![Clustering Results](https://img.shields.io/badge/Clusters-5-blue) ![Python](https://img.shields.io/badge/Python-3.8+-green) ![Scikit--learn](https://img.shields.io/badge/Scikit--learn-Latest-orange)

## 📋 Project Overview

This project analyzes the **Mall Customer Segmentation Dataset** to identify distinct customer groups using unsupervised machine learning. The analysis helps businesses understand customer behavior patterns and develop targeted marketing strategies.

## 🎯 Objectives

- **Data Analysis**: Explore customer income and spending patterns
- **Optimal Clustering**: Use Elbow Method to determine the best number of clusters
- **Customer Segmentation**: Apply K-Means algorithm to group customers
- **Business Insights**: Provide actionable recommendations for each segment
- **Quality Assessment**: Evaluate clustering performance using Silhouette Score

## 📊 Dataset Information

- **Source**: Mall Customer Segmentation Dataset
- **Size**: 200 customers
- **Features Used**: 
  - Annual Income (k$)
  - Spending Score (1-100)
- **Target**: Customer segments (unsupervised learning)

## 🔧 Technologies Used

- **Python 3.8+**
- **pandas** - Data manipulation and analysis
- **numpy** - Numerical computations
- **matplotlib** - Data visualization
- **scikit-learn** - Machine learning algorithms
- **jupyter** - Interactive development environment

## 📈 Key Results

### Customer Segments Identified (K=5):

1. **🎯 Balanced Customers** (40.5%)
   - Income: ~$55k | Spending: ~50
   - Strategy: Regular promotions and loyalty programs

2. **💎 Premium Customers** (19.5%)
   - Income: ~$86k | Spending: ~82
   - Strategy: Luxury products and VIP services

3. **🛍️ Young Spenders** (11.0%)
   - Income: ~$26k | Spending: ~79
   - Strategy: Trendy, affordable products

4. **💰 Cautious Wealthy** (17.5%)
   - Income: ~$88k | Spending: ~17
   - Strategy: Value propositions and quality assurance

5. **💵 Conservative Spenders** (11.5%)
   - Income: ~$26k | Spending: ~21
   - Strategy: Budget options and discounts

### Performance Metrics:
- **Silhouette Score**: 0.554 (Good clustering quality)
- **Optimal Clusters**: 5 (determined by Elbow Method)
- **WCSS**: 44,448.46 at K=5

## 🚀 Getting Started

### Prerequisites
```bash
Python 3.8 or higher
pip package manager
```

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/adarshpatil06123/mall-customer-segmentation.git
cd mall-customer-segmentation
```

2. **Install dependencies**
```bash
pip install -r requirements.txt
```

3. **Run the analysis**
```bash
jupyter notebook Mall_Customer_Clustering_Analysis.ipynb
```

## 📁 Project Structure

```
mall-customer-segmentation/
│
├── Mall_Customer_Clustering_Analysis.ipynb  # Main analysis notebook
├── Mall_Customers.csv                       # Dataset
├── requirements.txt                         # Python dependencies
├── README.md                               # Project documentation
└── images/                                 # Generated plots and visualizations
```

## 📊 Visualizations

The project includes comprehensive visualizations:

- **Elbow Curve**: Optimal K determination
- **Cluster Scatter Plot**: Customer segmentation results
- **Distribution Charts**: Customer distribution across clusters
- **Silhouette Analysis**: Clustering quality assessment

## 🔍 Analysis Workflow

1. **Data Loading & Exploration**
   - Load dataset and examine structure
   - Check for missing values and outliers

2. **Feature Selection**
   - Select Annual Income and Spending Score
   - Create feature matrix for clustering

3. **Elbow Method Implementation**
   - Calculate WCSS for K=1 to 10
   - Identify optimal number of clusters

4. **K-Means Clustering**
   - Apply clustering with optimal K=5
   - Extract cluster labels and centroids

5. **Visualization & Analysis**
   - Create comprehensive plots
   - Analyze cluster characteristics

6. **Quality Evaluation**
   - Calculate Silhouette Score
   - Validate clustering results

