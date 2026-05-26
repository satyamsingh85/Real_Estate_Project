# Real Estate Business Intelligence Dashboard

An interactive, multi-dimensional Power BI dashboard designed to monitor corporate real estate metrics, financial investments, and agent performance. This application transforms complex property transactional records into actionable strategic insights for executive-level decision-making.

## 📁 Project Components
* **`Real_Estate_Project.pbix`**: The core Power BI project file containing the data model, interactive dashboard visual layers, and customized calculations.

## 📊 Data Model Structure
The dashboard integrates data across multiple relational tables, as managed in the internal schema:
* **`Property details`**: Focuses on spatial metrics, houses sold, operational costs, and localized revenue.
* **`Customer Details` / `Employee Logs`**: Tracks international buyer locations, revenue generated per client, and individual agent sales numbers.
* **`calander`**: The centralized corporate date-dimension table used to map transactional records to specific quarters and months.
* **`Measure Table`**: A dedicated container isolating all custom business metrics and Key Performance Indicators (KPIs).

---

## 📈 Dashboard Features & Insights

### 1. Global Market & Agent Auditing
* **Geographical Distribution Map**: A visual map tracking expenses, revenue allocations, and total volume of transactions across global regions (including the United States, United Kingdom, South Korea, Malaysia, Italy, India, France, and Argentina).
* **Agent Performance Matrix**: A structural leaderboard tracking employee profiles (e.g., Emma Johnson, James Smith, Liam Brown, Olivia Jones) alongside their absolute revenue contributions.

### 2. Micro-KPI Cards
* **Expense Metrics**: Real-time evaluation card tracking absolute operational expenditure.
* **Profit Multipliers**: Instant reporting on net profit thresholds.
* **Sales Volume Counters**: Transparent counter displaying overall revenue generated and properties sold.

### 3. Trend & Advanced Analytics
* **Quarterly Expenditure Flow**: An area chart mapping operational expenses across fiscal quarters (`Qtr 1` to `Qtr 4`) to observe cyclical spending patterns.
* **Seasonal Revenue Engine**: A clean bar chart evaluating revenue spikes across calendar months (`Jan` to `Dec`).
* **Pareto Chart (Revenue by Country)**: An advanced analytics chart combining absolute country revenue metrics with a cumulative percentage line to discover the top 20% geographic markets driving 80% of business growth.
* **Temporal Slicers**: Interactive dynamic buttons enabling rapid, single-click timeline switches across fiscal years (`2025`, `2026`, and `2027`).

---

## 🛠️ How to Get Started

### Prerequisites
* You must have **Microsoft Power BI Desktop** installed on your machine.

### Deployment Steps
1. **Clone the repository:**
   ```bash
   git clone https://github.com
   ```
2. **Launch Project**: Navigate to the directory and double-click `Real_Estate_Project.pbix` to launch the workspace.
3. **Interact**: Use the year slicers or click on specific agents/countries within the charts to cross-filter the entire dashboard dynamically.
