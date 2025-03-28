# NBA-Player-Performance-Analysis
### **NBA Team Performance Analysis and Win Prediction**  

#### **Objective:**  
The goal of this project was to analyze key player and team statistics to determine their impact on a team's win percentage. Using exploratory data analysis (EDA) and regression modeling, I identified the most influential factors and built predictive models.  

#### **Data Exploration & Visualization:**  
- Conducted **correlation analysis** on various numerical attributes to understand relationships between player/team stats and win percentage.  
- Created **histograms** to visualize the distribution of critical stats like Personal Fouls (PF), Steals (STL), Three-Point Field Goals (3PFG), Turnovers (TOV), Weight, and Experience.  
- Used **scatter plots with regression lines** to analyze how variables such as Experience, Field Goals, Three-Point Field Goals, Total Rebounds, Assists, and Height impact win percentage.  
- Generated a **heatmap** to highlight the strongest correlations between features.  

#### **Predictive Modeling:**  
- Built multiple **Ordinary Least Squares (OLS) regression models**:  
  - **Game Stats Model:** Used **FG, FGA, Three-Point FG, Assists, Free Throws (FT), Steals, Blocks, Turnovers, and Personal Fouls** to predict win percentage.  
  - **Player Stats Model:** Used **Experience, Age, Height, and Weight** as predictors.  
  - **Final Model:** Focused on **Experience** as the primary independent variable to predict win percentage.  

#### **Model Evaluation:**  
- Tested the final model on unseen data and compared **actual vs. predicted win percentages**.  
- Calculated the **Mean Squared Error (MSE)** to assess the model’s accuracy.  

#### **Key Findings:**  
- **Experience, Field Goals, and Three-Point Shooting** had a strong positive correlation with win percentage.  
- **Turnovers negatively impacted team performance**, confirming the importance of ball control.  
- **Height had a weaker correlation** with win percentage than expected, suggesting that other skills and strategies play a more significant role.  

#### **Future Work:**  
- Improve the model by incorporating **advanced machine learning techniques** like Random Forest or Gradient Boosting.  
- Use **feature engineering** to enhance predictive power.  
- Build an **interactive dashboard** using Power BI or Tableau to visualize team performance insights.  

This project provided valuable insights into NBA team success and demonstrated how statistical modeling can be used for **sports analytics and decision-making**.
