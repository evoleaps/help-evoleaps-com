# How Copilot Uses Your Excel File

Smart Import for Excel uses Azure OpenAI services to enhance the import experience through intelligent column mapping.

## What Happens When You Upload a File

When you upload your Excel file:

- **Only the header row (column names)** is extracted and securely sent to the Azure AI service.
- **No row-level data** (i.e., actual records) is sent or processed by the AI.

The AI then analyzes the column names and returns a suggestion for how each column should be mapped to fields in Business Central.

## AI Mapping Behavior

- The AI attempts to recognize common patterns (e.g., “Customer No.”, “Amount”, “Posting Date”) even if the names are not an exact match.
- It returns a list of suggested mappings between Excel column names and Business Central fields.
- These mappings are applied automatically but can be reviewed and adjusted before completing the import.

## Privacy and Security

- **Only headers are shared** with the AI service.
- **No sensitive or personal data** is exposed.
- All communication is done securely and in compliance with Microsoft’s data handling standards.

## Summary

The Copilot feature helps reduce setup time and improve data accuracy by using AI to interpret your Excel headers and suggest how to map them to the appropriate fields in Business Central — all without requiring predefined templates.
