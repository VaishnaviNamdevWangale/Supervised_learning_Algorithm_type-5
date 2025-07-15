✅ 1. Import Required Libraries.
      numpy and pandas for data manipulation.
      matplotlib for plotting and visualizations.

📂 2. Load the Dataset
      ds = pd.read_csv("Position_Salaries (1).csv")
      Reads the CSV file containing position levels and corresponding salaries.

🔍 3. Splitting Features and Target
      x = ds[["Level"]]
      y = ds[["Salary"]]
      x: Independent variable (Position level)
      y: Dependent variable (Salary)

📊 4. Visualize Raw Data
      Visualizes the data to reveal non-linear patterns between level and salary.

🌳 5. Random Forest Regression Model
      Uses 100 decision trees (n_estimators=100) to build a Random Forest model.
      Fits the model on the feature x and target y.

🔮 6. Make Prediction
      reg.predict([[6.5]])
      Predicts salary for a new position level of 6.5.
      
📈 7. Visualize the Regression Curve
      Plots a smoother curve by creating a dense grid of levels.
      Displays the predicted regression line along with actual data points.

