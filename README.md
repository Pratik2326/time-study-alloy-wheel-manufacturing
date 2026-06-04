# 🔩 Application of Time Study Technique
## A Case Study of Alloy Wheel Industry

<p align="center">
  <img src="https://img.shields.io/badge/Published-March%202018-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Journal-IJRISE-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Domain-Industrial%20Engineering-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Methods-Time%20Study%20%7C%20Data%20Analysis-red?style=for-the-badge" />
</p>

---

## 📄 Publication Details

| Field | Details |
|-------|---------|
| **Journal** | International Journal of Research In Science & Engineering (IJRISE) |
| **Volume** | Special Issue, Volume 4, Issue 2 |
| **Published** | March 2018 |
| **ISSN (e)** | 2394-8299 |
| **ISSN (p)** | 2394-8280 |
| **Pages** | 237–240 |
| **Authors** | **Pratik More**, Mahesh Naidu, Lopesh Bhoir, Mayuresh Chavan |

---

## 🎯 What This Research Is About

Manufacturing companies lose thousands of hours every year to inefficiencies that nobody has measured.

This paper asks a simple question: **how long does it actually take to make an alloy wheel — and where is the time being wasted?**

Using **Time Study techniques** from Industrial Engineering, we walked into a real alloy wheel manufacturing facility, timed every single operation across 20 machining processes, and built a data model to find the bottlenecks.

The answer: **two operations were consuming disproportionate time** — and both had fixable solutions.

---

## 🔍 The Problem

An alloy wheel goes through 20 distinct manufacturing operations from raw casting to final packaging:

```
Foundry → Machining → Quality → Finishing → Packaging
```

Total baseline time: **388 minutes per wheel**

The challenge was identifying which operations were dragging down productivity — and finding data-driven solutions to fix them.

---

## 📊 Methodology

We applied the **Time Study framework** from Industrial Engineering:

1. **Data Collection** — Timed each operation for 20 cycles using structured time study sheets
2. **Rating** — Applied operator skill ratings to normalize observed times
3. **Standard Time Calculation** — Normal Time × Rating Factor + 15% allowances
4. **Analysis** — Built a standard time model across all 20 operations
5. **Bottleneck Identification** — Ranked operations by time consumption
6. **Recommendations** — Proposed process changes with quantified impact

---

## 📈 Key Findings

| Operation | Avg Basic Time (mins) | Standard Time (mins) |
|-----------|----------------------|---------------------|
| Heat Treatment | 240.0 | 278.0 |
| Ageing | 61.0 | 70.15 |
| **Hole Drilling** | **5.6** | **6.44** |
| Casting | 7.8 | 8.96 |
| **Rough Boring** | **2.33** | **2.67** |
| Air Leak Test | 1.77 | 2.04 |
| **Total** | | **388 mins** |

> Heat Treatment and Ageing dominate total time but cannot be reduced without compromising quality. The actionable bottlenecks are **Hole Drilling** and **Rough Boring**.

---

## 💡 Recommendations

### 1. Gang Drilling for Hole Drilling Operations
**Problem:** Single spindle drilling requires multiple passes for each hole.

**Solution:** Replace with multi-spindle gang drilling head.

**Impact:** ⬇️ **40–50% reduction** in hole drilling time

### 2. Combine Degating + Rough Boring on CNC
**Problem:** Degating uses CNC; Rough Boring uses a separate semi-automatic lathe — requiring material handling between machines.

**Solution:** Consolidate both operations on the CNC machine.

**Impact:** ⬇️ Reduced machining time + eliminated inter-machine travel + reduced labour effort

---

## 🔗 The Bigger Picture

This was my first published research — and it planted something that has driven my work ever since.

The core of what we did here is identical to what I do today as a Data Analyst:

| Then (2018) | Now (2024–2026) |
|-------------|-----------------|
| Collected time study data across 20 operations | Collected energy and utility data across 8 campus buildings |
| Built standard time models to find inefficiencies | Built Power BI dashboards to surface KPI anomalies |
| Identified bottlenecks nobody had measured | Identified HVAC faults nobody had caught |
| Delivered recommendations to reduce waste | Delivered cost-ranked reports that shaped investment decisions |

**Different domain. Same mindset.**

---

## 📁 Files

| File | Description |
|------|-------------|
| [`Time_Study_Alloy_Wheel_IJRISE_2018.pdf`](./Research_20paper.pdf) | Full published paper |

---

## 👤 Author

**Pratik More**
MS Business Analytics, University of Colorado Denver (May 2026)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin)](https://linkedin.com/in/pratikm0105)
[![GitHub](https://img.shields.io/badge/GitHub-Portfolio-black?style=flat&logo=github)](https://github.com/Pratik2326)
[![Dashboards](https://img.shields.io/badge/Live%20Dashboards-CU%20Denver-green?style=flat)](https://www.ucdenver.edu/offices/facilities-management-and-planning/sustainability/dashboards)
[![HR Analytics](https://img.shields.io/badge/HR%20Dashboard-Tableau%20Public-orange?style=flat)](https://public.tableau.com/app/profile/pratik.rajaram.more/viz/HRDashboard1_17755059903640/HRDashboard)

---

<p align="center">
  <i>From timing operations on a manufacturing floor in 2018 to building live analytics dashboards in 2026 — the question has always been the same: where is the time being lost, and what does the data say?</i>
</p>
