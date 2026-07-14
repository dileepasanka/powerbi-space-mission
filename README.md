# 🚀 Power BI – Global Space Mission Dashboard

An interactive, multi-page Power BI report that analyzes **global space mission activity from 1957 to present day** — covering launch volumes, success/failure rates, active rocket fleets, and spending across countries, agencies, and companies. Built to turn a raw historical launch log into a decision-ready story for anyone exploring trends in the space industry.

---

## 📌 Project Overview

Since Sputnik 1 in 1957, thousands of orbital and sub-orbital missions have been launched by dozens of countries and private companies. This report consolidates that history into a single, filterable dashboard so patterns — who launches the most, who succeeds most often, how costs compare, and how activity has evolved over time — are visible at a glance instead of buried in a spreadsheet.

The report is built entirely in **Power BI Desktop** and demonstrates end-to-end BI workflow: data modeling, DAX measure design, and interactive report design (drill-throughs, slicers, and cross-filtering) aimed at both technical and non-technical audiences.

---

## 🧭 Report Pages

The `.pbix` file contains four connected report pages, each answering a different business question:

### 1. Landing Page
The entry point of the report. Presents top-line KPIs (total missions, overall success rate, active rockets, total mission spend) alongside global navigation buttons, giving users an immediate high-level snapshot before they drill into specifics.

### 2. Global Launch Pulse
A time-based and geographic view of launch activity. Tracks how launch frequency has grown or slowed year over year, and maps where launches are concentrated globally, helping surface momentum shifts in the space race across decades.

### 3. Mission Status
Focused on mission outcomes — breaking down launches by **success, failure, and partial failure**. This page highlights reliability trends over time and by launch provider, useful for spotting which eras or agencies had the strongest track records.

### 4. Agency & Country Performance
A comparative view ranking **companies and countries** by launch volume, success rate, and spend. Designed to answer "who's leading the space industry" from multiple angles — commercial players (e.g., SpaceX, NASA, Roscosmos) versus national programs.

*(A rendered summary of all pages is included in `Summary.png` for a quick visual preview without opening Power BI.)*

---

## ✨ Key Features

- **Interactive drill-throughs** — jump from a summary visual directly into page-level detail for a selected country, agency, or year.
- **Custom DAX measures** — purpose-built calculations for success rate, launch cost aggregation, and year-over-year growth, rather than relying on raw column values.
- **Cross-filtering slicers** — filter by country, company, launch status, and time period, with all visuals on the page updating in sync.
- **Clean, presentation-ready layout** — consistent color theme and KPI card design intended for stakeholder walkthroughs, not just internal analysis.

---

## 🗂️ Repository Contents

| File | Description |
|---|---|
| `Space Mission.pbix` | The full Power BI report file — open in Power BI Desktop to explore live. |
| `1 Landing Page.png` | Screenshot of the report's home/overview page. |
| `2 Golbal Launch pulse.png` | Screenshot of the launch activity trend & map page. |
| `3 Mission Status.png` | Screenshot of the mission outcomes breakdown page. |
| `4 Agency country Performance.png` | Screenshot of the agency/country comparison page. |
| `Summary.png` | Combined preview of all report pages. |

---

## 🛠️ Tools & Techniques Used

- **Power BI Desktop** — report design and visualization
- **Power Query** — data cleaning and shaping
- **DAX (Data Analysis Expressions)** — custom measures for KPIs and rates
- **Drill-through & bookmarks** — guided, interactive navigation between pages
- **Data modeling** — structuring mission, agency, and country data for efficient filtering

---

## ▶️ How to Use

1. Clone or download this repository.
2. Open `Space Mission.pbix` in **Power BI Desktop** (free download from Microsoft).
3. Use the slicers and navigation buttons on each page to explore missions by country, company, year, or outcome.
4. Hover over visuals for tooltips with additional detail, or right-click data points to drill through to related pages.

---

## 👤 Author

Built by **Dileepa Rathnayake** as part of a broader data analytics portfolio, applying Power BI skills to a real-world historical dataset outside of a banking/finance context to demonstrate cross-domain analytical capability.

---

## 📄 License

No license specified yet — add one (e.g., MIT) if you'd like others to freely reuse or build on this report.
