## Website Hits Prediction

This is a project for predicting the hits on a web page in an IPython Notebook which demonstrates 
* Understanding Data
* Exploratory Data Analysis
    * Visualization
    * Manipulation
    * Feature Engineering
* Data Preparation
* Model Selection
* Validation
 
The goal of this repository is to demonstrate an insightful understanding of data using visualizations and feature engineering for the prediction model.

**Quick Start**: [`View`](https://nbviewer.jupyter.org/github/techedlaksh/website-hits-prediction/blob/master/final-notebook.ipynb) a static version of the notebook in the comfort of your own browser.

## Dependencies:

* Python 2.7
* Pandas
* Sklearn
* NumPy
* Seaborn
* Matplotlib
* XGBoost

## Installation
To run this notebook interactively:
1. **Clone this repo**

      ```sh
      $ git clone https://github.com/techedlaksh/website-hits-prediction
      $ cd website-hits-prediction
      ```
2. **Create new virtual environment**

      ```sh
      $ sudo pip install virtualenv
      $ virtualenv venv
      $ source venv/bin/activate
      $ pip install -r requirements.txt
       ```
3. **Run Notebook**

    ```sh
    $ jupyter notebook
    ```
4. Click on `final-notebook.ipynb` in the browser and enjoy!
5. When you're done with notebook, close the jupyter from terminal and deactivate the virtual environment with `deactivate`.

## Data
* row_num: a nuber uniquely identifying each row.
* locale: the platform of the session.
* day_of_week: Mon-Fri, the day of the week of the session.
* hour_of_day: 00-23, the hour of the day of the session.
* agent_id: the device used for the session.
* entry_page: describes the landing page of the session.
* path_id_set: shows all the locations that were visited during the session.
* traffic_type: indicates the channel the user cane through.
* session_duration: the duration in seconds of the session.
* hits: the number of interactions with the trivago page during the session.

## Task

>Use the data provided to build a model that predicts the number of hits per session, depending on the given parameters.

## Evaluation

>Predictions will be evaluated by the root mean square error.

## Notebook covers these topics

### Data Handling
* Importing data with pandas
* Understanding data using statistics with pandas
* Exploring Data through Visualizations with Matplotlib
* Feature Engineering
* Data Preparation for the model

## Model Selection
* Logistic Regression
* Random Forest
* XGBoost
* LightBGM

## Valuation
* K-folds cross validation to valuate results locally

**Note**: Trained models are exported which can be re-used by importing it into your script and predicting your data with the saved model.



