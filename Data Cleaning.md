## Data Cleaning
### 1-	Remove duplicates
### 2-	Standardize the format of each column:
####  a.	Date format for the Date column.
####  b.	Number format for the columns Client_Age, Service Duration Minutes, and Customer Satisfaction Rating.
####  c.	Text format for the columns Client Gender, Service Type, Payment Method, and Customer Booking Type.
####  d.	Currency format for the column Service Price CAD.
####  e.	General format for the columns Client ID and Employee ID.
### 3-	Check for missing values: Use the Conditional Formatting to detect the missing values.  The result showed no missing value.
### 4-	Handle the outliers:
####  a.	Check the column Service Price CAD for any unusual amount of money by using the conditional formatting. The result showed no outlier
####  b.	Check the column Service Duration Minutes for any unusual duration of service and it showed no outlier. 
### 5-	Data Validation: For the column Client Age, I used data validation to validate the age is between 18 and 65 years old. 
### 6-	Regroup the Client age in to different Age groups for a clear analysis:
####  a.	18-24
####  b.	25-34
####  c.	35-44
####  d.	45-54
####  e.	55-64
####  f.	65+
### 7-	Create and regroup the column Service Price into Service package:
  a.	$20-$40
  b.	$41-$60
  c.	$61-$80
  d.	$81-$100
  e.	$100 +

