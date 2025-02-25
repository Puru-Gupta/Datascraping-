# Web Scraping & Data Processing Project (USAID)

## Overview  
Developed and deployed **custom web scrapers** to extract data from multiple government portals using **Python, Selenium, and BeautifulSoup**. The scrapers handled JavaScript-driven content, bypassed CAPTCHA codes using **OCR (Python-tesseract)**, and processed approximately **30 million rows** of data. The extracted data was structured, stored in an **MS SQL database**, and delivered to the client.

## Websites Scraped  
1. **Ease of Living (EOL) Portal** - [https://eol.nic.in](https://eol.nic.in)  
   - **Data Extracted:**  
     - Availability Of Basic Facilities  
     - Beneficiary IDs Data Quality  
     - Ease Of Living Data Comparison  
     - Enumeration Progress  
     - Survey Data At A Glance  
     - Verification Progress  

2. **MGNREGA (Mahatma Gandhi National Rural Employment Guarantee Act) Portal** - [https://nreganarep.nic.in](https://nreganarep.nic.in)  

3. **PM Awas Yojana (Pradhan Mantri Awas Yojana) Portal** - [https://rhreporting.nic.in](https://rhreporting.nic.in)  

4. **Socio-Economic and Caste Census (SECC) Portal** - [https://secc.gov.in](https://secc.gov.in)  

## Technologies Used  
- **Python** – Core language for development  
- **Selenium** – For interacting with JavaScript-based content  
- **BeautifulSoup** – For parsing static HTML content  
- **Python-tesseract (OCR)** – To bypass CAPTCHA during data extraction  
- **Pandas** – For transforming raw data into structured formats  
- **MS SQL Database** – For storing final data with master mapping  

## Data Processing & Quality Checks  
- Performed **data profiling, outlier detection, and consistency checks** to improve data quality.  
- Standardized and structured the extracted data for usability.  
- **Final data was stored in an MS SQL database** with **master mapping** and **delivered to the client**.  

---
