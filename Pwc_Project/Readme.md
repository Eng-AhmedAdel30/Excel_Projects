# 📊 Call Center Performance Dashboard

> **Built with Microsoft Excel** | PwC-styled Analytics Tool  
> *Better insights. Stronger conversations.*

---

## Overview

The **Call Center Performance Dashboard** is an interactive Excel-based analytics tool built in the PwC visual style. It provides call center managers and analysts with a holistic view of operational performance — covering agent productivity, topic distribution, call resolution, and time-based trends.

**Tagline:** *Insight-driven decisions. Better customer experiences.*

---


## Screenshots

### Home Page
![Home Page](<Screenshots/1.Home Page.png>)

### Overview
![Overview](<Screenshots/2.Overveiw.png>)

### Time Analysis
![Time Analysis](<Screenshots/3.Time Analysis.png>)

---
## Dashboard Pages

### 1. 🏠 Home Page

The landing page of the dashboard. It introduces the tool and provides navigation buttons to the two analytical sections:

| Section | Description |
|---|---|
| **Overview** | Holistic view of call center performance, key metrics, and trends across teams, channels, and queues |
| **Time Analysis** | Analyze call handling times, wait times, and related metrics to improve efficiency and customer experience |

---

### 2. 📈 Overview

A comprehensive operational snapshot with the following components:

**KPI Cards (Top Row)**

| KPI | Value |
|---|---|
| Total Calls | 5,000 |
| Avg Satisfaction | 3.4 |
| ASA (sec) | 67.52 |
| Resolution Rate | 90% |
| Avg Talk Duration | 3.75 |

**Charts**

- **No. of Calls / Agent** — Bar chart showing individual agent call volume
- **No. of Calls / Topic** — Radar/spider chart breaking down calls by support category
- **Answered VS Not Answered** — Horizontal bar chart (Answered: 4,054 | Not Answered: 946)
- **Resolved VS Not Resolved** — Treemap/bar chart (Resolved: 3,646 | Not Resolved: 1,354)
- **Answer Rate Gauge** — Speedometer gauge showing 81% answer rate

---

### 3. ⏱️ Time Analysis

Focuses on temporal patterns to support staffing and scheduling decisions:

**Charts**

- **No. of Calls / Day (by weekday)** — Line chart comparing call volume across days of the week (peak: Monday with 770 calls)
- **No. of Calls / Day (by date)** — Line chart showing daily call volume across the month (days 1–31)
- **No. of Calls / Months** — Donut chart showing monthly distribution:
  - January: **36%**
  - February: **32%**
  - March: **32%**

---

## Key Metrics

| Metric | Value | Description |
|---|---|---|
| Total Calls | 5,000 | Total inbound calls in the period |
| Avg Satisfaction | 3.4 / 5 | Average customer satisfaction score |
| ASA (sec) | 67.52 | Average Speed of Answer in seconds |
| Resolution Rate | 90% | Percentage of calls fully resolved |
| Avg Talk Duration | 3.75 min | Average duration per call |
| Answer Rate | 81% | Percentage of calls answered |

---

## Charts & Visualizations

| Chart | Type | Location |
|---|---|---|
| Calls per Agent | Bar Chart | Overview |
| Calls per Topic | Radar Chart | Overview |
| Answered vs Not Answered | Horizontal Bar | Overview |
| Resolved vs Not Resolved | Bar/Area Chart | Overview |
| Answer Rate | Gauge Chart | Overview |
| Calls per Weekday | Line Chart | Time Analysis |
| Calls per Date | Line Chart | Time Analysis |
| Calls per Month | Donut Chart | Time Analysis |

**Topics covered in the radar chart:**
- Admin Support (976)
- Contract Related (976)
- Payment Related (1,007)
- Streaming (1,022)
- Technical Support (1,019)

**Agents tracked:**
Becky · Dan · Diane · Greg · Jim · Joe · Martha · Stewart

---

## Filters & Interactivity

Both the Overview and Time Analysis pages include a **Refresh** button and interactive slicers:

**Month Filters**
- February
- January
- March

**Topic Filters**
- Admin Support
- Contract Related
- Payment Related
- Streaming
- Technical Support

> All charts update dynamically when filters are applied using Excel slicers.

---

## How to Use

1. **Open** the `.xlsx` file in Microsoft Excel (2016 or later recommended).
2. **Navigate** between pages using the top navigation buttons: `Home Page` → `Overview` → `Time Analysis`.
3. **Filter** the data using the month and topic slicers on the right-hand panel.
4. **Refresh** the visuals using the orange **Refresh** button after changing filters.
5. **Analyze** KPI cards and charts to identify performance trends and areas of improvement.

---

## File Structure

```
📁 Call-Center-Dashboard/
│
├── 📊 CallCenter_Dashboard.xlsx       # Main Excel dashboard file
│
├── 📁 Screenshots/
│   ├── 1__Home_Page.png               # Home page screenshot
│   ├── 2__Overview.png                # Overview page screenshot
│   └── 3__Time_Analysis.png           # Time Analysis page screenshot
│
└── 📄 README.md                       # This file
```
