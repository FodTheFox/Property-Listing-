<h1>Property Listing Dashboard</h1>

 

<h2>Description</h2>
This project focused on resolving data cleaning challenges in a synthetic property listing dataset, highlighting the importance of accurate data representation in real estate. The dataset was deliberately 'dirty,' offering valuable experience in identifying and fixing common data issues. My primary objective was to handle inconsistencies in measurements and values using Excel, with a specific emphasis on PowerQuery."

<br />


<h2>Languages and Utilities Used</h2>

- <b>Excel</b> 
- <b>PowerBi</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2> walk-through:</h2>

<p align="center">
Inspecting Data: <br/>

![Screenshot 2024-09-26 192714](https://github.com/user-attachments/assets/7c7edca6-64da-437d-816d-1be8a5d24322)



Upon immediate inspection the dataset presents several challenges, including missing values, inconsistent text formats, and mixed measurement units. The most significant issue is converting measurements for the 'price per square foot' field, which had more than four different units, making it difficult to standardize the data (this was inspected by filtering)
 
<br />
Data Cleaning Process:  <br/>


![Screenshot 2024-09-26 193048](https://github.com/user-attachments/assets/1bb4f016-6ba3-4f66-bc47-4af0ec2ad79c)

<br />

I started by removing duplicates, clearing blanks, and standardizing column names using Excel's SUBSTITUTE, TRIM, and CLEAN functions. For price formatting, I encountered issues with text and numerical value mixing. To resolve this, I standardized all currency values under the header 'Lac' (representing the local currency) and ensured all price columns contained only numerical values."

A critical part of the cleaning process was converting all property areas to square feet. I used conversion rates for square meters, square yards, and other units. To handle text values mixed with numbers, I used Excel functions like VALUE, LEFT, TRIM, and FIND to isolate and convert text strings to numerical values. This allowed for accurate and consistent measurements across the dataset.


<br />
Transferring Data to PowerBI: <br/>

Testing out how i can remove Lac and keep as an integer as opposed to conjoining them together with text values 

<br />
Completing dashboard:  <br/>

![Property Listing](https://github.com/user-attachments/assets/4bffcf0a-4717-4146-80b5-7b7e23bf5db7)

<br />
<br />

</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
