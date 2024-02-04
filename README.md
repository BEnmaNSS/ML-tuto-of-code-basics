1 explanation of  linear regression : *explanation of slope (gradient) and the intercept, using sk_learn.
                                      *using .intercept_ and reg.coef_
																			----------------------
2 linear_regression_with one variable & multivariate: * Data Preprocessing: FillNA values with the median value of a column.
-------------------
3 gradient_descent with python 
----------------------------
4 _hiring_linear : * We have used df['experience'] = df['experience'].fillna('zero'):
                   * This line fills missing values in the 'experience' column of the DataFrame df with the string 'zero'.
									 *lambda x: w2n.word_to_num(str(x)) if isinstance(x, str) else x:
					         *checks if each value (x) in the 'experience' column is a string (isinstance(x, str)). 
							      If it's a string, it converts it to a numerical value using w2n.word_to_num(str(x)). If it's not a string (i.e., if it's already a numerical value), it leaves it unchanged.
--------------------------------
5_6 onehot_encodimg : * changing categorical to numerical values: using get dummies.
----------
7_7_train_test_split.ipynb: * predictions might give us wrong impression about accuracy of our model if we use the same data for training and test set. 
-------------
8_#* checking if there is no missing values
   * column variables : unique_left_values = df['left'].unique().
   * retained = df[df.left==0].
   * check our dataset.


