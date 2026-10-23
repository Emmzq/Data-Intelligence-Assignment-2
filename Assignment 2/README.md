

# Packages required to run the code
The following packages are needed to run the code in this assignment project:
- jupyter
- pandas
- xgboost
- sklearn
- matplotlib

Each can be installed using `pip` and the following commands:

`pip install xgboost`

`pip install pandas`

`pip install jupyter`

`pip install scikit-learn`

`pip install matplotlib`

# Running the code
## 1: data_prep.ipynb
For this file, the following files need to be downloaded and placed into their respective location in the project folder structure:
- microbiology_cultures_cohort.csv
- microbiology_culture_prior_infecting_organism.csv
- Inmicrobiology_cultures_demographics.csv  
- microbiology_cultures_ward_info.csv

All the relevant data files are placed in a `./Data` -folder on the same level as where the file is being run like this:

`./Data/microbiology_cultures_cohort.csv`<br>
`./data_prep.ipynb`

After the data has been placed into the right location, run all of the modules in the file `data_prep.ipynb`.

## log_reg_model.ipynb and xgb_model.ipynb
After running `data_prep.ipynb` successfully creating the `data_prepared.csv`-file, the following files can be executed:
- log_reg_model.ipynb
- xgb_model.ipynb
These files should not need any modifications and after running the files, the results can be seen at the two bottom most modules.

