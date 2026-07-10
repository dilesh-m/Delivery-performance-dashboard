# # 📦 Delivery Performance Analytics Dashboard

# 

---

## 🔹 Project Overview

The objective of this project was to design an **automated Power BI dashboard** to monitor **delivery and courier performance** across multiple locations.

The dashboard provides stakeholders with a **real-time, interactive view** of shipment volumes, courier contribution, and geographic delivery distribution.

This report refreshes automatically using **scheduled refresh**, ensuring that decision-makers always work with the **latest data**.

---

## 🔹 Business Problem

Operations and logistics teams often struggle to:

- Track overall shipment performance
- Compare courier partners effectively
- Identify high-performing cities, states, and pincodes
- Manually update reports, leading to outdated insights

### ❓ Key Questions Addressed:

- Which courier handles the highest number of shipments?
- Which states and cities contribute most to deliveries?
- How does delivery volume change over time?
- Can reporting be automated to reduce manual effort?

---

## 🔹 Data Description

The dataset contains shipment-level information, including:

- Order and delivery details
- Courier partner names
- Customer and location information
- Delivery dates and geographic attributes (city, state, pincode)

The data is refreshed automatically to reflect the latest operational updates.

---

## 🔹 Tools & Technologies Used

- **Power BI Desktop**
- **Power Query** – Data cleaning & transformation
- **DAX** – KPI calculations and aggregations
- **Data Modeling** – Relationships and optimization
- **Power BI Service** – Scheduled refresh & automation

---

## 🔹 Data Preparation & Transformation

Using **Power Query**, I:

- Cleaned inconsistent courier names
- Removed errors and null values
- Standardized location fields (City, State, Pincode)
- Created date-related columns for time-based analysis
- Optimized the dataset for better refresh performance

---

## 🔹 Data Modeling & Measures

- Built an optimized data model to avoid duplicate calculations
- Created **DAX measures** for:
    - Total Shipments
    - Total Customers
    - Delivered Pincodes
    - Courier-wise shipment percentage
- Ensured measures responded dynamically to slicers (Year, Month, Day)

---

## 🔹 Dashboard Features

- Total Shipments
- Total Customers
- Total Delivered Pincodes

### 🚚 Courier Performance

- Courier-wise shipment distribution
- Easy comparison of courier partners

### 🌍 Geographic Analysis

- Top 5 States
- Top 5 Cities
- Top 5 Pincodes

### 🎛️ Interactivity

- Year, Month, and Day slicers
- Cross-filtering across visuals

### 🔄 Automation

- Configured **scheduled refresh** in Power BI Service
- Eliminated manual data updates

## 🔹 Key Insights

- A single courier partner contributes nearly **60% of total shipments**
- Deliveries are highly concentrated in **specific states and cities**
- A small set of pincodes drives a large portion of deliveries
- Automated refresh significantly improves reporting efficiency

## 🔹 Business Impact

- Reduced manual reporting effort
- Improved visibility into courier performance
- Enabled faster, data-driven operational decisions
- Provided a scalable dashboard framework for logistics analysis

## 🔹 Skills Demonstrated

- Power BI Dashboard Development
- Power Query (ETL)
- DAX & KPI creation
- Data modeling best practices
- Scheduled refresh & automation
- Business-focused data storytelling

## 🔹 Challenges & Learnings

### Challenges:

- Handling inconsistent courier names
- Optimizing performance with large datasets
- Managing refresh errors during transformation

### Learnings:

- Importance of clean data models
- How automation improves data reliability
- Designing dashboards for non-technical users

## 🔹 Final Outcome

This project demonstrates my ability to:

- Build **end-to-end Power BI solutions**
- Automate reporting workflows
- Translate raw logistics data into actionable insights
