# Data-Scraping-Flipkart-
Scraping of Macbook product data from flipkart

Procedure
•	Changed working directory to the folder containing selenium script
•	Imported the necessary libraries
•	Inspected the webpage to locate all the required details to be extracted from the webpage
•	Once each detail was located using “inspect”, it was passed on to corresponding variables using list comprehension
•	For each variable containing the detail, appropriate data conversion was done according to the question requirements
•	Reusable function was defined (flipkart(soup))) 
•	Using the flipkart(soup)) function, dataframe (flip) was defined which contained the required details
•	flip dataframe was converted to .csv file as “Flipkart.csv” 


Challenges
•	While extracting price, the output was of the form '₹84,940₹92,9008% off'
•	The required price was the one between two ‘₹’s (final price after discount)
•	The required price was extracted using  “.split('₹') method”
