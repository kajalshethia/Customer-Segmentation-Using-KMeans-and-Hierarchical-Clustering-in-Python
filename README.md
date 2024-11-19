# Customer-Segmentation-using-KMeans-and-Hierarchical-Clustering-in-Python

### Overview
This project focuses on customer segmentation using **KMeans** and **Hierarchical Clustering** algorithms in Python. The goal is to group customers based on their behavior and characteristics, enabling actionable insights for targeted strategies.

### Key Features
- Implements **KMeans** and **Hierarchical Clustering** for segmentation.
- Uses Python libraries such as `pandas`, `numpy`, `scikit-learn`, `seaborn` and `matplotlib` for data preprocessing, clustering, and visualization.
- Provides actionable insights into customer behavior, engagement, and spending patterns.

### Dataset
The dataset includes the following features:
- **Minutes Watched**: Number of minutes a customer engaged with the platform.
- **CLV (Customer Lifetime Value)**: Spending by the customer.
- **Channels**: Acquisition sources such as Facebook, YouTube, LinkedIn, etc.
- **Regions**: Customer geographical data divided into regions (USA Canada UK & Australia, Western Europe, Rest of the World).

The dataset is cleaned, normalized, and preprocessed for clustering analysis.

### Methodology
1. **Data Preprocessing**:
   - Handle missing values, scale features, and encode categorical data.
2. **Clustering Techniques**:
   - **Hierarchical Clustering**:
     - Visualize clusters with dendrograms.
       <img width="506" alt="image" src="https://github.com/user-attachments/assets/e514d6e1-570d-4c3f-929f-44d39001eea8">

   - **KMeans Clustering**:
     - Identify optimal clusters using the Elbow Method.
       <img width="367" alt="image" src="https://github.com/user-attachments/assets/e4139711-f3d8-4096-9a66-dbf7760a93b4">

3. **Segmentation Analysis**:
   - Evaluate and interpret clusters to identify key customer groups.
4. **Visualization**:
   - Create heatmaps, scatterplots, and dendrograms to present the findings.


### Key Results
The segmentation identified the following customer groups:
1. **High-Engagement Facebook Users**: Highly engaged users from Facebook with moderate spending.
2. **Google and YouTube Learners**: Users acquired via Google and YouTube, with moderate engagement but low spending.
3. **Referral-Based Learners**: Moderately engaged users who joined through referrals.
4. **LinkedIn Users**: Customers with low engagement and moderate spending.
5. **Instagram Users**: Low-engagement users from Instagram with moderate spending.
6. **High-Spending YouTube Users**: Users with moderate engagement but the highest spending.
7. **Other Channel Users**: Diverse users with high engagement and moderate spending.

### Requirements
To run this project, you need:
- **Python 3.8+**
- Libraries:
  - `pandas`
  - `numpy`
  - `scikit-learn`
  - `matplotlib`
  - `seaborn`



