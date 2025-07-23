# 🏭 Production Dashboard – Power BI

A dynamic and intuitive dashboard built in **Power BI** for tracking and optimizing production performance.

![Dashboard Preview](<img width="1378" height="771" alt="ProductionDashboard - Power BI - Google Chrome 22_07_2025 22_37_24" src="https://github.com/user-attachments/assets/14349a85-5e0d-43e2-9519-b3f64ff80bf3" />
)

## 📌 Features

### 🎯 KPI Cards
- ✅ **Total Approved** – Quantity of successfully produced items
- ❌ **Total Rejected** – Quantity of faulty or unapproved items
- ⏱️ **Productive Hours** – Time spent actively producing
- 🛑 **Downtime Hours** – Time lost due to interruptions or failures

### 📈 Visuals
- **Area Chart** – *Total Produced by Month*  
  Track production trends and seasonal patterns over time.

- **Gauge Chart – % Productivity**  
  Displays the ratio of productive hours to total time.

- **Gauge Chart – % Quality**  
  Shows the percentage of approved items out of total production.

### 🧩 Slicers
- 👷 **By Operator** – Filter metrics by employee or workstation  
- 📅 **By Month** – Analyze data across different periods

## 🔧 Data Model Highlights

| Field Label           | Column Name         | Description                       |
|----------------------|---------------------|-----------------------------------|
| operador             | `OperatorName`      | Name of machine operator          |
| ocorrência           | `IssueType`         | Type of issue or interruption     |
| data início / fim    | `StartDate`, `EndDate` | Operation dates                |
| hora início / fim    | `StartTime`, `EndTime` | Operation
