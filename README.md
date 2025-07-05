# Dynamic-parking-pricing
# 🚗 Dynamic Pricing for Urban Parking Lots

> Capstone Project | Summer Analytics 2025  
> Hosted by: Consulting & Analytics Club × Pathway  

---

## 📋 Overview

Urban parking spaces face fluctuating demand throughout the day, leading to issues of overcrowding or underutilization if static pricing is applied.  
This project develops an **intelligent dynamic pricing system** for 14 urban parking lots using **real-time data streams**, leveraging machine learning models and economic theory to set optimal parking prices.

The system updates prices based on:
- Occupancy rates
- Queue lengths
- Nearby traffic conditions
- Special events or holidays
- Type of incoming vehicles
- Competitor parking prices (optional in advanced models)

The solution ensures **smooth, explainable price variations** and offers optional vehicle rerouting recommendations.

---

## 🛠️ Tech Stack Used

| Tool/Library | Purpose |
|--------------|---------|
| **Python**   | Core programming language |
| **Pandas**   | Data handling & manipulation |
| **Numpy**    | Numerical computations |
| **Pathway**  | Real-time data ingestion and processing |
| **Bokeh**    | Real-time visualization of pricing trends |
| **Google Colab** | Development & execution environment |
| **GitHub**   | Version control and submission platform |

---
📝 Architecture Diagram Description:

This architecture shows the workflow of the dynamic pricing system:

Real-time parking data is streamed using Pathway.

Key features (occupancy, queue length, traffic, etc.) are extracted.

Prices are updated using three models:

Model 1: Simple linear pricing based on occupancy.

Model 2: Demand-based pricing using multiple features.

Model 3: Competitive pricing based on nearby parking lots.

Prices are smoothed and visualized in real-time using Bokeh.
