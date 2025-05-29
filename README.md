# 🌍 Global COVID-19 Analysis Dashboard with Power BI

[![Power BI](https://img.shields.io/badge/Tool-Power%20BI-yellow?style=for-the-badge&logo=powerbi)](https://powerbi.microsoft.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)](#)

> A compelling, interactive, and data-rich **Power BI Dashboard** analyzing the global impact of COVID-19 from 2020 to 2023 across major nations, including the G7, Asia, and Middle East. Global COVID-19 Analysis Dashboard using Power BI | Multi-Nation Insights  This project provides a comprehensive Power BI dashboard analyzing the global impact of COVID-19 from 2020 to 2023. It offers comparative insights across countries such as India, China, USA, UK, Russia, and members of the G7.

---

## ✨ Live Features

📊 **Country-Wise Comparison**  
🕒 **Time-series Analysis (2020–2023)**  
🌐 **Geopolitical Insights: India 🇮🇳 vs China 🇨🇳 vs Pakistan 🇵🇰**  
⚰️ **Death Rate Trends across Continents**  
📌 **Top 5 Pandemic-hit Nations**  
🌍 **G7 Nations Comparative Dashboard**

---

## 📌 Project Preview

📄 [View Full Dashboard PDF](./Covid19Analysis.pdf)
*Interactive Power BI dashboard visualizing confirmed cases, death rates, and recovery stats*

---

## 📈 Visualized Metrics

- 📅 Yearly Breakdown (2020–2023)
- 🦠 Confirmed Cases (Average)
- 💀 Death Count (Average)
- 💚 Recovered Count (Average)
- 📉 Death Rate (%) by Nation which is measured as (Average Death count / Average Confirmed Cases)*100
- This is death rate among infected individuals also known as case fatality rate or CFR
- 📍 Comparative Country Clusters

---
## 📉 Understanding Case Fatality Rate (CFR)

> **Case Fatality Rate (CFR)** is a crucial epidemiological indicator that measures the severity of a disease by calculating the percentage of diagnosed individuals who eventually die from it.

### 🔢 Formula

\[
\text{CFR (\%)} = \left( \frac{\text{Total Deaths}}{\text{Total Confirmed Cases}} \right) \times 100
\]

### 🧠 Why CFR Matters

- 📌 **Indicates disease severity** and public health impact.
- 📉 A high CFR may point to:
  - Ineffective treatment or overwhelmed healthcare systems
  - Late diagnosis or limited access to care
  - More aggressive viral strains
- 📈 A declining CFR may indicate:
  - Better testing and early detection
  - Improved healthcare infrastructure
  - Effective vaccination or natural immunity

### ⚠️ CFR vs IFR

> **CFR** considers only **confirmed cases**.  
> **IFR (Infection Fatality Rate)** accounts for **all infected people**, including undiagnosed cases — thus generally lower than CFR.

### 📊 CFR in This Dashboard

In this Power BI project, CFR is:
- Visualized as **year-wise trends** for each country (2020–2023).
- Used to **compare fatality outcomes** between nations like 🇮🇳 India, 🇺🇸 USA, 🇨🇳 China, 🇷🇺 Russia, and G7 members.
- Helps identify how different countries managed the pandemic over time.

---

## 🌍 Countries Analyzed

- **G7 Nations**: 🇺🇸 USA, 🇬🇧 UK, 🇯🇵 Japan, 🇨🇦 Canada, 🇫🇷 France, 🇮🇹 Italy, 🇩🇪 Germany  
- **Asia & Neighbours**: 🇮🇳 India, 🇨🇳 China, 🇵🇰 Pakistan  
- **Middle East**: 🇮🇷 Iran, 🇮🇱 Israel, 🇵🇸 Palestine  
- **Europe & Others**: 🇷🇺 Russia, 🇹🇷 Turkey, 🇬🇷 Greece, 🇾🇪 Yemen

---

## 🧰 Built With

- [Power BI Desktop](https://powerbi.microsoft.com/)
- DAX & Data Modeling
- ### Official COVID-19 Datasets (Johns Hopkins University CSSE)
    - 📄 [View Confirmed Cases Dataset](./data/time_series_covid19_confirmed_global.csv)
    - 📄 [View Death Cases Dataset](./data/time_series_covid19_deaths_global.csv)
    - 📄 [View Recovered Cases Dataset](./data/time_series_covid19_recovered_global.csv)
- Bing Maps for Geo-Visualization

---

## 🎯 Use Cases

- 🎓 Academic Research & Case Studies  
- 🧠 Healthcare Analytics  
- 📊 Business Intelligence Portfolios  
- 🏛️ Public Policy Insights  
- 📈 Data Storytelling Projects

---

## 📁 Project Structure
📦 Global-COVID19-PowerBI-Dashboard/
- 📄 Covid19Analysis.pdf                  - Exported Power BI dashboard as PDF
- 📄 LICENSE                              - MIT License file
- 📄 README.md                            - Project documentation
- 📁 data/                                - COVID-19 dataset folder (optional grouping)
   - all_country_flags_w80_dataset.csv   -Country flags and metadata
   - time_series_covid19_confirmed_global.csv
   - time_series_covid19_deaths_global.csv
   - time_series_covid19_recovered_global.csv

