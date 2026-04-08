# 📊 Automated Currency Exchange Tracker

This project automates the daily collection of currency exchange rates using **Make.com**. It fetches the latest rates for USD, INR, and EUR from an API and logs them into Google Sheets for real-time tracking and dashboarding.

---

# 🚀 Features

- ✅ **Real-time API Integration**  
  Uses ExchangeRate-API to fetch live conversion rates.

- 📈 **Automated Logging**  
  Automatically appends USD, INR, and EUR rates into Google Sheets with timestamp.

- 🧠 **Data Scientist Mindset**  
  Structured data for easy use in Power BI, Python, or dashboards.

---

# 🛠️ Tech Stack

- **Automation Tool:** Make.com (Integromat)  
- **API:** ExchangeRate-API (v6)  
- **Storage:** Google Sheets  

---

# 🧩 Workflow Overview

```mermaid
graph TD
A[HTTP Request - ExchangeRate API] --> B[Extract Currency Data]
B --> C[Google Sheets - Add Row]
