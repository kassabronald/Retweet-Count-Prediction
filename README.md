# Retweet-Count-Prediction
This project was part of my Machine and Deep Learning course at Ecole Polytechnique Paris

How to run the code:

- If you are using google collab:
  Make sure that the following lines are uncommented

from google.colab import drive
drive.mount('/content/drive')
  
  To locate the "train.csv" file locate it in your google drive and copy the path in pd.read_csv


-If you are using Jupyter Notebook:
  Make sure that the following lines are commented

from google.colab import drive
drive.mount('/content/drive')
  
  Make sure "train.csv" and "evaluation.csv" are in the same directory where you are working



After loading the data, you can choose which model to run (we submitted 3)


-Pipeline architecture: (Cell number 3) (If trained on the whole data it takes a LOT of time, at least on CPU)
-Neural Network: (Cell number 5 to 10) (If trained on the whole data it takes a LOT of time, at least on CPU)
-XGBoost: (Cell number 11) (Can be trained on the whole data)



Make Sure to download all the required packages and versions.

