# Predicting the 2025 WNBA Champions

## Overview

This project develops a machine learning model to predict the winner of the 2025 WNBA Championship. By analyzing historical team statistics, player performance metrics, 
regular season records, and other relevant factors, the model aims to provide data-driven insights into the potential champions for the upcoming season. 
This analysis can be valuable for sports analysts, WNBA enthusiasts, and those interested in understanding the dynamics of team success in professional basketball.

## Data Sources

*   **WNBA.com:** Used for historical, advanced game results, team standings and statistics.

## Technologies Used

*   **Excel:** Populated worksheet with combined team data.
*   **Python:** Primary programming language for data analysis and machine learning.
*   **Pandas:** Data manipulation and analysis.
*   **NumPy:** Numerical computing.
*   **Scikit-learn:** Machine learning algorithms and model evaluation (train_test_split, RandomForestRegressor, mean_absolute_error, r2_score).
*   **Matplotlib:** Data visualization.
*   **Seaborn:** Enhanced data visualization.

## Project Structure

The project is contained within the [Predicting WNBA 2025 Champions.ipynb](Predicting%20WNBA%202025%20Champions.ipynb) Jupyter Notebook. 

The notebook is structured as follows:

1.  **Data Acquisition and Preprocessing:**
    *   Importing historical WNBA data from official WNBA website.
    *   Cleaning and handling missing values in the dataset.
    *   Data transformation and feature engineering.

2.  **Feature Engineering:**
    *   Creating and selecting relevant features for the model, such as:
        *   Team offensive and defensive statistics (e.g., Simple Rating System, Strength Of Schedule, Offensive & Defensive Rating, Win/Loss Ratio).
        *   Regular season records and performances.
    *   Creating new features that combine existing metrics.

3.  **Model Selection and Training:**
    *   Choosing appropriate machine learning algorithms for classification (e.g., Random Forest).
    *   Splitting the dataset into training and testing sets.
    *   Training the model on historical championship data.

4.  **Model Evaluation:**
    *   Assessing the model's performance using metrics such Mean Absolute Error and R2 Score.
    *   Evaluating the model's ability to predict championship winners.
    *   Validating the model on past seasons to assess its reliability.

5.  **Prediction and Analysis:**
    *   Using the trained model to predict the 2025 WNBA Champion.
    *   Analyzing the key factors contributing to championship success.
    *   Identifying potential contenders and dark horse teams for the 2025 season.

6.  **Visualization and Analysis:**
    *   Analyzing the characteristics of teams predicted to win.
    *   Visualizing the top ten teams and contenders for a possible WNBA championship.

7.  **Conclusions and Insights:**
    *   Summarizing the model's prediction for the 2025 WNBA Champion.
    *   Providing insights into the factors that contribute to success in the WNBA.

## Key Findings

*   The model predicts that the Minnestoa Lynx will win the 2025 WNBA Championship.
*   Key features influencing championship success include:
    *   Simple Rating System
    *   Strength Of Schedule
    *   Offensive & Defensive Rating
    *   Win/Loss Ratio
*   The model identifies the Los Angeles Sparks as a potential dark horse contender based on being slotted in the tenth spot of top ten teams.

## How to Run the Code

1.  **Clone the repository:**
    ```
    git clone https://github.com/KaiCole365/Women-College-Pro-ML-Projects.git
    cd Women-College-Pro-ML-Projects
    ```

2.  **Install the required libraries:**
    ```
    pip install pandas numpy scikit-learn matplotlib seaborn  # Add other libraries if needed
    ```

3.  **Run the Jupyter Notebook:**
    ```
    jupyter notebook Predicting\ WNBA\ 2025\ Champions.ipynb
    ```

## Potential Improvements

*   Backtest the model on a longer historical dataset, compiling 3-4 years of data to assess its long-term accuracy and stability.
*   Incorporate more granular player-level data and advanced stats (e.g., player tracking data).
*   Develop a more sophisticated model to account for injuries, coaching changes, and mid-season acquisitions.
*   Use more advanced model evaluation techniques.

## Author

### Kai Cole
