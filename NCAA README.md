# NCAA Women's Basketball March Madness 2025 Predictive Model

## Overview

This project develops a machine learning model to predict the outcomes of the 2025 NCAA Women's Basketball Tournament (March Madness). The model analyzes historical team statistics, 
player performance data, and other relevant factors to generate predictions and provide insights into potential tournament matchups. The project is geared towards providing 
insights and predictions related to the tournament.

## Data Sources

*   **Sports-Reference.com (College Basketball):** Primary data source for detailed team and player statistics.

## Technologies Used

*   **Python:** Primary programming language for web scraping, saving the dataset in csv format, data analysis, cleaning, and machine learning.
*   **Pandas:** Data manipulation and analysis.
*   **NumPy:** Numerical computing.
*   **BeautifulSoup:** Web scraping of historical NCAA Women's basketball data from Sports-Reference.com.
*   **Seaborn:** Enhanced data visualization.

## Project Structure

The project is contained within the [NCAA Women's MM 2025 Predictive Model.ipynb](NCAA%20Women's%20MM%202025%20Predictive%20Model.ipynb) Jupyter Notebook. 

The notebook is structured as follows:

1.  **Data Acquisition and Preprocessing:**
    *   Scraping or importing historical NCAA Women's Basketball data.
    *   Cleaning and handling missing values in the dataset.
    *   Data transformation and feature engineering.

2.  **Feature Engineering:**
    *   Creating and selecting relevant features for the model, such as:
        *   Simple Rating System (SRS)
        *   Strength of Schedule (SOS)
        *   Scoring Efficiency
        *   Defensive Efficiency
        *   Win/Loss Ratio
    *   Creating new features that combine existing metrics.

3.  **Model Selection and Training:**
    *   Choosing machine learning algorithms suitable for classification (Random Forest).
    *   Splitting the dataset into training and testing sets.
    *   Training the model on historical tournament data.

4.  **Model Evaluation:**
    *   Assessing the model's performance using metrics such as Mean Absolute Error and R2 Score.
    *   Validating the model on past tournament results to assess its reliability.

5.  **Prediction and Bracket Simulation:**
    *   Using the trained model to predict the outcomes of the 2025 NCAA Women's Tournament games.
    *   Simulating the championship game between the top two teams, based on the model's predictions.

6.  **Visualization and Analysis:**
    *   Visualizing key factors influencing tournament outcomes.
    *   Analyzing the characteristics of teams predicted to perform well.
    *   Creating visualizations of the predicted top ten teams.

7.  **Conclusions and Insights:**
    *   Summarizing the model's predictions for the 2025 tournament.
    *   Discussing the limitations of the model and potential areas for improvement.
    *   Providing insights into the factors that contribute to success in the NCAA Women's Tournament.

## Key Findings

*   The model predicts that South Carolina to win the 2025 NCAA Women's Tournament with predicted wins of 36.
*   Key features influencing tournament success include:
    *   Simple Rating System (SRS)
    *   Strength of Schedule (SOS)
    *   Scoring Efficiency
    *   Defensive Efficiency
    *   Win/Loss Ratio

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
    jupyter notebook NCAA\ Women\'s\ MM\ 2025\ Predictive\ Model.ipynb
    ```

## Potential Improvements

*   Incorporate more granular player-level data and scouting reports.
*   Develop a more sophisticated model to account for injuries, upsets, and other dynamic factors.
*   Explore advanced machine learning techniques such as neural networks or ensemble methods.
*   Backtest the model on a longer historical dataset to assess its long-term accuracy.
*   Incorporate more advanced metrics (e.g. win probability added, cinderella teams, upsets, Sweet 16 teams)

## Author

### Kai Cole


