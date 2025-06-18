# How Smart Import Works

Smart Import for Excel automates the process of importing data into Dynamics 365 Business Central.

Here’s how it works step by step:

## 1. Upload Your Excel File

Upon the app installation, the Import with Copilot action is available on supportet pages. After clicking on it,
select your Excel file. You can drag and drop the file or browse to upload.

The file should contain a header row with column names (e.g., "Name", "Posting Date", "Amount", "Customer No.", etc.).
Once the file is uploaded, click **Generate** to initiate column analysis with AI.

## 2. AI-Powered Column Mapping

Smart Import uses AI to analyze the column names and match them to the corresponding fields in Business Central — even if the labels don’t exactly match.

Examples:
- `"Client Name"` → `"Name"` (Customer)
- `"Invoice Date"` → `"Posting Date"` (General Journal)
- `"Item Desc"` → `"Description"` (Item)


## 3. Validation & Preview

Before importing, the system:
- Ensures all required fields are covered
- Flags invalid or missing values
- Gives you a preview of how the data will be imported

This step helps reduce errors before data reaches Business Central.

## 4. Import into Business Central

When you're ready, simply click **Keep it**.

The data will be inserted directly into the selected table (e.g., General Journal, Customer List), and is immediately available for use.

---

Smart Import removes the need for templates or manual field mapping — making your Excel-to-BC import process faster, smarter, and less error-prone.
