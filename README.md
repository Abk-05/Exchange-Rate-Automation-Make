# 📊 Automated Currency Exchange Tracker

This project automates the collection of real-time currency exchange rates using **Make.com**. It fetches USD-based exchange rates via API and logs them into Google Sheets for tracking, analysis, and dashboarding.

---

# 🚀 Features

- ✅ **Real-time API Integration**  
  Fetches live exchange rates using ExchangeRate-API  

- 📈 **Automated Data Logging**  
  Stores USD, INR, and EUR values in Google Sheets  

- 📂 **Dataset Included**  
  Historical data in CSV format  

- 🧠 **Data-Ready Structure**  
  Perfect for Power BI, Python, or analytics  

---

# 🛠️ Tech Stack

- **Automation Tool:** Make.com (Integromat)  
- **API:** ExchangeRate-API (v6)  
- **Storage:** Google Sheets  
- **Data Format:** CSV  

---

# 🧩 Workflow Overview

```mermaid
graph TD
A[HTTP Request - ExchangeRate API] --> B[Extract Currency Data]
B --> C[Google Sheets - Add Row]
