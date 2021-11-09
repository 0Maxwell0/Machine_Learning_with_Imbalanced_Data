Imbalanced_Data_nb



In this repository, I have placed my notebooks with works on imbalanced data. The aim of doing the work was to gain hands-on experience, building intuition, and getting familiar with the most frequent approaches when working on imbalanced data.

Main approaches for dealing with imbalanced data:
1. On a data level (under-sampling, over-sampling)
2. Cost-sensitive approach
3. Ensemble algorithms<br>
In this repository, there are works with all 3 approaches.  

=======================================================

**Data**:<br>
The link:
https://www.kdd.org/kdd-cup/view/kdd-cup-2004/Data <br>
target: whether a protein is homologous to a target protein<br>
variables: 74. The features describe the match (e.g. the score of a sequence alignment) between the native protein sequence and the sequence that is tested for homology.<br>
There are no missing values. All variables are numerical.<br>

=======================================================

**Additional Packages**:
- autopep8==1.5.4
- imbalanced-learn==0.7.0
- matplotlib==3.3.2
- numpy==1.19.2
- pandas==1.1.3
- scikit-learn==0.23.2
- scipy==1.5.2
- seaborn==0.11.0
- yapf==0.30.0
- yellowbrick==1.2

=======================================================

Content:

0. Cheatsheet (under-sampling, over-sampling)

1. **Udersampling Methods**
	- Random Undersampling
	- Condensed Nearest Neighbour
  - Tomek Links
  - One Sided Selection
	- Edited Nearest Neighbours
	- Repeated Edited Nearest Neighbours
	- All KNN
	- Neighbourhood Cleaning Rule    
	- NearMiss
	- Instance Hardness Threshold


2. **Oversampling methods**
	- Random Oversampling
	- ADASYN
	- SMOTE
	- BorderlineSMOTE
	- KMeansSMOTE
	- SMOTENC
	- SVMSMOT

3. **Over and Undersampling Methods**
	- SMOTENN
	- SMOTETomek


4. **Ensemble Methods**
	- bagging
	- boosting
	- ensemble methods with sampling
	- bagging + boosting


6. **Cost Sensitive Learning**
	- Types of cost
	- Obtaining the Cost
	- Missclassification Cost
	- Bayes Risk
	- MetaCost

7. the python code for fetching the dataset

8. the fetched dataset

===================================================================================================


Tons of thanks to Soledad Galli as mostly notebooks and materials in this repo are based on her course ( 
 https://www.udemy.com/course/machine-learning-with-imbalanced-data/?referralCode=F30537642DA57D19ED83 )
