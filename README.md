# Google-sheets-ETL-data-pipeline

Gwanda Fisa, a small SME selling thrifted shoes, needed a low-cost, user-friendly solution to track sales, supplies, and costs. With a team of one proprietor sourcing shoes from Gikomba market and two salespeople, the business handles tens to hundreds of daily sales. I built a data pipeline to ingest, extract, transform, and load data into a database.

## Pipeline Components
- **Data Ingestion**: Google Sheets, chosen for its free access, ease of use for non-technical staff, suitability for low to moderate data volumes, and real-time collaboration for multiple users.
- **Data Extraction**: Google Sheets API, selected for its free cost and seamless integration with Google Sheets.
- **Data Transformation**: Python’s pandas library.
- **Data Loading**: PostgreSQL database on Aiven’s cloud platform for reliability, data integrity, and scalability.

## Limitations
1. **Scalability**: Google Sheets struggles with large datasets (>10,000 rows), limiting growth.
2. **Manual Errors**: Manual data entry in Google Sheets risks inaccuracies despite validation.

This pipeline offers a cost-effective, accessible solution for Gwanda Fisa’s data needs, leveraging Google Sheets for entry, pandas for transformation, and Aiven PostgreSQL for storage. 
