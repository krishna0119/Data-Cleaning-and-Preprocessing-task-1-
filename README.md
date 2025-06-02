//Overview
This project focuses on cleaning and preprocessing a raw vehicle dataset containing various attributes like make, model, condition, mileage, price, and more. The objective is to prepare the dataset for further analysis or modeling by handling missing values, correcting data types, standardizing formats, and removing inconsistencies.

//Tools Used
-Python

-Pandas

-Jupyter Notebook (Task_1.ipynb)

-CSV format data files

//Dataset Description
Column	:Description
year	:The manufacturing year of the vehicle.
make	:The brand or manufacturer of the vehicle.
model	:The specific model of the vehicle.
trim	:Additional designation for the vehicle model.
body	:The body type of the vehicle (e.g., SUV, Sedan).
transmission	:The type of transmission in the vehicle (e.g., automatic).
vin	:Vehicle Identification Number, a unique code for each vehicle.
state	:The state where the vehicle is registered.
condition	:Condition of the vehicle, possibly rated on a scale.
odometer	:The mileage or distance traveled by the vehicle.
color	:Exterior color of the vehicle.
interior	:Interior color of the vehicle.
seller	Name of the vehicle seller or dealership.
mmr	:Market value estimate of the vehicle.
sellingprice	:Actual sale price of the vehicle.
saledate	:Date of sale, originally in unstructured string format.

//Cleaning and Preprocessing Steps
- Removed duplicate rows.

- Handled missing values:

Filled categorical fields (make, model, trim, body, transmission, etc.) with "unknown".

Filled numeric fields (condition, odometer, mmr, sellingprice) with median values.

Filled saledate nulls with the most frequent date.


/////////
- Standardized column names to lowercase with underscores.

- Converted date fields to datetime format.

- Cleaned text fields (trimmed spaces, consistent casing).

- Ensured proper data types for numerical and categorical columns.

///Files Included
Task_1.ipynb: Jupyter notebook with all preprocessing code and explanations.

cleaned_dataset_final.csv: The cleaned and processed dataset ready for use.

README.md: Project documentation.

//Usage
To run the notebook:

jupyter notebook Task_1.ipynb

Make sure your input CSV is placed in the same directory or update the path accordingly in the code.

//Contact
If you have any questions or suggestions, connect with me.
