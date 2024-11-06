# Challenging_experiment_1 -- A quick guide
### The model_training contains the code for dataset preparation and model training attempts. Needs a Specific dataset from kaggle and this notebook was made on kaggle.
### Same goes with model_inference notebook
### The results png and labels__correlogram are images extracted from training the final successful (best) model. Other related metrics are auto saved in your kaggle working directory when you run it on kaggle.
### best.pt is the best model obtained from this attempt which has been exported from model_training notebook and uses in inference notebook.
### data2.yaml configures data pipeline and other related arguments for yolo to be trained with.
### emotions_prediction_v1 is the csv file that contains the required results for each test image present on thee dataset, which was asked in the competition. It is generated from inference notebook.
