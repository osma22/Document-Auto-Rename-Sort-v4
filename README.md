# AI Document Automation System using N8N

An AI-powered document processing workflow that automatically watches a Google Drive HOLD folder, extracts data from scanned PDFs using OCR and AI, renames files intelligently, organizes them into the correct folders, and sends confirmation email notifications.

### Features

* Automatic Google Drive folder monitoring
* AI/OCR-based text extraction from scanned PDFs
* Smart detection of document date, company name, account holder, and account number
* Automatic file renaming using structured naming format
* Auto-sorting into company-specific folders
* Email notifications after processing

### Example Output

`2024.08 Southern California Edison Nisan Celik 123456.pdf`

### Workflow

1. Upload scanned PDF to HOLD folder
2. AI extracts and analyzes document data
3. File is renamed automatically
4. Document is moved to the correct folder
5. Confirmation email is sent automatically
