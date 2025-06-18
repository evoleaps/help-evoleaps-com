# Understanding Column Mapping

Smart Import for Excel uses AI to automatically map columns from your Excel file to the corresponding fields in Dynamics 365 Business Central — even if the column names are not an exact match.

## How Column Mapping Works

When you upload a file and click **Generate**, the app performs intelligent matching between:

- Excel column headers (e.g., "Customer No.", "Posting Date", "Amount")
- Business Central field names in the selected table (e.g., `Sell-to Customer No.`, `Posting Date`, `Amount`)

The mapping logic takes into account:
- Synonyms and variations in field names  
- Data types and expected formats  

## Manual Adjustments

If any columns are not mapped automatically, or if the mapping is incorrect, you can manually:
- Select the correct target field for each column  
- Preview how values will be filled in the destination table

## Tips for Better Results

- Use clear, descriptive column headers in your Excel file.
- Avoid merging header cells or using multiple header rows.

