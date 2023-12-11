## Cleaning at source in Excel

### Introduction
You're working in data analysis at Adventure Works, and you've just received a new dataset from your manager, Renee. She's tracking sales and inventory data in Excel, and you're asked to create a Power BI dashboard to visualize the data for management. When you open the file, you realize the data is messy and unorganized. Rows and columns are misaligned, there are missing values, and the formatting is inconsistent. You know that Microsoft Power BI is a powerful tool for visualizing and analyzing data, but you also know that to get the most from the data, you need to clean and prepare the data in Excel first, before importing it to Power BI. How do you go about that?

This reading assists you in understanding the importance of cleaning data at the source in Excel. You will discover the various functions and features that can help you do the cleaning before importing the data into Power BI. By the end of this reading, you should understand how to use Excel functions to clean and prepare your data in Excel for further analysis in Power BI.

Cleaning at source in Excel
First, let's reap what cleaning data at the source means. It refers to the process of refining and correcting your data in the original source (in this case, Excel) before importing it into another tool for further analysis or visualization (such as Power BI). Cleaning data at the source can save you time and effort and ensure better quality results in your final reports and visualizations, leading to better insights and more informed decision-making.

Now, let's explore some examples of common Excel functions that can help you clean data at the source.

### Text Functions
Excel provides a wide range of text functions to help clean textual data. Some examples include:

LEFT, RIGHT, and MID: These functions help extract specific parts of text from a cell. For instance, if you have a dataset with full names in a single column, you can use these functions to separate first and last names into different columns.

TRIM: This function removes extra spaces from a text string. It's useful for cleaning up inconsistent spacing between words and ensuring uniformity in your data.

UPPER, LOWER, and PROPER: These functions convert text to uppercase, lowercase, or proper case (proper case being where the first letter is capitalized, and the rest are in lowercase). This can be helpful when dealing with data that has inconsistent capitalization.

Date and Time Functions
Working with dates and times in Excel can be difficult, but these functions can help you manage such data:

DATE, TIME, and DATEVALUE: These functions help you create date or time values and convert text strings into date or time formats. This is particularly useful when importing data from external sources that may have different date or time formats.

YEAR, MONTH, and DAY: These functions extract the year, month, or day from a date value. They can be useful for grouping data by specific time periods.

Logical Functions 
Logical functions can help you clean up and categorize data based on specific conditions. Some examples include:

IF: This function tests a condition and returns one value if the condition is true, and another value if it's false. For example, you can use the IF function to categorize sales amounts as "high" or "low" based on a threshold value.

COUNTIF and SUMIF: These functions count or sum the values in a range that meet a specified condition. They're useful for aggregating data based on specific criteria.

Lookup Functions
Lookup functions help you find and retrieve data from other parts of the worksheet or other worksheets based on specific criteria. Examples include:

VLOOKUP and HLOOKUP: These functions search for a value in the first column or row of a table and return a corresponding value from another column or row. They're useful for merging data from multiple sources or filling in missing data.

INDEX and MATCH: These functions can be combined to perform more flexible lookups than VLOOKUP and HLOOKUP. They're especially useful when the lookup value is not in the first row or column of the table or when you need to perform a two-way lookup.

### Data Validation and Conditional Formatting
These features can help you identify and correct errors in your data before importing it into Power BI:

Data Validation: This tool allows you to set criteria for the allowable data in a cell or range of cells. For example, you can restrict the input to numbers within a specific range, dates within a specific period, or a list of predefined options. Data validation can help you prevent errors and inconsistencies in your data.

Conditional Formatting: With this feature, you can apply different formats (such as colors, fonts, or icons) to cells based on specific conditions. Conditional formatting can help you quickly spot errors, outliers, or patterns in your data.

Tip: Excel functions and features are explored in detail in the Creating data in Microsoft Excel and preparing for data analysis course in this program.

### Conclusion
Cleaning data at the source in Excel is essential to ensure high-quality results in your Power BI visualizations and reports. By using Excel functions text functions, date and time functions, logical functions, lookup functions, and features like data validation, and conditional formatting, you can refine and tidy up your data before importing it into Power BI. Remember, investing time and effort in cleaning your data at the source will not only save you time during the analysis and visualization stages but also improve the accuracy and reliability of your insights. With these tools and techniques at your disposal, you're well-equipped to tackle any messy dataset that comes your way.