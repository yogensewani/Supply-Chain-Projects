# 📊 Supply Chain Analytics Portfolio

Welcome to my professional portfolio of advanced Excel models. This repository bridges theoretical supply chain management frameworks with data-driven operational execution. Each model is engineered using rigorous analytical logic to address common enterprise friction points across forecasting, inventory management, network logistics, and strategic sourcing.

---

## 🗺️ Portfolio Directory

*   [🤝 Vendor Evaluation Model](#-vendor-evaluation-model)
*   [📈 Demand Forecast Model](#-demand-forecast-model)
*   [📦 Inventory Model](#-inventory-model)
*   [🚛 Distribution Cost Model](#-distribution-cost-model)
*   [🛠️ Technical Toolbelt](#%EF%B8%8F-technical-toolbelt)

---

## 🤝 Vendor Evaluation Model

### 🥇 Multi-Criteria Vendor Normalization & Ranking Engine
*   **The Problem:** Standardizing procurement selection processes across multiple suppliers when competing KPIs (e.g., lead times vs. pricing vs. quality scores) mask the optimal choice.
*   **Supply Chain Framework:** **Weighted Scoring Profile Matrix** using **Simple Linear Scaling Normalization** to compress disparate metrics into standardized numerical scales.
*   **Excel Mechanics:** 
    *   Advanced architectural segmentation separating raw **Vendor Data** inputs from functional parameter weighting sheets.
    *   Directional score transformation logic (ensuring cost and defect values scale downwards while quality and on-time percentages scale upwards).
    *   Automated decision engines providing instant ordinal positions (`RANK`) and conditional strategic outcomes (e.g., *“Acceptable”*).
*   **Visual Documentation:** Driven by a centralized procurement **Dashboard** interface giving supply chain buyers immediate visibility into supplier performance tiers.

#### Repository Location:
📁 [`./Vendor Evaluation Model.xlsx/`](./Vendor%20Evaluation%20Model.xlsx/)
*   📥 **[Download Model File](./Vendor%20Evaluation%20Model.xlsx/Vendor%20Evaluation%20Model.xlsx)**
*   🖼️ **[View Dashboard Preview](./Vendor%20Evaluation%20Model.xlsx/dashboard_preview.png)**

---

## 📈 Demand Forecast Model

### 🛒 Statistical Baseline & Seasonal Forecasting
*   **The Problem:** Mitigating the Bullwhip Effect by resolving baseline forecasting errors, unpredictable SKU variations, and hidden demand seasonality.
*   **Supply Chain Framework:** **Holt-Winters Exponential Smoothing** (adjusting for local level, trend, and seasonality variations) alongside a calculated **Seasonality Index** mapped across multi-year historical tracking periods.
*   **Excel Mechanics:** 
    *   Leverages advanced time-series predictive modeling using `FORECAST.ETS` engines.
    *   Calculated moving averages and standard error upper/lower bounds (`FORECAST.ETS.CONFINT`) to establish risk-adjusted confidence limits.
    *   Separate **Historical Data** processing arrays feeding into an executive-facing **Forecast Sheet**.
*   **Visual Documentation:** Features dynamic timelines mapping historical actuals directly against multi-period forward projections.

#### Repository Location:
📁 [`./Demand Forecast Model.xlsx/`](./Demand%20Forecast%20Model.xlsx/)
*   📥 **[Download Model File](./Demand%20Forecast%20Model.xlsx/Demand%20Forecast%20Model.xlsx)**
*   🖼️ **[View Dashboard Preview](./Demand%20Forecast%20Model.xlsx/dashboard_preview.png)**

---

## 📦 Inventory Model

### 💾 Multi-Item Stochastic Safety Stock & EOQ Simulator
*   **The Problem:** Balancing the financial trade-offs between carrying capital blockages (overstocking) and high-consequence service penalties or production halts (stockouts).
*   **Supply Chain Framework:** **Economic Order Quantity (EOQ)** paired with stochastic **Safety Stock** formulas under variable daily demand profiles using **Cycle Service Level ($Z$-scores)** parameters.
*   **Excel Mechanics:** 
    *   Dynamic continuous calculation equations evaluating `Annual Demand (D)`, `Order Cost (S)`, and `Holding Cost (H)`.
    *   Automated Reorder Point (ROP) indicators parsing daily standard deviations of demand (`Std Dev Demand`) against supplier `Lead Time (L days)`.
    *   `IF` and nested evaluation logical strings tracking current warehouse metrics to output instantaneous operational statuses (e.g., *“OK”* vs *“Reorder”*).
*   **Visual Documentation:** Backed by an underlying **Simulated Demand** daily modeling table to stress-test stock depletion behaviors over time.

#### Repository Location:
📁 [`./Inventory Model.xlsx/`](./Inventory%20Model.xlsx/)
*   📥 **[Download Model File](./Inventory%20Model.xlsx/Inventory%20Model.xlsx)**
*   🖼️ **[View Dashboard Preview](./Inventory%20Model.xlsx/dashboard_preview.png)**

---

## 🚛 Distribution Cost Model

### 🛣️ Network Freight Allocation & Route Optimization
*   **The Problem:** Minimizing multi-tiered freight expense allocations when routing products across diverse distribution nodes and retail touchpoints without breaching warehouse capacities.
*   **Supply Chain Framework:** **Network Optimization and Cost Matrix Formulations** (Linear Programming applications engineered to find the absolute minimum total expenditure across geographical networks).
*   **Excel Mechanics:** 
    *   Structured matrices using `SUMPRODUCT` arrays to instantly compute variable shipping tariffs based on routing combinations.
    *   Engineered with **Excel Solver Add-in** constraints (Simplex LP optimizer engines) to automate lowest-cost distribution routes.
    *   Dedicated **Model and Analysis** core tabs feeding separate, clean executive analytical report view layers.
*   **Visual Documentation:** Utilizes an integrated **Charts Dashboard** showing aggregated route expenditures categorized by active Distribution Centers.

#### Repository Location:
📁 [`./Distribution Cost Model.xlsx/`](./Distribution%20Cost%20Model.xlsx/)
*   📥 **[Download Model File](./Distribution%20Cost%20Model.xlsx/Distribution%20Cost%20Model.xlsx)**
*   🖼️ **[View Dashboard Preview](./Distribution%20Cost%20Model.xlsx/dashboard_preview.png)**

---

## 🛠️ Technical Toolbelt

The models hosted across this repository demonstrate a deep command of enterprise spreadsheet design:
*   **Mathematical Modeling:** Continuous probability analysis, Holt-Winters predictive smoothing vectors, optimization algorithms.
*   **Data Structures:** 3-Tier spreadsheet mapping (Inputs $\rightarrow$ Normalized Computations $\rightarrow$ Clean Presentation Layers).
*   **Excel Engine Mastery:** Solver Add-in configuration, multi-criteria lookup arrays, directional normalization scaling formulas, error-handling logics.
*   **Professional UX Styling:** Complete removal of core workspace gridlines on presentation tabs, standardized numeric precision, and strict executive reporting layouts.

---

## 📂 How to Open and Review

1.  Navigate into any model directory listed above to access the project assets.
2.  Review the `.png` screenshot if you want to inspect the dashboard architecture natively on GitHub.
3.  Click the respective download link to obtain the working spreadsheet. 
4.  *Note for Evaluators: Please verify that the **Excel Solver Add-in** is enabled via your application's settings menu (`File > Options > Add-ins`) to execute optimization vectors inside the logistics and inventory spreadsheets.*
