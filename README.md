# Attrition-Data-Cleaning
Employee Attrition is something companies are always trying to combat. Encoding, cleaning, and imputating are necessary steps before analysis. Wielding a trash-in trash-out philosophy, we tackle this dirty dataset in python.


### Finished Notebook ###
This work was done on a virtual lab primarily, to see the thought process, check the files above where I include my juypter notebook.

### Programs Used ###
- Excel
- Python

### Scope of Work ###
- Merge 15 files into 1
- Clean file by:
  - removing duplicates
  - removing missing rows w/ target variable
  - removing rows that cannot be knowingly restored
  - feature engineer new columns that can add context
  - imputating where possible
  - notating missing data
- Encode file to be ready for predictive modeling using:
    - Addressing categorical variables by changing to binary
    - One hot encoding low cardinality categorical variables
    - Target Encoding higher cardinality categorical variables
    - Feature scaling numerical values to ensure the model treats them properly

### Goal ###
The goal of this project was to merge and clean data primarily in python to prepare it for predictive modeling. This was course work for a DAT 430 class.

### Data Source ###
The data was provided by SNHU. The scenario discusses reducing employee attrition by encompassing the many attributes the dataset has avaliable and predicting how likely an employee is to attrition or not. The raw merged dataset has 7040 rows and 36 attributes.

### Data Opportunities ###
This data didn't come with a codebook that could give info on how certain columns were calculated. Monthly income, monthly rate, and hourly rate didn't seem to have any clear connections which is odd for employees working a job. This made it difficult to clean and certain assumptions had to be made. 

### Process and Reflection ###
I learned a lot cleaning this dataset in Python. I certainly learned removing duplicates is the 1st important step before addressing null values. I found using the combination of Python and Excel handy to cross reference using Excel filters and sometimes removing more complex rows easier. This was my first time imputating data, notating data is missing, and really diving into how predictive modeling and data analysis can go hand in hand. 
