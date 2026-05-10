# Fire Station Placement Optimization Using Historical Fire Incident Clustering

## Project Overview
This project applies clustering algorithms and data analytics techniques to identify high-risk fire hotspots and optimize fire station placement using historical fire incident data from Toronto.

The analysis focuses on improving emergency response efficiency, reducing response distance, and supporting data-driven urban safety planning.

---

## Objectives
- Identify high-risk fire clusters using historical incident data
- Compare clustering model performance
- Analyze factors influencing fire risk severity
- Optimize fire station placement strategies
- Generate business and urban-planning insights from fire incident data

---

## Dataset
- Dataset: Toronto Fire Incidents Dataset
- Time Period: 2011–2018
- Total Records: 11,214 fire incidents
- Domain: Public Safety & Urban Analytics

---

## Technologies & Tools
- Python
- Pandas
- NumPy
- Scikit-learn
- MongoDB
- Plotly
- Google Colab

---

## Workflow
1. Data Cleaning
2. Exploratory Data Analysis (EDA)
3. Feature Engineering
4. Data Normalization
5. Clustering Analysis
6. Dashboard Visualization
7. Model Evaluation
8. Business Insight Reporting

---

## Clustering Models

### K-Means
- Number of Clusters: 3
- Inertia: 11.431
- Silhouette Score: 0.4143

### DBSCAN
- eps = 1.1
- min_samples = 4
- Silhouette Score: 0.4656
- Noise Ratio: 0.19%

DBSCAN achieved better clustering quality, while K-Means was selected for urban planning optimization due to clearer geographic segmentation.

---

## Key Insights
- Population density, high-rise buildings, and industrial facilities strongly influence fire risk levels
- High-risk clusters experienced significantly higher financial losses
- Western Toronto areas showed the highest concentration of fire incidents

---

## Optimization Results
- Proposed adding 3 new fire stations at cluster centroids
- Reduced average response distance by approximately 20–30%
- Estimated annual savings of CAD 2.5 million
- Improved estimated emergency response time by 1–2 minutes per incident

---

## Future Improvements
- Integrate GIS and real-time traffic data
- Apply real-time streaming analytics
- Develop dynamic fire-risk prediction systems
- Improve spatial clustering with advanced geospatial techniques

---

## Author
Nguyen Le Yen Nhi  
Financial Technology Student | Aspiring Data Analyst
