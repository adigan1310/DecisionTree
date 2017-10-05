ID3 ALGORITHM IMPLEMENTATION

Language used : Python

Steps to compile the code:
1) Extract the data_set 1 and data_set 2 files and place them in folder named Data_set1 and Data_set2
2)Open command prompt and open the directory that contains the ID3.py file
3)Enter the commmand "python <filename>.py <path of training data setfile> <path of test data set file> <path of validation data set file> <pruning factor>
Example is as follows:
	"python ID3.py F:/Data_set1/training_Set.csv F:/Data_set1/test_Set.csv F:/Data_set1/validation_set.csv 0.2"
4)The code will construct the tree based on the training set and displays it. It will also compute the accuracy of the data set when tested with the constructed tree.