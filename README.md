# data-analysis-exercises
 Exercises for the data analysis course

In the MINGW64 terminal activate the Python project virtual environment with `source project/Scripts/activate`.  I created the virtual environment with the command `python -m venv project`.

To capture all the Python package requirements use `pip freeze > requirements.txt`.  In another system (another virtual environment) you can install these with `pip install -r requirements.txt`.

To store the R dependencies, we use the `renv` library.  `renv::snapshot()` should create files (and should actually create the Python requirements file).  `renv::restore()` will restore the packages (Python and R) from the snapshotted information.

A basic runthrough is at https://alexweston013.medium.com/how-to-set-up-an-r-python-virtual-environment-using-renv-483f67d76206 .

