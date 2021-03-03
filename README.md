# emotex
an emotion classifier of a string sentence and live srteaming tweets from twitter

-----Exotex Deployment Instructions-------
Recquirements:
1. Anaconda
2. Jupyter notebook
3. Packages like
         - tweepy v 3.9.0
         - scikit-learn v 0.22.1
         - nltk v 2.4.5
         - tkinter (comes built-in with python)
Instructions/ Steps:
1. Make sure all the packages mentioned above are installed in anaconda
2. Launch jupyter notebook from anaconda, create a folder and upload all the files:
     -d1.csv(original dataset)
     
     -data_clean.csv(cleaned dataset, code file is also included)
     
     -data_clean_NLP.ipynb (source code to clean the dataset d1. this code will create the data_clean.csv file in the end)
     
     -creating_model.ipynb (this source code shows all the algorithms we tried along with their classification reports )
     
     -predictions.ipynb (this code shows the initial tests and classifications of the best fit svm model)
     
     -Implementation_Gui.ipynb (this code shows the testing of gui and classifications in notebook too.)
     
     -GUI.ipynb (this code contains the GUI with machine learning and works on the data_clean.csv which was made through data_clean_NLP.ipynb )
     
3. Run the GUI.ipynb for the tkinter window to enter sentence or hashtag for emotion analysis.
4. Run the data_clean_NLP.ipynb, creating_model.ipynb, predictions.ipynb and Implementation_Gui.ipynb to see the process. run files in this order only.


