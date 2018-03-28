  # ![GA Logo](https://camo.githubusercontent.com/6ce15b81c1f06d716d753a61f5db22375fa684da/68747470733a2f2f67612d646173682e73332e616d617a6f6e6177732e636f6d2f70726f64756374696f6e2f6173736574732f6c6f676f2d39663838616536633963333837313639306533333238306663663535376633332e706e67) March Madness Machine Learning

---

_Author: Dodge McIntosh_

---

## Project Goals:

1. Create a machine learning model to accurately predict the outcomes of every possible matchup in this year's (2018) March Madness tournament (a notoriously impossible task).
2. Generate a successful Kaggle prediction and place in the top half of the open public leaderboard.
3. Create clear and compelling visualizations throughout my work and present my findings in a class setting.


## Project Context

" Google Cloud and NCAA® teamed up to bring this year’s version of the Kaggle machine learning competition. Another year, another chance to anticipate the upsets, call the probabilities, and put your bracketology skills to the leaderboard test. Kagglers will join the millions of fans who attempt to forecast the outcomes of March Madness® during this year's NCAA Division I Men’s and Women’s Basketball Championships. But unlike most fans, you will pick your bracket using a combination of NCAA’s historical data and your computing power, while the ground truth unfolds on national television."
- From Kaggle website

## Data sources

> - Much of the information was provided by Kaggle (maybe too much)
  - Participants were free to incorporate any outside sources of information as long as they were free and publicly accessible

## Modeling Process Overview

1. Pull in all relevant data provided by Kaggle and scrape additional data (as neccessary).
2. The training dataset is based off the detailed box scores from the regular season. I used this data to make advanced analytics for each team based on the NBA approach, available for reference [here](http://hangtime.blogs.nba.com/2013/02/15/the-new-nba-comstats-advanced-stats-all-start-with-pace-and-efficiency/).
Within this process I performed:
- advanced feature engineering
- working with and successfully merging multiple different dataframes
3. Generated my classification model (a random forest) using the training data. Within this process, I made use of:
    - train-test split for validation
    - grid searching for hyperparameters
    - strong exploratory data analysis to question correlation and relationship across predictive variables
    - code that reproducibly and consistently applies feature transformation (such as the preprocessing library)
4. Predicted the outcomes (as probabilities) for target columns in the test dataset and submitted my predictions to Kaggle to see how my model performed against unknown data.
    - **Note**: Kaggle expects to see submissions in a specific format. I needed to check the challenge's page to make sure I was formatting files correctly, which was a challenge in itself.

## Project Feedback + Evaluation

For this project, I wanted to make sure I was adhering to the following principles throughout:

- **Organization**:	Clearly commented, annotated and sectioned Jupyter notebook or Python script. Comments and annotations add clarity, explanation and intent to the work. Notebook is well-structured with title, author and sections. Assumptions are stated and justified.
- **Exploratory Data Analysis**: A thorough exploratory data analysis has been conducted. Descriptive statistics, univariate and bivariate analysis, and plotting are skillfully used to explore connections across the dataset between features and targets.
- **Modeling Process**: Skillful and correct use of cross-validation, grid search, and goodness-of-fit metrics to evaluate candidate models. Assumptions and decisions in the modeling process are stated and justified. Use of correct modeling techniques in each challenge. Data is reproducibly and reliably transformed between training and test datasets.

## Questions and Connections

Find me on [LinkedIn](https://www.linkedin.com/in/dodgemcintosh/) to share your tips and tricks, ask me any questions, or if you just want to connect!