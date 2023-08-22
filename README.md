NFL Quarterback Touchdown Prediction Project

Overview
Welcome to the NFL Quarterback Touchdown Prediction Project! This project focuses on utilizing NFL play-by-play data to predict the number of touchdowns thrown by quarterbacks. The data is sourced from the nflverse-data repository, which provides detailed play-by-play information for NFL games.

Project Goal
The main goal of this project is to build a machine learning model that accurately predicts the number of touchdowns a quarterback will throw during an NFL game. By using a combination of specific in-game statistics, the project aims to uncover patterns and relationships that influence quarterback touchdown performance.

Data Source
The project relies on play-by-play data from the nflverse-data repository. This dataset contains comprehensive play-by-play records for NFL games, offering insights into every play, player involvement, game context, and more.

Methodology
Data Collection and Preprocessing: Play-by-play data is gathered from the nflverse-data repository and subjected to meticulous cleaning and preprocessing. The focus is on variables such as 'pass', 'complete_pass', 'interception', 'sack', 'yards_gained', and 'touchdown'.

Feature Selection and Filtering: Specific in-game statistics are chosen as features for touchdown prediction. The dataset is also filtered to include only quarterbacks who have played at least 15 games in a given season, ensuring a robust dataset for analysis.

Model Training and Linear Regression: The project employs Linear Regression as the chosen algorithm for prediction. The algorithm learns relationships between the selected features and the number of touchdowns, enabling accurate predictions.

Model Evaluation and Visualization: The trained Linear Regression model's performance is evaluated using Mean Squared Error (MSE) and Root Mean Squared Error (RMSE). Jupyter Notebook displays are utilized to showcase the linear regression process and results.

Prediction and Insights: Once the model is ready, it can predict the number of touchdowns for quarterbacks in actual NFL games. These predictions provide valuable insights into the expected quarterback touchdown performance.
