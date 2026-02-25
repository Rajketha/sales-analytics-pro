# 📊 Sales Analytics Pro

A full-stack, interactive Sales Analytics Web Application designed for data analysts and business intelligence professionals. This project demonstrates a complete data lifecycle from raw transactional data to actionable insights.

## 🚀 Key Features

### 🖥️ Interactive Live Dashboard
- **Real-time KPI Tracking**: Monitor critical business metrics like Total Revenue, Profit, Margin, and Average Order Value (AOV) instantly.
- **Dynamic Visualizations**: High-performance charts powered by **Chart.js**, including:
    - **Monthly Trend Lines**: Track revenue and profit growth over time.
    - **Regional Doughnuts**: Visualize market share and margins across geographic territories.
    - **Product Performance**: Horizontal bar charts identifying top-selling items.
    - **Customer Demographics**: Age distribution analysis to understand buyer personas.

### 🧠 Automated Insight Engine
- **SQL-Driven Intelligence**: A backend engine that runs complex SQL queries to detect business trends automatically.
- **Natural Language Insights**: Generates 5-10 actionable bullet points after every data update, identifying regional risks, growth spikes, and payment preference shifts.
- **Dynamic Context**: Insights update instantly when new data is imported or manually added.

### 📥 "Work on My Data" Mode
- **CSV Bulk Import**: Upload custom datasets to transform the dashboard's context instantly.
- **Fuzzy Column Mapping**: Intelligent logic that automatically detects and maps divergent column names (e.g., "Item" → "Product", "Sales" → "Revenue").
- **Clear & Append Options**: Flexibility to either start fresh or add to existing historical data.

### 🛠️ Smart Data Cleaning Pipeline
- **Auto-Normalization**: Backend pipeline handles title-casing, white-space stripping, and standardizing regional names.
- **Intelligent Validation**: Automatic date formatting, currency symbol stripping, and duplicate Order ID detection.
- **Predictive Defaults**: Smartly calculates missing values (like Cost Price) based on historical product margins.

### 🍱 Tech Stack & UI
- **Backend**: Python, Flask, SQLite.
- **Frontend**: Vanilla JavaScript (ES6+), CSS Grid/Flexbox, Chart.js.
- **Design System**: Premium **Dark Glassmorphism** UI featuring frosted effects, smooth transitions, and high-contrast typography.
- **Analysis**: Advanced SQL (Window Functions, CTEs, Cohort Analysis).

## 📂 Project Structure

```text
sales-analytics-pro/
├── app.py                  # Flask Core: API + Insights Engine
├── init_db.py              # Database Schema & Migrations
├── seed_data.py            # Initial seed of 60K transactional rows
├── static/
│   ├── style.css           # Premium Dark UI Design
│   └── app.js              # SPA Logic & Chart Lifecycle
└── templates/
    └── index.html          # Interactive Dashboard Template
```

## ⚙️ Quick Start

1. **Clone & Install**:
   ```bash
   git clone https://github.com/Rajketha/sales-analytics-pro.git
   cd sales-analytics-pro
   pip install flask
   ```

2. **Initialize & Seed**:
   ```bash
   python init_db.py
   # (Optional) Seed with sample data
   python seed_data.py
   ```

3. **Run**:
   ```bash
   python app.py
   # Open http://localhost:5000 in your browser
   ```

---
*Created as a high-performance Data Analyst portfolio piece.*
