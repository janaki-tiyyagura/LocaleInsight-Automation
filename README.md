
---

# LocaleInsight Automation

**LocaleInsight Automation** is an end-to-end data automation solution that generates **geo-wise user counts from the Braze platform** in minutes. It replaces a slow, manual process with a **scalable, cloud-based ETL pipeline** built on Azure, delivering fast, accurate, and reliable campaign analytics.

---

## 🚀 Overview

Marketing teams previously spent **45–60 minutes per campaign** manually extracting country-wise user counts from Braze. This process was repetitive, error-prone, and difficult to scale as campaigns and geographies increased.

LocaleInsight Automation solves this by **automating data extraction, processing, and reporting**, delivering accurate geo-level user counts in **~5 minutes per campaign**.

---

## 🧩 Problem Statement

* Manual extraction of geo-wise user counts from Braze
* High risk of human error and inconsistent results
* Slow turnaround impacting campaign planning and decisions
* Not scalable with increasing campaigns and regions

---

## ✅ Solution

LocaleInsight Automation:

* Fetches campaign user data from **Braze using REST APIs**
* Orchestrates workflows using **Azure Data Factory**
* Stores raw data in **Azure Storage**
* Processes and aggregates data using **PySpark**
* Automatically calculates **country-wise user counts**
* Delivers fast, consistent, and error-free outputs to marketing teams

---

## 📊 Impact

* ⏱️ **Time reduced from 45–60 minutes to ~5 minutes per campaign**
* ❌ Eliminated manual counting errors
* 📈 Improved accuracy and consistency of campaign analytics
* 🌍 Scales easily across multiple geographies and campaigns
* 🎯 Enables faster, data-driven campaign planning and decisions

---

## 🛠️ Tech Stack

* **Azure Data Factory** – Workflow orchestration
* **REST APIs** – Data extraction from Braze
* **Azure Storage** – Intermediate data storage
* **PySpark (Notebooks)** – Data processing and aggregation
* **Python** – Automation logic

---

## 🔄 High-Level Workflow

1. Trigger pipeline in Azure Data Factory
2. Fetch campaign user data from Braze via REST API
3. Store raw data in Azure Storage
4. Process data using PySpark notebooks
5. Generate country-wise user counts
6. Share results with marketing teams

---

## 🎯 Use Cases

* Campaign planning and email distribution
* Geo-level audience analysis
* Marketing operations analytics
* Scalable reporting for multi-region campaigns

---

