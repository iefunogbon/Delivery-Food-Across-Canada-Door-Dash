# Delivery-Food-Across-Canada-Door-Dash

FOOD DELIVERY ACROSS CANADA -DOOR DASH ANALYSIS REPORT USING POWER BI
I played the role of a Junior Data Analyst at TnetPro Limited, Luton United Kingdom to analyze the dataset of Door dash Food Delivery across Canada.
 

# Objective
To analyze the door dash food delivery across Canada  and gain insight to what customers ordered and the distance it took to deliver the orders to customers

# Data Structure
The dataset consists of  the following rows and columns:
118 Rows and 7 Columns of order transaction in Brampton

369 Rows and 7 Columns of order transaction in Calgary

268 Rows and 7 Columns of order transaction in Edmonton

568 Rows and 7 Columns of order transaction in Montreal

239 Rows and 7 Columns of order transaction in Ottawa

844 Rows and 8 Columns of order transaction in Toronto

694 Rows and 8 Columns of order transaction in Vancouver and 

198 Rows and 8  Columns of order transaction in Winnipeg.

  The column in the dataset includes: unnamed, Restaurant, url,  Category, Distance, Star, and num_reviews.

# Data Cleaning
While conducting the data cleaning,  the workbook dataset  of each city  was combined using Append in Power BI. 
The  final dataset now consists of  3298 rows and 8 rows  to carry out the analysis. The first column(unnamed) was renamed as column1 consisting of just numbers was removed.
The distance column  had a combination of  time and distance that was separated with a dot. The column was split to time and distance column separately.  Some of the distance data was inputted in ft and mi and I converted the column distance to mi.
In addition, the category column consists of price symbol sign and the category of product delivered to clients. Then the column was split to price, category 1, and category 2. Also, the num review column was cleaned by removing the brackets. 

# Analysis and Insights
The analysis was conducted using Power Business Intelligence(Power BI).
From the 3298 rows  data of door dash delivery  in  Brampton, Toronto, Vancouver, Calgary,  Montreal, Ottawa, Edmonton. and Winnipeg, the following insights was carried out in the process of the analysis:

•	Restaurant: “Toronto” has the highest number of restaurant( 844 restaurant  ) which  is  7 times more  than the “ Brampton (118 restaurant )” the  city with the lowest  number of  restaurant.
