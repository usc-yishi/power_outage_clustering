# 🌞 Solar Photovoltaic User Detection & Power Outage Analysis

## 📑 Overview

The integration of renewable energy sources into modern power grids has brought about new challenges, especially in distinguishing solar photovoltaic (PV) users from non-PV users in large-scale datasets. Traditional methods often rely heavily on expensive satellite imagery or detailed on-site information from solar panels. However, these solutions are not feasible when scaling to datasets encompassing tens of thousands of users.

Additionally, real-world smart meter data presents various challenges, such as **data transmission errors**, **abnormal electricity behaviors** (e.g., electricity theft or leakage), and the **detection of power outages**. These factors complicate the accurate analysis of energy usage patterns.

### 🛠 Project Goals

This project aims to address these challenges by leveraging **large-scale real-world smart meter data** to:

- **Classify** users with solar PV systems versus non-solar users.
- **Detect power outage events** without relying on costly external data sources.
- Utilize a high-resolution dataset covering **160,000 consumers in Southern California**, recorded at **1-hour intervals**.

---

## 🚀 Features

- 🌐 **Scalable PV User Detection**: Differentiates between solar and non-solar households without satellite data.
- ⚡ **Outage Detection**: Identifies power outages amidst noise and anomalies in smart meter readings.
- 📊 **Real-World Data Application**: Applies advanced analytics on an extensive dataset with over **400 million records**, ensuring robustness and scalability.

---

## 📂 Repository Structure

```plaintext
├── data/                 # Data processing scripts & raw data samples
├── src/                  # Core algorithms & models
├── notebooks/            # Jupyter Notebooks for exploratory analysis
├── docs/                 # Project documentation
├── results/              # Visualizations & analysis results
└── README.md             # Project overview & usage instructions
