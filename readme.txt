step 1:
install jupyter nootbook(anaconda3)
since JN runs on local host so install wamp or xamp
in cmd type "Jupyter Nootbook" or directly open Jupyter Nootbook

step 2:
import-> pandas , sklearn libraries into your program 

step3:
import .csv or any other file that contains data set for training and testing of data
into your program 
-> csv file contains dataset in the form of rows and cols, you can drop any row or col for csv

step 4:
select train and test data (ref# img 1 block 6 ,7)
in the code we are dropping the prediction col from train data (block 6)
and in the testing data we are only selecting "species" col because it will predict (block 7)

step 5:
create model and call built-in model GaussionNB from sklearn library

step 6:
now train the model by model.fit method 

step 7:
now predict the values based on the csv inputted 

outcome:
the model has 96% accuracy , so it is 96%fit , if you want to increase the accuracy change 
the training and testing data

<------------------------------>
for any query contact us on “jawadkhan31849@gmail.com”