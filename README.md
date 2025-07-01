# Predicting-Customer-Churn-for-Blinkit-Grocery-Platform

Overview:
In this project, I analyzed Blinkit's customer and marketing data to identify behavioral signals of churn and build a predictive model to support retention strategies.

- Key Steps:

  📥 Loaded and cleaned multi-source datasets: orders, feedback, customers, marketing performance
  
  📊 Conducted exploratory data analysis using Seaborn/Matplotlib (histograms, heatmaps, box plots)
  
  🧠 Engineered features like:

    Total orders, Avg. order value, Delivery delay
    
    Feedback ratings, Registration age

  🔍 Defined churn as “no orders in last 60 days”
  
  🤖 Trained and compared models:

    Logistic Regression (AUC = 0.73)
    
    Random Forest (Best AUC = 0.77, 96% recall)
    
    XGBoost (AUC = 0.77, 92% recall)

- Results:

  Identified top drivers of churn:

    Fewer orders
    
    Low feedback ratings
    
    High delivery delays

  Exported churn predictions and probabilities for Power BI reporting
  
  Delivered actionable insights for re-engagement campaigns and service improvements

- Tools Used:
  · Python 
  · Pandas 
  · Seaborn 
  · Scikit-learn 
  · XGBoost 
  · Power BI

- Next Steps:

  Build a Power BI dashboard for real-time churn tracking
  
  Segment customers by risk level and lifetime value
  
  Deploy periodic prediction pipeline for marketing teams

