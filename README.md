# TIANCHI

# Install
	!pip install -r requirements.txt

# Data set mount description
  /tcdata
		  |--train
		     |--img
		        |-- img_0000_0000.png
		        |-- img_0003_0000.png
		     |--label
		        |-- img_0000_0000.png
		        |-- img_0003_0000.png
		     |-- label.csv
		  |--test
		     |--img
		        |-- img_0000_0000.png
		        |-- img_0003_0000.png
  If you want to use our model for training and prediction, mount the data set along the directory path descibled above.

# Modify the ratio between the training set and the validation set 
 If you want to modify the ratio between the training set and the validation set, please modify the corresponding lines in the dataloader.py file in the utils directory. 
        
# In the label.csv, we provide the real score

# In the prob.csv, we provide the one-hot score
