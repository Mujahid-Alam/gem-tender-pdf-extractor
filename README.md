# 🏛️ GeM Tender Scraper & PDF Data Extraction System

A Python-based end-to-end data pipeline that scrapes tender listings from the Government e-Marketplace (GeM) portal, downloads associated PDF documents, extracts structured information, and stores the data in MongoDB for analysis and automation.

---

## 📌 Project Overview

The **Government e-Marketplace (GeM)** (https://bidplus.gem.gov.in/all-bids) is a 100% Government-owned Section 8 company established under the Department of Commerce, Ministry of Commerce and Industry, Government of India.

This project automates the extraction of tender data from the GeM portal, processes PDF documents, and stores structured procurement information in a database for further analysis.

---

## 🚀 Features

- 🔎 Scrapes live tender listings from GeM portal
- 📄 Downloads tender-related PDF documents
- 🧠 Extracts structured data from PDFs using `pdfplumber`
- 🗄️ Stores data in MongoDB
- 🔄 Handles multiple categories and pagination
- ⚙️ Automates end-to-end data collection workflow

---

## 🛠️ Technologies Used

- Python
- BeautifulSoup (bs4)
- Requests
- urllib
- pdfplumber
- MongoDB
- pymongo

---

## 📂 Project Workflow

1. Scrape tender listings from GeM portal  
2. Extract bid details (bid number, dates, department, etc.)  
3. Download associated PDF files  
4. Parse and extract structured data from PDFs  
5. Store cleaned data into MongoDB collections  

---

## 🗄️ Database Structure

### Collection: `alltabdata`
- bid_no  
- item  
- qty  
- department details  
- start_date / end_date  
- PDF URL  

### Collection: `pdfreaddata`
- end_date  
- end_time  
- opening_date  
- organisation  
- department_name  
- item_category  
- quantity  

---

## 📊 Use Cases

- Government procurement analysis  
- Tender market research  
- Data engineering practice project  
- Automation of document extraction  
- Backend ETL pipeline learning  

---

## ⚠️ Disclaimer

This project is built for **educational and research purposes only**.  
It does not misuse or modify any government data.

---

## 🚀 Future Improvements

- Add REST API layer using Flask / FastAPI  
- Schedule scraping using Cron jobs  
- Dashboard visualization (React / Plotly)  
- Dockerize the application  
- Improve PDF parsing accuracy with NLP

---

## 👨‍💻 Author

**Full Stack Developer**  
React | Django | Odoo | Python | Web Scraping | MongoDB  

Focused on building scalable automation and ERP-based solutions.
