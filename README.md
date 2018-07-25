# Datacup
1. Make sure all requirements from the requirements.txt file are available in environment
2. Run the notebooks Catboostv2, LGBMv2 and finally Stackfull
	Note: In all these there is a DATA_PATH variable at the top to tell where to look for the data. Replace it with your local path to data.
3. You can keep running Catboost and LGBM with different seeds (change at the top) to increase the stack performance.

The file requirements.txt explains what Python libraries have to be in the environment. There are two notebooks in Extra which are there 
simply as exploratory and are part of the final presentation to illustrate the tradeoff between complexity and precision. The other 
directories are there to host the outputs of the different notebooks.