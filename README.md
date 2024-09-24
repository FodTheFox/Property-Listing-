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
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

Upon immediate inspection the dataset presents several challenges, including missing values, inconsistent text formats, and mixed measurement units. The most significant issue is converting measurements for the 'price per square foot' field, which had more than four different units, making it difficult to standardize the data (this was inspected by filtering)

<br />
Data Cleaning Process:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

I started by removing duplicates, clearing blanks, and standardizing column names using Excel's SUBSTITUTE, TRIM, and CLEAN functions. For price formatting, I encountered issues with text and numerical value mixing. To resolve this, I standardized all currency values under the header 'Lac' (representing the local currency) and ensured all price columns contained only numerical values."

A critical part of the cleaning process was converting all property areas to square feet. I used conversion rates for square meters, square yards, and other units. To handle text values mixed with numbers, I used Excel functions like VALUE, LEFT, TRIM, and FIND to isolate and convert text strings to numerical values. This allowed for accurate and consistent measurements across the dataset.


<br />
Transferring Data to PowerBI: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Running a few more check on PowerQuery:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

Testing out how i can remove Lac and keep as an integer as opposed to conjoining them together with text values 

<br />
Completing dashboard:  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
