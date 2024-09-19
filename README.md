# Air-Quality-Forecasting-using-Machine-Learning

**Project Overview:**
Developed a forecasting model to predict air quality metrics using the FB Prophet algorithm. The project involved data cleaning, preprocessing, and time-series forecasting to provide actionable insights into air quality trends.

**Key Responsibilities:**

- **Data Acquisition and Cleaning:**
  - Loaded air quality data from a CSV file into a pandas DataFrame.
  - Addressed data quality issues by removing irrelevant columns and handling missing values.
  - Replaced placeholder values (`-200`) with NaN and imputed missing values using column means.

- **Data Preparation:**
  - Transformed date and time columns into a single datetime column to facilitate time-series analysis.
  - Combined date and time information into a unified format compatible with the forecasting model.

- **Forecasting with FB Prophet:**
  - Utilized the FB Prophet library, specifically designed for time-series forecasting, to model and predict air quality metrics.
  - Created a future DataFrame to extend the prediction period by one year.
  - Generated forecasts for future air quality and visualized the results.

- **Visualization and Analysis:**
  - Plotted the forecast results to visualize predicted air quality trends.
  - Analyzed forecast components to understand seasonal effects and trends in air quality data.

**Technical Skills:**
- Data Cleaning and Preprocessing: Pandas, NumPy
- Time-Series Forecasting: FB Prophet
- Data Visualization: Plotting forecast and components

**Outcome:**
Successfully implemented a forecasting model that predicts future air quality metrics. The model provides valuable insights into air quality trends, helping in planning and decision-making for environmental and health-related initiatives.

**Tools and Technologies:**
- Python, Pandas, NumPy
- FB Prophet
- Data visualization libraries

**Challenges Overcome:**
- Managed and corrected data inconsistencies and missing values to ensure accurate forecasting.
- Successfully combined and formatted datetime information for effective time-series modeling.
