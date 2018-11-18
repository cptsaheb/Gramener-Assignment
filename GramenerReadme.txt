PROBLEM STATEMENT : 

Usecase # 2 - Credit Risk

The dataset contains information of about a thousand individuals, create a model that attempts to classify their credit risk. Since the original dataset is fairly cumbersome to work with, feel free to cross-reference the rows against the kaggle hosted version. 

Dataset: https://archive.ics.uci.edu/ml/datasets/Statlog+%28German+Credit+Data%29
https://www.kaggle.com/uciml/german-credit 
----------------------------------------------------------

Jupyter Notebook file attached:
1.imported the required libraries.
2.loaded the file using pandas
3. printed the loaded file.
4. on visualization saw 'NaN'under 'Saving accounts' and 'checking accounts' columns.
5. dropped those columns as it will not affect much.
6. Using Label encoder, Labeled all the categorical columns 'sex, Housing, Checking account, Purpose, Savings accounts'.
7.Using pyplot, plotted some graphs between some columns to see where we can figure out the risk.

8. RESULTS

>>People from Age 23 to 32 are the target customer and the amount can be in range 2000 to 5000.
>>Offers for car loan and radio loan can pick up more customers or lenders.
>>Short term credit with credit range 2000 t0 5000 yield maximum customer and profits.



