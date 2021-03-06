
## Data Cleaning: TECHNICAL and CONSISTENCY corrections of the data

The goal of this module is to clean the raw data obtained from the [data extraction](/2_data_extraction). in particular the data cleaning consists of TECHNICAL and CONSISTENCY corrections of the data. 

    Validation of the attributes names and number

    Check that the number of columns of numerical attributes is consistent with what is expected

    Show whether there is any column with special characters (NA, NaN, Null, Inf, -Inf)

    Change found special caracters with a specific numeircal value

    Check whether there are inconsistent attributes values, e.g, negative values

The code is written in R environment. The folder [data cleaning](./3_data_cleaning) contains i) the [R-code](data_cleaning.rmd), ii) [a raw data sample file](/raq_data_sample.txt) obtained by the [data extraction](/2_data_extraction) module, iii) a [R-Markdown](https://cdn.rawgit.com/rempic/TEST_GIT/v1/DATA_CLEANING/data_cleaning.html) with code and description of the data cleaning workflow.  

Open the R-Markdown for more details about the workflow: [Data Cleaning](https://cdn.rawgit.com/rempic/TEST_GIT/v1/DATA_CLEANING/data_cleaning.html)
