# Credit Card Customer Segmentation

## 📌 Problem Statement

AllLife Bank wants to better understand its existing credit card customers to improve personalized marketing and service delivery.

This project uses unsupervised learning to identify distinct customer segments based on spending-related financial attributes and past interactions with the bank.

---

## ⚙️ Tech Stack

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- SciPy
- K-Means Clustering
- Hierarchical / Agglomerative Clustering

---

## 🔍 Approach

- Data loading and data overview
- Exploratory Data Analysis (EDA)
- Missing-value analysis
- Outlier analysis
- Feature scaling using StandardScaler
- K-Means clustering
- Elbow Method for cluster selection
- Silhouette Score analysis
- Silhouette visualization
- Hierarchical / Agglomerative Clustering
- Dendrogram analysis
- Cluster profiling
- Comparison of K-Means and Hierarchical Clustering

---

## 📊 Clustering Results

Both K-Means and Hierarchical Clustering produced well-defined customer segments.

- Silhouette Score: approximately **0.59** for both methods
- Adjusted Rand Index (ARI): **0.9944**
- The high ARI indicates near-perfect agreement between the two clustering approaches.
- The resulting clusters were highly similar, with some cluster labels swapped between methods.

---

## 👥 Customer Segment Profiles

### Cluster 1 – High-Value Digital Customers

- Very high credit limit
- Highest number of credit cards
- Very high online usage
- Low branch visits
- Very low customer-service calls

**Business opportunity:** Target these customers with premium products, personalized offers, and digital-first services.

### Cluster 2 – Service-Focused Customers

- Lowest credit limit
- Fewest credit cards
- Moderate online usage
- Highest number of customer-service calls
- Frequent interaction with support

**Business opportunity:** Improve service experience and identify suitable opportunities for cross-selling and credit-card upgrades.

---

## 💡 Business Recommendations

- Develop personalized marketing campaigns for different customer segments.
- Offer premium products and services to high-value, digitally active customers.
- Improve customer support for customers with frequent service interactions.
- Identify suitable cross-selling and upselling opportunities.
- Encourage greater adoption of digital banking channels.
- Use cluster profiles to tailor products, communication, and service strategies.

---

## 📁 Project Files

- `UL_project.ipynb` → Complete Python clustering workflow
- `UL_project.pdf` → Detailed project report

---

## 🚀 Future Improvements

- Test additional clustering algorithms such as DBSCAN and Gaussian Mixture Models.
- Explore additional customer attributes for richer segmentation.
- Develop automated customer-segment monitoring.
- Build an interactive dashboard to visualize customer segments and business recommendations.
