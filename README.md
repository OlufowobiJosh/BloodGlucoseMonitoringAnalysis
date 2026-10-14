> **Confidentiality notice:** This portfolio is a reconstruction using synthetic records only. All uploaded figures, totals, dates, categories and trends have been changed to protect patient and organisational confidentiality; they do not represent actual workplace or patient data.

# Blood Glucose Monitoring | Excel Healthcare Analytics

**Excel-only descriptive analytics portfolio demonstration** inspired by a real workplace improvement project. I extracted and organised monitoring records in the organisation's approved clinical system, prepared structured data in Microsoft Excel, developed glucose classification formulas, built KPI cards and interactive charts, and presented the analysis to management.

> **Confidentiality:** The public workbook and CSV use independently simulated records. All counts, dates, categories, figures and trends were changed to protect patient and organisational confidentiality. These are **not** actual clinical or organisational results. No original patient records or hospital-branded dashboard screenshots are included.

## Dashboard

Open [`Blood_Glucose_Monitoring_Dashboard.xlsx`](Blood_Glucose_Monitoring_Dashboard.xlsx) in desktop Excel. The **Dashboard** tab contains four KPI cards, a monthly average glucose trend, a glycaemia distribution chart, time-of-day monitoring comparison and a monitoring-context chart. Change the year in **AB10** to filter all KPI and chart calculations together. Charts are native, editable Excel charts; the filter is a compatible dropdown, **not a native PivotTable slicer**.

## Business question

How can existing monitoring records be organised to reveal glucose-level patterns, monitoring timing and possible gaps in recording, helping staff review monitoring practice?

## Method

1. Organise monitoring dates, results and contextual notes into consistent columns.
2. Classify recorded glucose readings with project-specific example thresholds: **below 4 mmol/L** (hypoglycaemia), **4–15 mmol/L inclusive** (normal for this demonstration), **above 15 mmol/L** (hyperglycaemia). These are **not universal clinical reference ranges**.
3. Group monitoring context into Morning, Midday and Evening; keep declined checks separate from measured glucose results.
4. Calculate counts and averages and create interactive Excel reporting views.
5. Communicate descriptive findings to stakeholders without claiming causal or clinical conclusions.

## Workbook sheets

- `Dashboard` — visual reporting, editable charts and year selector.
- `Synthetic_Data` — fictional records and prepared analysis columns.
- `Chart_Data` — formula driven calculations for KPI cards and charts.
- `Instructions` — workbook notes and confidentiality guidance.

## Limitations

All public insights describe synthetic data only; they are not patient level findings, clinical advice, or verified workplace outcomes. This recreation is inspired by the structure and analytical approach of the original Excel work but does not publish the original workbook.


### Dashboard interactivity
Use the **Year** dropdown in cell `AB10` and **Time of Day** dropdown in `AB14` to filter the KPI cards and four Excel charts together. The workbook uses editable Excel formulas and native charts, not a pasted dashboard image.
