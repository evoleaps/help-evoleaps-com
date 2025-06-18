# Core Concepts

## What is AI-Powered Import?

Smart Import for Excel leverages AI to streamline and simplify the process of importing data into Dynamics 365 Business Central. Instead of relying on rigid templates or exact column names, the app uses artificial intelligence to interpret the structure of your Excel files.

### Key Capabilities

- **Intelligent Column Matching**  
  The app recognizes column headers even if they differ from the field names in Business Central. For example, "Due Date", "Deadline", or "Payment Date" may all be correctly mapped to the same journal field.

- **No Manual Setup**  
  There’s no need to define templates, mappings, or configurations. Simply upload your file and let the AI do the heavy lifting.

### Benefits

- Reduces manual effort and the risk of errors  
- Makes imports more accessible to non-technical users  
- Speeds up the data entry process

Smart Import’s AI engine is designed to enhance productivity and reduce friction in your daily workflows.


## How Smart Import Works

Smart Import for Excel automates the process of importing data into Dynamics 365 Business Central.

Here’s how it works step by step:

### 1. Upload Your Excel File

Upon the app installation, the Import with Copilot action is available on supportet pages. After clicking on it,
select your Excel file. You can drag and drop the file or browse to upload.

The file should contain a header row with column names (e.g., "Name", "Posting Date", "Amount", "Customer No.", etc.).
Once the file is uploaded, click **Generate** to initiate column analysis with AI.

### 2. AI-Powered Column Mapping

Smart Import uses AI to analyze the column names and match them to the corresponding fields in Business Central — even if the labels don’t exactly match.

Examples:
- `"Client Name"` → `"Name"` (Customer)
- `"Invoice Date"` → `"Posting Date"` (General Journal)
- `"Item Desc"` → `"Description"` (Item)


### 3. Validation & Preview

Before importing, the system:
- Ensures all required fields are covered
- Flags invalid or missing values
- Gives you a preview of how the data will be imported

This step helps reduce errors before data reaches Business Central.

### 4. Import into Business Central

When you're ready, simply click **Keep it**.

The data will be inserted directly into the selected table (e.g., General Journal, Customer List), and is immediately available for use.

---

Smart Import removes the need for templates or manual field mapping — making your Excel-to-BC import process faster, smarter, and less error-prone.


## Understanding Column Mapping
Smart Import for Excel uses AI to automatically map columns from your Excel file to the corresponding fields in Dynamics 365 Business Central — even if the column names are not an exact match.

### How Column Mapping Works

When you upload a file and click **Generate**, the app performs intelligent matching between:

- Excel column headers (e.g., "Customer No.", "Posting Date", "Amount")
- Business Central field names in the selected table (e.g., `Sell-to Customer No.`, `Posting Date`, `Amount`)

The mapping logic takes into account:
- Synonyms and variations in field names  
- Data types and expected formats  

### Manual Adjustments

If any columns are not mapped automatically, or if the mapping is incorrect, you can manually:
- Select the correct target field for each column  
- Preview how values will be filled in the destination table

### Tips for Better Results

- Use clear, descriptive column headers in your Excel file.
- Avoid merging header cells or using multiple header rows.



## How Copilot Uses Your Excel File

Smart Import for Excel uses Azure OpenAI services to enhance the import experience through intelligent column mapping.

### What Happens When You Upload a File

When you upload your Excel file:

- **Only the header row (column names)** is extracted and securely sent to the Azure AI service.
- **No row-level data** (i.e., actual records) is sent or processed by the AI.

The AI then analyzes the column names and returns a suggestion for how each column should be mapped to fields in Business Central.

### AI Mapping Behavior

- The AI attempts to recognize common patterns (e.g., “Customer No.”, “Amount”, “Posting Date”) even if the names are not an exact match.
- It returns a list of suggested mappings between Excel column names and Business Central fields.
- These mappings are applied automatically but can be reviewed and adjusted before completing the import.

### Privacy and Security

- **Only headers are shared** with the AI service.
- **No sensitive or personal data** is exposed.
- All communication is done securely and in compliance with Microsoft’s data handling standards.

### Summary

The Copilot feature helps reduce setup time and improve data accuracy by using AI to interpret your Excel headers and suggest how to map them to the appropriate fields in Business Central — all without requiring predefined templates.

