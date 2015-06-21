Codebook
========

Variable list and descriptions
------------------------------

Variable name    | Description
-----------------|------------
subject_train    | data in "subject_train.txt"
X_train         | data in "y_train.txt"
y_train       | data in "subject_test.txt"
subject_test  | data in "X_train.txt"
X_test | data in "X_test.txt"
Y_test     | data in "y_test.txt"
data | tidy data where train and test data are inlcuded
data1 | data merged where descriptive attribute is added
data2 | data where attribute names are more readable and order is adjusted
list_group_split | tidy data which is meeted in the last requirements

Work for cleaning data
------------------------------


Note, in the following script, the first number represents the line in the analysis.Rmd, so you can check the corresponding line so that you can get a better understanding.

19, donlowd the file and unzip it manually, then set path 

27, read data 

37, Merge the traing、test and subject dataset and we get tidy data where train and test data are included

47, Extract mean and sd value

54, merge process，add descriptive names to data and we get data1

63, Label data and get data2. 
In data2, the first 561 attribute represents x, the 562th represents subject, the 563th and 564 represent y value.

74, Second tidy data set and we get list_group_split



