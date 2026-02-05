# Retail Execution & Field Analytics System
### Progetto di Analisi Integrata per il Settore Retail
**Sviluppato da: Fabio De Bartolomeo**


## 📌 Visione del Progetto
Questo repository ospita un sistema avanzato di monitoraggio delle performance retail, progettato per trasformare dati grezzi in insight operativi. Il progetto affronta la complessità del settore attraverso una pipeline che unisce la potenza di calcolo di **Python** per la data preparation e la flessibilità di **Power BI** per la visualizzazione strategica.

In assenza di documentazione tecnica originale, ho ricostruito le logiche di business tramite un'attività di **reverse engineering** e basandomi sulla mia esperienza **hands-on** nel settore.


## 🛠 Moduli Strategici

### 1. Monitoraggio Stock e Audit (Retail Execution)
Analisi focalizzata sulla *shelf health* e sull'efficienza della catena di approvvigionamento.
* **KPI Core:** `OSA%` (On-Shelf Availability) e `OOS%` (Out-of-Stock).
* **Logica di Audit:** Monitoraggio dei **4 momenti chiave** del rilevamento condizione per distinguere tra disponibilità a scaffale, anomalie di magazzino e fuori assortimento.
* **Obiettivo:** Identificazione proattiva dei colli di bottiglia logistici per ridurre il fatturato perso.

### 2. Performance Field Force (Visite Cicliche)
Dashboard dedicata al controllo del presidio territoriale e all'efficienza dei flussi di lavoro.
* **KPI Core:** `TMC%` (Target Medio Copertura), frequenza di visita e durata media del presidio.
* **Ambito:** Monitoraggio di **1.751 punti vendita** con drill-down granulare per regione e insegna.


## 💻 Tech Stack

* **Python:** Utilizzato per la pulizia dei dataset, la normalizzazione delle anagrafiche (es. gestione province) e la risoluzione delle ridondanze nei file JSON/CSV.
* **Power BI:** Data modeling relazionale, calcoli complessi in **DAX** e data visualization semantica (formattazione condizionale basata sulle criticità).


## 🚀 Struttura del Repository
* `/scripts`: Notebook Python per il processo di pulizia e normalizzazione dati.
* `/dashboard`: File `.pbix` con l'analisi interattiva completa.
* `/data`: (Opzionale) Sample dei dati utilizzati o template CSV.

# English version

# Retail Execution & Field Analytics System
### Integrated Analytics Project for the Retail Sector
**Developed by: Fabio De Bartolomeo**


## 📌 Project Overview
This repository hosts an advanced retail performance monitoring system designed to transform raw data into actionable operational insights. The project tackles sector complexity through a pipeline that combines the computational power of **Python** for data preparation and the strategic flexibility of **Power BI** for visualization.

Due to the absence of original technical documentation, I reconstructed the business logic through **reverse engineering**, leveraging my **hands-on experience** in the retail field.


## 🛠 Strategic Modules

### 1. Stock Monitoring & Audit (Retail Execution)
Analysis focused on shelf health and supply chain efficiency.
* **Core KPIs:** `OSA%` (On-Shelf Availability) and `OOS%` (Out-of-Stock).
* **Audit Logic:** Monitoring **4 key detection states** to distinguish between shelf availability, warehouse anomalies, and delisted items.
* **Objective:** Proactive identification of logistical bottlenecks to minimize lost revenue.

### 2. Field Force Performance (Cyclic Visits)
Dashboard dedicated to territorial coverage monitoring and workflow efficiency.
* **Core KPIs:** `TMC%` (Target Mean Coverage), visit frequency, and average visit duration.
* **Scope:** Monitoring **1,751 points of sale** with granular drill-downs by region and retailer.


## 💻 Tech Stack & Methodology

* **Python:** Used for dataset cleaning, master data normalization (e.g., province management), and resolving redundancies in JSON/CSV files.
* **Power BI:** Relational data modeling, complex **DAX** calculations, and semantic data visualization (conditional formatting based on criticality levels).
* **Problem Solving:** Independent reconstruction of the data architecture, ensuring total alignment between extracted KPIs and real-world store dynamics.


## 🚀 Repository Structure
* `/scripts`: Python notebooks for the data cleaning and normalization process.
* `/dashboard`: `.pbix` file containing the full interactive analysis.
* `/data`: (Optional) Data samples or CSV templates used for the project.

---
