## Data Cleaning Summary – Sales Dataset

In this task, I performed data cleaning and preprocessing on the sales dataset using Microsoft Excel. The following steps were taken:

1. **Column Header Cleanup**
   - Removed any extra spaces from headers.
   - Converted all headers to lowercase and replaced spaces with underscores for consistency.

2. **Blank Cells and Duplicates**
   - Used `COUNTBLANK` and filters to check and handle missing values.
   - Removed duplicate rows using Excel’s “Remove Duplicates” feature.

3. **Data Formatting**
   - Converted the `order_value_eur` and `cost` columns to number format.
   - Adjusted decimal places to ensure uniform financial data representation.
   - Verified data types using `ISTEXT` and `ISNUMBER` functions.

4. **Date Column Fix**
   - Some date entries were in text format (e.g., left aligned).
   - Used:  
     - Select date column → Data → Text to Columns → Delimited → Next → Next → Date: MDY → Finish
     - Then Format Cells → Custom → `dd-mm-yyyy`
   - This ensured all date values were in the same and correct format.

5. **Table Format**
   - Converted the dataset into a proper Excel Table to enable structured formatting and easy filtering.

6. **Final Output**
   - Saved the cleaned data as `.xlsx`.
   - Uploaded cleaned Excel file and screenshots of raw vs cleaned data.

This cleaned dataset is now ready for further analysis, visualization, or modeling.
