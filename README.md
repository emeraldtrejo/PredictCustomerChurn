# PredictCustomerChurn

Instructions
By clicking the folder icon in the top left of this workspace, you can see the folder and file structure for this project.

Each of the three files you need to complete for this project are already created for you and in the other open tab:

churn_library.py
churn_script_logging_and_tests.py
README.md
As this is a project in best coding practices, a notebook of the original code used to solve the problem has been provided already in the churn_notebook.ipynb (available in this tab).

It will be your job for this project to use this starting code to complete the two .py files listed above.

You will notice there are a number of functions that have already been provided with document strings in each of these files. These functions have been set up to guide you to a solution (no intended tricks here). However, if you would like to refactor the notebook in an alternative way to the setup in these files that is also okay, as long as you meet all the requirements in the Rubric.

Setting Up Environment Trouble Shooting
Though many of the libraries used in this notebook are a common part of data manipulation and machine learning models, there are a few useful command line installations that might prove to be useful when working in this workspace, as well as if you try to run files on your local machine.

Error


QXcbConnection: Could not connect to display
Aborted
Solution


import os
os.environ['QT_QPA_PLATFORM']='offscreen'
Install the linter and auto-formatter:


pip install pylint
pip install autopep8
Formatting, Linting & Running Scripts
Once you have scripted your results, the following should hold:

Running the below code in the terminal should test each of the functions and provide any errors to a file stored in the logs folder.

ipython churn_script_logging_and_tests.py
You may choose to add an if __name__ == "__main__" block that allows you to run the code below and understand the results for each of the functions and refactored code associated with the original notebook.

ipython churn_library.py
You should check the pylint score using the below. Many of the common data science variable names don't meet pep8 standards, and these are probably okay to leave.

pylint churn_library.py
pylint churn_script_logging_and_tests.py
You should make sure you don't have any errors, and that your code is scoring as high as you can get it! You might shoot for well over 7.

To assist with meeting pep 8 guidelines, use autopep8 via the command line commands below:

autopep8 --in-place --aggressive --aggressive churn_script_logging_and_tests.py
autopep8 --in-place --aggressive --aggressive churn_library.py
