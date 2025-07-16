# 🌍 Nigeria Flood Impact Dashboard

A data-driven dashboard visualizing the impact of flooding events across Nigeria from 2012 to 2025, with insights on human casualties, infrastructure damage, rainfall intensity, and socio-economic vulnerability.

## 📌 Project Overview

This project aims to transform raw and fragmented flood data into actionable insights using web scraping, data mining, and interactive visualization techniques.

It consolidates incident data from official and open sources—such as **NEMA**, **NIHSA**, and news archives—into a clean, structured format and visualizes key patterns using **Power BI**.

## 💡 Objectives

- Provide a centralized, interactive view of Nigeria’s flood impact
- Reveal patterns and hotspots over time and geography
- Correlate rainfall levels, socio-economic factors, and human impact
- Support data-driven decision-making for disaster response and planning

## 📂 Data Pipeline

1. **Web Scraping & Data Mining**
   - Scraped from NEMA reports, FloodList Africa, and rainfall APIs
   - Supplemented with HDI, poverty data, and satellite rainfall records

2. **Data Cleaning & Transformation**
   - Tools: `Python`, `Pandas`, `Power Query`, `Excel`
   - Standardized state/LGA names, date formats, and metric units
   - Merged multiple sources into a single dataset

3. **Validation**
   - Cross-referenced with NEMA and NIHSA data
   - Cleaned for accuracy, missing values, and redundancy

4. **Visualization**
   - Built in **Power BI**
   - Features KPIs, geo heatmaps, scatterplots, and socioeconomic overlays

## 📊 Dashboard Features

- 📅 Year-by-year breakdown of flood events
- 🗺️ Geo heatmaps of affected LGAs/states
- 🌧️ Scatterplots of rainfall vs. affected population
- 🧭 Socioeconomic vulnerability vs. death rate (bubble chart)
- 🏠 Houses & farmland damage analysis
- 📌 High-risk zones and disaster flags

## 📁 Folder Structure

