# KKN-Classification-visualizing
# Wine Quality Classification with KNN

This project uses the K-Nearest Neighbors (KNN) algorithm to classify wine quality as either "Good" (quality ≥ 6) or "Bad" (quality < 6) based on two key features:  

- Alcohol content  
- Volatile acidity

## What the Code Does

1. Loads & Prepares Data
   - Reads the wine dataset (WineQT.csv).  
   - Selects "alcohol" and "volatile acidity" as key features.  
   - Converts wine quality into binary classes (Good/Bad).  

2. Trains & Tests KNN Model
   - Splits data into training (70%) and testing (30%) sets.  
   - Scales features for better performance.  
   - Tests different K values (1,20,2) to find the best accuracy.  

3. Evaluates Performance  
   - Accuracy Score: Shows how well the model predicts wine quality.  
   - Confusion Matrix: Displays correct vs. incorrect predictions.  

4. Visualizes Decision Boundaries 
   - Plots how KNN separates "Good" and "Bad" wines for different K values.  
   - Helps understand how changing K affects classification.  

## Key Observations 
- Small K (e.g., K=1): Complex boundaries (may overfit).  
- Large K (e.g., K=20): Smoother boundaries (may underfit).  
- Best K: Selected based on highest accuracy.  

