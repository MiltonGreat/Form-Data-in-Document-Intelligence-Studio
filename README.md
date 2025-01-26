# Document Processing with Azure AI Document Intelligence

## Overview

This project explores the use of Azure AI Document Intelligence to automate the processing of documents such as receipts and invoices. By leveraging Azure's prebuilt models, this project demonstrates how to extract structured data from unstructured text, capturing key/value pairs, tables, and other meaningful information.

The project focuses on how Document Intelligence builds upon traditional Optical Character Recognition (OCR) capabilities by transforming unstructured text into structured, analyzable data.

### Features

1. Analyze and extract data from forms and documents.

2. Identify field names and associated data (key/value pairs).

3. Process information in tables for easy integration into databases.

4. Automate data extraction for common business scenarios such as:
- Processing receipts for expense tracking.
- Extracting invoice details for accounting purposes.

### Prebuilt Model for Receipts

This project leverages a prebuilt receipt model that is trained to identify specific fields such as:

  - Merchant name, address, and phone number.
  - Date and time of the transaction.
  - Purchased items, quantities, and prices.
  - Total amounts, subtotals, and tax values.
  - Process a variety of receipt formats, including thermal receipts, hotel receipts, and parking receipts.

#### Sample Receipt

![receipt](https://github.com/user-attachments/assets/2b8b8a56-6889-4b5b-9015-5e1a5308c388)

### Project Workflow

1. Create an Azure AI Services Resource:
- In the Azure Portal, create a resource for Azure AI Document Intelligence.
- Use the free tier to test features if you're new to the service.

2. Explore Prebuilt Models in Document Intelligence Studio:
- Use the Receipt Model to analyze and extract data from receipts.
- Experiment with other prebuilt models for documents such as invoices and ID cards.

3. Test Data Extraction:
- Upload a receipt image or PDF.
- Observe the extracted fields, such as merchant details, date, and totals.

#### Analyze a receipt in Document Intelligence Studio

![screenshot-documentintelligence ai azure com-2025 01 26-11_18_27](https://github.com/user-attachments/assets/ffd37258-3dbd-4770-bfa2-45ac4c87bcb3)

### What I Learned

- Azure AI Document Intelligence simplifies document processing by combining OCR with machine learning models trained to recognize data structures.
- Prebuilt models reduce the need for custom training, enabling faster implementation for common business scenarios.
- Automating document processing saves time and minimizes errors in data handling.

### Future Enhancements

- Integrate with a database to store extracted data for further analysis.
- Build custom models to handle unique document formats.
- Use the extracted data to generate real-time business insights.

### References

https://learn.microsoft.com/en-us/training/modules/analyze-receipts-form-recognizer/4-exercise/?ns-enrollment-type=learningpath&ns-enrollment-id=learn.wwl.document-intelligence-knowledge-mining
