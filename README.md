# 🚦 Road Accident Dashboard

An Excel-based data analysis and visualization dashboard tracking **307,973 road accident casualties** across the UK for the years **2021 and 2022**. The dashboard provides actionable insights on casualty severity, vehicle types, road types, surface conditions, location, and light conditions.

---

## 📁 File

```
Road_Safety.xlsx
```

---

## 🗂️ Workbook Structure

| Sheet | Purpose |
|-------|---------|
| `Data` | Raw dataset — 307,973 accident records with 23 fields each |
| `Data Analysis` | Pivot tables aggregating data for all dashboard charts |
| `Dashboard` | Interactive visual dashboard with charts, KPIs, and filter panel |
| `Sheet2–Sheet7` | Supporting calculation/pivot sheets |

---

## 📊 Dashboard KPIs

| Metric | Value | Share |
|--------|-------|-------|
| ⚠️ Fatal Casualties | 3,953 | 1.3% |
| 🟡 Serious Casualties | 40,740 | 13.2% |
| 🟢 Slight Casualties | 263,280 | 85.5% |
| **Total Casualties** | **307,973** | 100% |

---

## 📈 Dashboard Sections

### 1. Casualties by Vehicle Type
| Vehicle | Casualties |
|---------|-----------|
| 🚗 Cars | 245,337 |
| 🏍️ Bikes | 25,066 |
| 🚛 Vans | 24,729 |
| 🚌 Buses | 9,507 |
| 🚫 Others | 3,334 |

### 2. Monthly Trend (2021 vs 2022)
- **2021 Total:** 163,554 casualties
- **2022 Total:** 144,419 casualties
- Accidents peak around **October–November** and dip in **January–February**
- 2022 shows a consistent reduction in casualties compared to 2021

### 3. Casualties by Road Type
| Road Type | Casualties |
|-----------|-----------|
| Single carriageway | 230,612 |
| Dual carriageway | 45,467 |
| Roundabout | 20,929 |
| One way street | 6,197 |
| Slip road | 3,234 |
| Two way street | 1,534 |

### 4. Casualties by Road Surface
| Surface | Casualties |
|---------|-----------|
| Dry | 208,967 |
| Wet / Damp | 81,853 |
| Ice | 16,836 |
| Fog | 317 |

### 5. Casualties by Location
| Area | Casualties |
|------|-----------|
| Urban | 198,532 |
| Rural | 109,441 |

### 6. Casualties by Light Condition
| Condition | Casualties |
|-----------|-----------|
| Daylight | 227,286 |
| Darkness | 80,687 |

---

## 🗃️ Raw Data — Column Reference

The `Data` sheet contains **307,973 rows** and **23 columns**:

| Column | Description |
|--------|-------------|
| `Accident_Index` | Unique accident identifier |
| `Accident Date` | Date of the accident |
| `Month` | Month extracted from date (formula) |
| `Year` | Year extracted from date (formula) |
| `Day_of_Week` | Day name (e.g., Monday) |
| `Junction_Control` | Control type at junction |
| `Junction_Detail` | Type of junction |
| `Accident_Severity` | Fatal / Serious / Slight |
| `Latitude` / `Longitude` | GPS coordinates |
| `Light_Conditions` | Daylight or Darkness |
| `Local_Authority_(District)` | District name |
| `Carriageway_Hazards` | Hazards present on road |
| `Number_of_Casualties` | Count of casualties per accident |
| `Number_of_Vehicles` | Vehicles involved |
| `Police_Force` | Responding police force |
| `Road_Surface_Conditions` | Dry / Wet / Ice / Fog |
| `Road_Type` | Type of road |
| `Speed_limit` | Speed limit at location |
| `Time` | Time of accident |
| `Urban_or_Rural_Area` | Urban or Rural |
| `Weather_Conditions` | Weather at time of accident |
| `Vehicle_Type` | Car / Bus / Van / Bike / Others |

---

## 🔍 Filter Panel

The dashboard includes an interactive **Filter Panel** with:
- **Accident Date** slicer — filter by month/year range (All Periods or custom)
- **Urban or Rural** slicer — toggle between Rural and Urban views

All charts update dynamically when filters are applied.

---

## ✨ Features

- 📌 **Interactive slicers** for date range and urban/rural filtering
- 📉 **Year-on-year monthly trend line** (2021 vs 2022)
- 🥧 **Donut charts** for location and light condition breakdowns
- 📊 **Bar charts** for road type analysis
- 🏷️ **KPI cards** with donut gauges for casualty severity percentages
- 🌑 **Dark-themed** professional dashboard design

---

## 🛠️ Tools Used

- **Microsoft Excel** — Pivot Tables, Slicers, Line Charts, Donut Charts, Bar Charts, TEXT Formulas

---

## 🔑 Key Insights

- **85.5%** of all casualties are slight, but fatal and serious combined still account for over **44,000** casualties.
- **Cars** are involved in nearly **80%** of all casualties by vehicle type.
- **Single carriageways** are the most dangerous road type — nearly **75%** of all casualties occur there.
- **Urban areas** see nearly double the casualties of rural areas (198K vs 109K).
- **Dry roads** account for the majority of casualties, reflecting higher traffic volume on clear days.
- **2022 recorded ~12% fewer casualties** than 2021 (144K vs 163K), suggesting improved road safety outcomes.

---

## 📄 License

This dataset and dashboard are intended for road safety research and analysis purposes.
