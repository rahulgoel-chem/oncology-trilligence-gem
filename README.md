# Clinical Trials Change Monitor (4-Hour Automated Alerts)

This project is a Python-based automated monitoring system that tracks changes in clinical trials from **ClinicalTrials.gov**. It specifically targets trials related to **ADCs, CAR-T, Lymphoma, Leukemia, and Solid Tumors**.

## 🚀 Features
* **Real-time Extraction**: Fetches the latest trial data using the ClinicalTrials.gov API (v2).
* **Automated Cleaning**: Removes duplicates, handles missing NCT IDs, and fills blanks with "NA".
* **Delta Comparison**: Compares snapshots every 4 hours to detect changes in status, dates, enrollment, and locations.
* **Professional Reporting**: Generates automated reports in **.docx** and **.pdf** formats.
* **Email Alerts**: Sends an email notification with attached reports whenever an update is detected.

## 🛠️ Tech Stack
* **Language:** Python 3.x
* **Libraries:** `requests`, `python-docx`, `fpdf`, `json`, `smtplib`
* **Environment:** Designed for Google Colab or local Python environments.

## 📋 Monitored Fields
The system specifically watches for updates in:
* Study Status
* Primary Completion Date & Completion Date
* Enrollment Numbers
* Locations/Facilities
* Sponsors & Collaborators
* Phases & Start Dates

## ⚙️ Setup Instructions
1. **Clone the Repo**:
   ```bash
   git clone [https://github.com/yourusername/clinical-trials-monitor.git](https://github.com/yourusername/clinical-trials-monitor.git)
