## IPL Score Predictor
Predict total runs between teams using current runs and wickets.

## Algorithms used:
- Linear Regression
- K-Nearest Neighbor Regressor
- XGBoost Regressor
- RandomForest Regressor
- SVR
- Decision Tree Regressor

## Dataset:
The dataset comprises of over by over details of matches and runs from 2008 to 2020.

Dataset Used: ipl_data.csv
- mid-match id
- date - when matches are played
- venue - a place where matches are played
- bat_team - batting team
- bowl_team - bowling team
- batsman - batsman
- bowler - bowler
- runs - runs scored
- wickets - wickets
- overs - overs - next 3 are based on this
- run_last_5 - runs scored in last 5 overs
- wicket_last_5 - wickets in last 5 overs
- Stricker - batsman playing as main 1
- non-striker - batsman playing as runner-up - not main 0
- total - total score (target variable)
