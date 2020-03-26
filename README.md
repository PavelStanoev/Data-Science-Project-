# Data-Science-Project-
Data science project  - preprocessing research data and using machine learning (linear regression) in Jupyter Notebook . Integrated in  MySQL and Tableau Public


"Absenteeism_data" is a research on work absenteeism. It has been preprocessed and modeled in respectively 'Preprocessing.ipynb' and 'Modelling.ipynb' (Jupyter Notebook). Both files are merged in Module.py.

In 'Integration.ipynb' with the Module.py , the 'mode'l and  the 'scaler' made in 'Modelling.ipynb' we connect  with MYSQL database from where we are getting our new .csv file and integrating it in tableau for visual representation.


How to use the model with your new data : 

1.Collect your data in .csv file with the same information as the data in "Absenteeism_data.csv". Note : DO NOT change the names and the number of columns.

2.You dont need to run the 'Preprocessing.ipynb' and 'Modelling.ipyn'. Everything important is stored in 'Module.py' , 'model' and 'scaler'.

3.Run 'Integration.ipynb' with 'Module.py' , 'model' and 'scaler' in the same folder. NOTE : In the 'Integration.ipynb' code there is a line where you write your MYSQL username and password. Change it with your information , which you can find in the main window of the MYSQL Workbench.

4.From the MYSQL Workbench you can download the new .csv file and upload it in tableau for visual representation. I have uploaded an image of probability for absenteeism in regards of transportation expense and children.
