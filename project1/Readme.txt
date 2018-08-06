This document is to explain how to run the 'Project1_finalized.ipynb'
for the project. The file is a Jupyter note book file with python 2.7 
version. We recommend to use Anaconda Navigator python 2.7 version to 
test out the code.

Author: Jiahui (Will) Li (004356402) & Ruiyi (John) Wu (304615036)
Date: 1/29/2018
=====================================================================

1-	The python script has been well documented and labeled for different
	parts. The code should be run from top to bottom by each block. 
	Otherwise, some of the variables won't be recognize if one skip 
	part of the block. 

2-	The current setting is with the parameter min_df = 2 with LSI reduction
	To run a simulation with min_df =5, one can easily change the parameter
	in section 'Part B' where 
	'final_count_vectorizer_2 = CountVectorizer(min_df = 2, tokenizer=tokenize)'.
	Change 2 to 5. And run the following code all over again. 

3- 	To use NMF reduction, simply replace all the 'SVD.*' function to 'trainNMF.*'
	after the label 'Part E', and the variable "reduced_train_tfidf" to
	'NMFed_train'. And run the code after Part E again. 