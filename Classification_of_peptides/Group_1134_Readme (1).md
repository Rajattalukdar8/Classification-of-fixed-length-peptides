
# Classification of the peptides in multiclass.
We need to classify peptides in 8 classes. It is a multi-class classification problem, which can be solved using SVM. These peptides have different number of amino acids. They have given us the fixed length peptides. And we have done that classification with SVM. 





## Appendix

1) We have use the train and the test dataset which was provided.

2) Duplicate sequence and missing values was removed

3) Sequence having unnatural aminom acid was also removed

4) Feature extraction was done by using protlearn python package

5) Amino acid composition,dipeptide composition and binary profile patterv was generated  from sequence for features

6) All the features were the merged for train and test

7)The features were normalized

8)Machine learning model was implimented such as gaussian naive bayes, K nearest neighbor, decision tree and SVM

9)SVM gave a better accuracy for classification of peptide sequences,

10)To run the program just type  python C:/User/Sameeha/Dekstop/BDMH/Untitled49_bdmh.py

11) Install all dependencies pip install protlearn, pip install --upgrade protlearn

12) After that just call lpython file by code: python .\Group_1134_train_BDMH_Assignment_2.py

13) After that it will ask the train data to enter. Enter the train file like in formate train_BDMH.csv .

14) After that it will ask the test data to enter. Enter the test file like in formate test_BDMH.csv . 

15) Enter your path for train data and then it will ask for the path of test data enter your path 

16) It will take some time to run as the model takes some time to train

17) The output file with sequence ID and Lable will be generated.

18) We got the best accuracy with SVM which is 53.53250 %.



## Authors

- [@Ariba Ansari](ansari20336@iiitd.ac.in)(MT20336)
- [@Nitesh Naresh Narwade](nitesh20329iiitd.ac.in)(MT20329)
- [@Rajat Talukdar](nitesh20329iiitd.ac.in)(MT20343)
   


