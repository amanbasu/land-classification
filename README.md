# land-classification
Classifying different parts of land using Machine Learning

There are multiple satellites that capture the data about the amount of light intensity reflected at different frequencies from the Earth at a very granular geographic level. Some of this information can be used to classify the Earth into different buckets - built-up, barren, green or water. The training data contains different parameters classified into the 4 classes. 

# Column Description

* Numeric columns <b>X1 to X6 and I1 to I6</b> define characteristics about the land piece
* <b>ClusterID</b> is a categorical column which clusters a type of land together
* <b>target</b> is the output categorical column which needs to be found for the test dataset
    * 1 = Green Land
    * 2 = Water
    * 3 = Barren Land
    * 4 = Built-up 


