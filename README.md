# 🏥 DevClinic Appointment Insights | Power BI Dashboard

## 📌 Project Overview
DevClinic Appointment Insights is an interactive Power BI dashboard designed to analyze patient appointments, provider workload, and healthcare service efficiency.

The project focuses on understanding appointment trends, patient distribution, provider performance, and waiting time patterns to support better operational decision-making.

## 🎯 Project Objectives
- Analyze total patient appointments and unique patients.
- Compare appointments across different provider roles.
- Identify average patient waiting time by provider.
- Understand patient distribution based on waiting time.
- Analyze appointment trends over time.
- Identify appointment patterns across different weekdays.

## 🛠️ Tools & Technologies
- **Power BI** – Dashboard development and data visualization.
- **Power Query** – Data cleaning and transformation.
- **Microsoft Excel** – Dataset preparation and handling.

## 🧹 Data Cleaning & Transformation
Performed data preparation using Power Query:

- Promoted the first row as column headers.
- Corrected column data types.
- Handled null values using Fill Down.
- Removed unnecessary empty columns.
- Extracted days from the Waiting Time column.
- Converted waiting time into weeks.
- Created conditional waiting time categories.

### Waiting Time Categories
| Category | Waiting Period |
|---|---|
| 1 Week | 0–7 days |
| 2 Week | 8–14 days |
| 3 Week | 15–21 days |
| 4 Week | 22–28+ days |

## 📊 Dashboard Features

The dashboard includes the following visualizations:

1. **Appointments by Provider Role** – Compares appointments handled by Psychologists, MDs, and Nurses.
2. **Average Waiting Time by Provider Role** – Analyzes average patient waiting time.
3. **Patient Distribution by Waiting Time** – Shows patient distribution across waiting time categories.
4. **Appointments Over Time** – Tracks appointment trends over time.
5. **Appointments by Provider Role vs Day of Week** – Uses a matrix to compare weekday patterns.
6. **Appointments by Provider Role** – Uses a treemap to visualize provider-wise appointment distribution.

### KPI Cards
- Total Appointments
- Unique Patients
- Average Waiting Time (Days)
- Total Provider Roles

### Interactive Slicers
- Appointment Date
- Provider Role
- Waiting Time (Weeks Bucket)

## 💡 Key Business Questions
- How many appointments are requested and scheduled over time?
- Which provider role handles the most appointments?
- What is the average waiting time for each provider role?
- How are patients distributed across providers?
- What are the appointment patterns across weekdays?
- Which waiting time category has the highest patient count?

## 📁 Project Files
- `Dev Clinic report.pbix` – Power BI dashboard file.
- `DevClinic Appointment Data.xlsx` – Source dataset.
- `DevClinic Problem Statement.pdf` – Project requirements and problem statement.

## 📈 Key Learnings
- Hands-on experience with Power BI dashboard development.
- Data cleaning and transformation using Power Query.
- Working with date and time data.
- Creating calculated categories for waiting time analysis.
- Building interactive dashboards using slicers, KPI cards, and multiple visualizations.
- Translating business requirements into meaningful insights.

## 👨‍💻 Author
**Sarthak Paliwal**

B.Tech – Information Technology

**Skills:** Power BI | Excel | Power Query | Data Analytics

🔗 **GitHub:** https://github.com/sarthakpaliwal09

---

⭐ If you find this project useful, feel free to explore the repository and share your feedback!
