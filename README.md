# Lead Management MIS Dashboard

## Dashboard Preview
<!-- Take a screenshot of your final dashboard and save it as 'dashboard.png' in this folder -->
<!-- Then replace the line below with your image -->
![Lead Management MIS Dashboard](dashboard.png)

---

## Project Overview

This is a Management Information System (MIS) project built to track and report on the complete sales lead pipeline for a product-based company operating across 4 cities in Maharashtra, India.

The goal was to give sales managers a single view to monitor lead volume, conversion performance, salesperson efficiency, and regional revenue — without digging through raw data.

---

## Dataset Details

| Field | Details |
|---|---|
| Source | Self-created structured dataset |
| Total Records | 500 leads |
| Time Period | January 2026 – April 2026 |
| Cities Covered | Pune, Mumbai, Nashik, Nagpur |
| Salespersons | Amit, Neha, Raj, Sonal |
| Products | Laptop, Mobile, Tablet, Accessories |
| Lead Sources | Website, Facebook, Instagram, LinkedIn, Referral |

**Columns in dataset:**
Lead ID, Date, Month, Year, Lead Source, Product, Salesperson, Status, Deal Value, Follow-up Date, Region

---

## Tools Used

- **Microsoft Excel** — Data structuring, Pivot Tables, KPI calculations, Dashboard layout
- **Power Query** — Data cleaning and transformation
- **Excel Charts** — Bar charts, Donut chart, Line chart
- **Slicers** — Interactive filters for Region, Salesperson, Status

---

## What I Built

### KPI Cards (5 metrics)
| KPI | Value |
|---|---|
| Total Leads | 500 |
| Converted Leads | 119 |
| Conversion Rate | 24% |
| Total Revenue | ₹2,11,85,879 |
| Average Deal Size | ₹42,372 |

### Charts & Visuals

**1. Lead Source Analysis (Horizontal Bar Chart)**
- Compares lead volume across 5 sources: Website, Facebook, Instagram, LinkedIn, Referral
- Website and Facebook are the top lead generators (98 and 113 leads respectively)

**2. Salesperson Performance (Bar Chart)**
- Tracks both lead count and total deal value per salesperson
- Raj handled the highest leads (138), Neha generated highest revenue (₹52,82,321)

**3. Region Wise Performance (Horizontal Bar Chart)**
- Compares revenue contribution across Pune, Mumbai, Nashik, Nagpur
- Nashik leads with ₹62,28,113 in total deal value

**4. Status Breakdown (Donut Chart)**
- Shows split of 500 leads across: Converted (24%), Won (23%), New (18%), Qualified (18%), Lost (17%)

**5. Monthly Trend (Line Chart)**
- Tracks month-on-month deal value and lead count across Jan–Apr 2026
- Month 3 (March) shows peak revenue of ₹75,34,971

### Interactive Slicers
- Filter entire dashboard by: **Salesperson**, **Region**, **Status**
- All charts and KPIs update dynamically on slicer selection

---

## Key Insights

- **24% conversion rate** — 1 in 4 leads converts to a deal
- **Raj** handles the most leads but **Neha** generates more revenue per lead — indicating higher deal quality
- **Nashik** contributes the highest regional revenue despite not being the largest city
- **Website** is the most consistent lead source across all months
- **March** was the strongest month — ₹75L+ in deal value with 173 leads

---

## File Structure

```
Lead-Management-MIS/
│
├── Lead_Management_MIS_Dataset.xlsx   # Main workbook with all sheets and dashboard
├── dashboard.png                       # Screenshot of final dashboard (add this)
└── README.md                           # This file
```

### Sheets inside the workbook:
- **Main Table** — Raw data (500 rows)
- **KPI** — KPI calculation pivot
- **Lead Source Analysis** — Pivot + chart
- **Salesperson Performance** — Pivot + chart
- **Region-wise Performance** — Pivot + chart
- **Status Breakdown** — Pivot + chart
- **Monthly Trend** — Pivot + chart
- **Dashboard** — Final consolidated view

---

## How to Use

1. Download `Lead_Management_MIS_Dataset.xlsx`
2. Open in Microsoft Excel (2016 or later)
3. Go to the **Dashboard** tab
4. Use slicers on the right to filter by Region, Salesperson, or Status
5. All KPIs and charts update automatically

---

## Skills Demonstrated

- MIS Dashboard Design in Excel
- Pivot Table creation and management
- GETPIVOTDATA formula for dynamic KPI cards
- Slicer-based interactive filtering
- Chart formatting and design
- Sales domain reporting — lead funnel, conversion tracking, revenue analysis
