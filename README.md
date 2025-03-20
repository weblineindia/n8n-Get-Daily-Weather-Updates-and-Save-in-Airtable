# 🌦️ Get Daily Weather and Save It in Airtable

## 📄 Template Description
This smart automation workflow, created by the **AI team at WeblineIndia**, helps with the **daily collection and storage of weather data**.

Using the **OpenWeatherMap API** and **Airtable**, this solution gathers vital weather details such as **temperature, humidity, and wind speed**. The automation ensures daily updates, creating a dependable **historical record of weather patterns** for future reference and analysis.

---

## ✅ Workflow Steps

### 1. Set Schedule Trigger (Cron Node)
- **What It Does:** Triggers the workflow automatically at a specific time daily (e.g., 7 AM).
- **How to Set It Up:** 
  - Configure the **Cron node** in n8n to run every day at your preferred time.

---

### 2. Fetch Weather Data (HTTP Request)
- **What It Does:** Retrieves current weather data from the **OpenWeatherMap API**.
- **How to Set It Up:** 
  - Use the **HTTP Request node**.
  - Include your **API Key** and query parameters (e.g., `q=London&units=metric`).
  - Specify the city and the desired units (metric/imperial).

---

### 3. Parse Weather Data (JSON Parse Node)
- **What It Does:** Extracts essential weather information like temperature, humidity, and wind speed from the API response.
- **How to Set It Up:** 
  - Utilize the **JSON Parse node** to parse the weather API response.
  - Map the necessary fields for storage.

---

### 4. Store Data in Airtable (Airtable Node)
- **What It Does:** Inserts the parsed weather data into your Airtable base.
- **How to Set It Up:** 
  - Use the **Airtable node**.
  - Map extracted fields such as **temperature**, **humidity**, and **wind speed** to their respective Airtable columns.

---

### 5. Save and Execute
- **What It Does:** Finalizes and activates the workflow.
- **How to Set It Up:** 
  - Save and **activate** the workflow.
  - Once live, the automation will fetch and store weather data **automatically every day**.

---

## 📊 Outcome
This robust solution, developed by **WeblineIndia**, **reliably collects and archives daily weather data**. It provides businesses and individuals with an easily accessible **record of weather trends** for analysis and informed decision-making.

---

## 🚀 Benefits
✅ Automates daily weather data collection  
✅ Creates a historical weather record  
✅ Reduces manual effort and errors  
✅ Facilitates data-driven decisions based on weather trends  

---

## 📌 Example Use Cases
- Agriculture weather tracking
- Travel companies monitoring weather conditions
- Historical weather trend analysis
- Automated reporting systems for weather-dependent industries

---


## 🌐 About WeblineIndia
At **WeblineIndia**, we specialize in creating **custom automation solutions** and **innovative software workflows** that help businesses streamline operations and achieve efficiency.

This **Weather Data Fetcher** is just one example of our expertise in delivering **value through technology**.

---