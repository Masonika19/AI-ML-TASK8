# AI-ML-TASK8
# K-Means Clustering on  Mall Customer Data

##  Objective
Apply K-Means clustering to segment mall customers based on their features.

## Tools Used
- pandas
- scikit-learn
- matplotlib

## Steps
1. Load and clean data  
   - Drop `CustomerID`  
   - Convert `Gender` to numeric  
2. Scale features using `StandardScaler`  
3. Use Elbow Method to find optimal K  
4. Apply K-Means clustering  
5. Visualize clusters using PCA (2D)  
6. Evaluate with Silhouette Score  

## Output
- Elbow curve to choose K  
- Cluster plot (colored groups)  
- Silhouette Score for performance(Silhouette Score:0.27191023466188324)

