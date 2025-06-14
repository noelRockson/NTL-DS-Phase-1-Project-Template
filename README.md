# ✈️ Aviation Safety Analysis  
![Aircraft Image](https://upload.wikimedia.org/wikipedia/commons/thumb/f/fb/Cessna_172S_Skyhawk_SP%2C_Private_JP7294014.jpg/640px-Cessna_172S_Skyhawk_SP%2C_Private_JP7294014.jpg)

# Project Title  
**Aircraft Risk Analysis for Safer Commercial and Private Aviation**

## 🧭 Overview  
This project explores aviation accident data to identify the safest aircraft models for continued operation in commercial and private sectors. Using real-world historical data from the National Transportation Safety Board (NTSB), the analysis aims to provide data-driven recommendations to enhance flight safety and inform fleet management decisions.

## 💼 Business Understanding  
In the aviation industry, selecting the safest and most reliable aircraft models is crucial for minimizing risks, improving public confidence, and reducing operational losses. This project seeks to:
- Identify which aircraft types have the highest and lowest incident severity
- Recommend aircraft models that are still in operation and have a strong safety record
- Support decision-making for fleet acquisition or phase-out

## 📊 Data Understanding  
The dataset includes over 80,000 aviation accident records collected by the NTSB. Key variables include:
- `Make`, `Model` of aircraft
- Injury outcomes (`Fatal`, `Serious`, `Minor`, `Uninjured`)
- `Event.Date`, `Location`, `Phase.of.Flight`
- Aircraft technical specifications (`Number.of.Engines`, `Engine.Type`, etc.)

## 🛠️ Data Preparation  
Several data cleaning and transformation steps were performed:
- Removed irrelevant columns and rows with missing critical values (e.g., `Make`, `Model`, `Event.Date`)
- Replaced missing injury data with 0 or "Unknown"
- Extracted `Event.Year` from `Event.Date`
- Grouped and aggregated injury statistics by aircraft model

## 📈 Analysis and Results/Recommendations  
- Visualized accident trends and injury distributions from 1948 to 2022
- Compared total injuries vs. uninjured passengers by aircraft
- Cross-checked model usage with current global fleet activity

### ✅ Final Aircraft Recommendations:
1. **Boeing 737** – Commercial mainstay with excellent survivability and oversight  
2. **Cessna 180** – Rugged and reliable for utility and remote operations  
3. **Piper PA-18** – Safe for private and training use; forgiving flight characteristics  

Each model was selected based on low fatality rates, favorable safety records, and continued active service.

## ✅ Conclusion and Next Steps  
This project highlights the importance of integrating injury data and current aircraft operations to guide safety recommendations. Future improvements include:
- Integrating weather, location, and pilot experience data
- Predictive modeling of accident likelihood per aircraft class
- Publishing a dashboard for real-time aircraft risk evaluation

## 📁 Repo Structure  

