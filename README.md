
# City of Long Beach Crime Analytics Dashboard (2025)

### End-to-End Data Analytics Project using Python, Power BI, and Web Scraping

---

##  Overview
This project automates the process of collecting, cleaning, and visualizing monthly **crime statistics for the City of Long Beach (CA)**.  
The source data is published only as PDF reports on the **Long Beach Police Department website**, making it difficult to analyze trends manually.  

Using **Python** for automation and **Power BI** for visualization, this project turns those static PDFs into a dynamic dashboard that reveals year-to-date and month-over-month crime patterns.

---

##  Project Objectives
- Automatically **scrape monthly crime reports** from the official Long Beach Police Department site.  
- Extract tables from PDFs and **clean/normalize data** using Python (Pandas, Tabula-py).  
- Build a **Power BI dashboard** to visualize crime trends by type and month.  
- Enable ongoing updates — new PDFs can be parsed automatically and appended to the dataset.

---

##  Key Features
-  **Automated Web Scraper** – Fetches new monthly PDF reports using `requests` + `BeautifulSoup`.
-  **PDF Table Extraction** – Converts tabular data from complex PDFs via `tabula-py`.
-  **Data Cleaning Pipeline** – Cleans headers, handles nulls, and normalizes category names with `pandas`.
-  **Data Modeling** – Creates a star schema in Power BI (FactCrime + DimDate).
-  **Interactive Dashboard** – Visualizes:
  - Total incidents per month
  - Crime breakdown by category
  - Month-over-month % change
  - Year-to-date totals and comparison
-  **DAX Measures** for `Total Incidents`, `MoM %`, `YTD Incidents`, and category share.

---

##  Tech Stack
| Tool / Library | Purpose |
|-----------------|----------|
| **Python (Pandas)** | Data cleaning & transformation |
| **Requests / BeautifulSoup** | Web scraping (extract PDF links) |
| **Tabula-py** | PDF table extraction |
| **Power BI** | Interactive dashboard and DAX metrics |
| **Google Colab** | Notebook environment for pipeline |
| **GitHub** | Version control & documentation |

---

## 📂 Project Structure
