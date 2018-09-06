# NFL
NFL Play Analysis and Prediction Models
This project is to build predictive models to determine the offensive play chosen in certain NFL game situations.  Two models are built:
-The Basic Model predicts whether a run or pass will be called
-The Detailed Model predicts whether the play will be a short pass, long pass, end run, off tackle run, off guard run, or middle run

There are certain play situations that are filtered out of the dataset and not intended to be predicted by these models.  Specifically, the models predict play type under a 1st through 3rd down situation (i.e. 4th down situations are excluded) and are not meant to predict play type when there are less than 2 minutes remaining in the half or in overtime.  In other words the models predict play type only in the first 28 minutes of each half of regulation play.

Base data consumed comes from the 'Detailed NFL Play-by-Play Data 2009-2017 dataset.  In addition, a handful of additional inputs were separately created offline and added to the base Kaggle data.  This data is provided in a separate .csv file.
