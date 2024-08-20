# Credit-score

The solution helps to predict based on several properties of the borrower to determine whether to issue a loan or not.

[Kaggle-link](https://www.kaggle.com/competitions/GiveMeSomeCredit)!

<figure style="float:display:block; margin-left: auto; margin-right: auto;">
	<img src="images/pipeline.jpg" alt="" width="100%">
</figure>
<div style="clear:both">

I tested many ways of predicting the results. Check my solution more detailed in the *.ipynb. 
Briefly - the best model gave me 86.5 AUC-ROC score by LightGBM. Also, suprisingly by GridSearching
I achieved also quite impressive results.

# Note:
For more comfortable usage, please download the results. Unfortunately, due to the jupyter bug it shows all
traceback of gridsearchCV and CatBoost what is uncomfortable. Check this out locally, because nodes will be closed automatically!
