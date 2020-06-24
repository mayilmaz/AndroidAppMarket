## Android App Market - Data Exploration and Visualization

This repo contains the code for data exploration and visualization using Android App Market dataset. It is made up of two CSV files:
- `apps.csv`: contains all the details of the applications on Google Play. There are 13 features that describe a given app.
- `user_reviews.csv`: contains 100 reviews for each app, most helpful first. The text in each review has been pre-processed and attributed with three new features: Sentiment (Positive, Negative or Neutral), Sentiment Polarity and Sentiment Subjectivity.

Further explanations are included in Jupyter notebook.

### Required Libraries
- Pandas
- Plotly
- Seaborn
- Matplotlib


### Install the requirements
- Install the requirements using `pip install -r requirements.txt` .
    * Make sure you use Python 3.
