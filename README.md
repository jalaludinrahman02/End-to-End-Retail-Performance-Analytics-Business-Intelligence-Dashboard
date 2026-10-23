# 📊 ElektroMax - Executive Sales & Customer Analytics Dashboard 2024

![Power BI](https://img.shields.io/badge/Power_BI-F2C94C?style=for-the-badge&logo=powerbi&logoColor=black)
![Data Analytics](https://img.shields.io/badge/Data_Analytics-Business_Intelligence-00b4d8?style=for-the-badge)
![Domain](https://img.shields.io/badge/Domain-Retail_Electronics-116530?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

---

## 📌 Executive Summary

**ElektroMax** adalah dashboard *Business Intelligence* komprehensif yang dirancang untuk memantau performa penjualan ritel elektronik interaktif pada periode tahun 2024. Dashboard ini menyajikan gambaran eksekutif (*Executive Overview*), performa ritel per cabang dan kategori produk (*Product & Toko Analytics*), serta pemetaan perilaku transaksi dan demografi pelanggan (*Customer Analytics*).

Dashboard ini membantu jajaran manajemen dan *stakeholder* ritel dalam mengevaluasi pencapaian omzet, rasio profitabilitas (*Gross Profit Margin*), pertumbuhan dibanding tahun sebelumnya (*Year-over-Year Growth*), efektivitas promosi, serta penentuan strategi pemasaran berbasis segmen pelanggan.

---

## 🎯 Key Performance Indicators (KPIs) Overview (FY 2024)

* **Total Omzet:** **Rp 98,27 Miliar** *(▲ +1,25% YoY vs LY Rp 97,06 Miliar)*
* **Gross Profit:** **Rp 30 Miliar** *(▲ +1,71% YoY vs LY Rp 29,91 Miliar)*
* **Gross Profit Margin (GPM):** **30,96%** *(▲ +0,31% YoY)*
* **Total Transaksi:** **18.960 Transaksi** *(▲ +0,06% YoY)*
* **Jumlah Pelanggan Aktif:** **521 Pelanggan**
* **Rata-Rata Frekuensi Belanja:** **36,39x / Pelanggan**
* **Average Ticket Size (AOV):** **Rp 5,18 Juta / Transaksi**
* **Rasio Retur Transaksi:** **0,10%** *(▼ -3,57% YoY)*

---

## 🧠 Key Insights & Business Highlights

### 1. Performa Penjualan & Tren Musiman (Executive Overview)
* **Puncak Penjualan:** Terjadi lonjakan omzet dan volume transaksi pada akhir tahun (Bulan 12), mencatatkan omzet hingga **Rp 12,1M** dengan **2.320 transaksi** akibat dorongan *Harbolnas 12.12* dan *Year-End Campaign*.
* **Penjualan Terstabil:** Kuartal III hingga Kuartal IV menunjukkan pertumbuhan yang stabil dibandingkan periode tahun lalu (*Last Year*).

### 2. Produk & Cabang Toko (Product & Toko Analytics)
* **Kategori Kontributor Terbesar:**
  1. **Televisi:** Rp 31,64 Miliar
  2. **AC:** Rp 23,70 Miliar
  3. **Kulkas:** Rp 16,02 Miliar
  4. **Mesin Cuci:** Rp 14,09 Miliar
* **Subkategori Profit Margin Tinggi:** *Small Appliance* (GPM **33,87%**) dan *Water Heater* (GPM **33,82%**).
* **Toko Berkinerja Terbaik (Top Stores):**
  * **ElektroMax Sun Plaza:** Omzet Rp 10,42 Miliar *(Achievement Rate: 333,84%)*
  * **ElektroMax Palembang Indah:** Omzet Rp 10,16 Miliar *(Achievement Rate: 470,29%)*
  * **ElektroMax Mall of Indonesia (MOI):** Omzet Rp 10,15 Miliar *(Achievement Rate: 241,56%)*

### 3. Segmentasi Pelanggan & Perilaku Belanja (Customer Analytics)
* **Kontribusi Segmen Pelanggan:**
  * **Regular:** Menyumbang omzet terbesar yaitu **Rp 50,50M** (51M) dari 9.801 transaksi.
  * **Platinum:** Menyumbang **Rp 17,28M** dari 3.330 transaksi.
  * **Gold:** Menyumbang **Rp 15,97M** dari 3.034 transaksi.
  * **Silver:** Menyumbang **Rp 14,52M** dari 2.795 transaksi.
* **Metode Pembayaran Terfavorit:** *QRIS* (4,9rb transaksi) dan *Transfer Bank* (4,7rb transaksi) menjadi pilihan utama transaksi nontunai, diikuti *Tunai* (3,8rb) dan *Kartu Kredit* (3,7rb).
* **Demografi Pelanggan:** Usia **36–45 tahun** mencatatkan kontribusi omzet tertinggi (**Rp 40M**), disusul kelompok usia **25–35 tahun** (**Rp 33M**).
* **Efektivitas Promosi Top 2:**
  1. *Flash Sale Weekend:* Menyumbang omzet **Rp 15,19 M Miliar** (3.587 transaksi).
  2. *Bundling AC + Instalasi:* Menyumbang omzet **Rp 13,69 M Miliar** (2.533 transaksi).

---

## 🖥️ Dashboard Layout & Architecture

Dashboard ini terbagi menjadi 3 tab interaktif utama:

```text
Dashboard Structure
│
├── 📑 1. Executive Overview
│   ├── KPI Cards (Omzet, Profit, GPM %, Total Transaksi, YoY Growth)
│   ├── Line Chart: Tren Omzet vs Last Year (Bulanan)
│   ├── Line Chart: Tren Transaksi vs Last Year (Bulanan)
│   ├── Bar Chart: Total Omzet by Subkategori Produk
│   └── Table: Detail Achievement % Per Toko
│
├── 🏬 2. Toko & Produk Analytics
│   ├── Donut Chart: Total Omzet by Region (Region 1-4)
│   ├── Bar Chart: Gross Profit Margin % by Subkategori
│   ├── Horizontal Bar Chart: Breakdown Omzet Toko Top 10
│   └── Data Matrix: Detail Kinerja Toko & Produk (GPM%, YoY Growth, AOV)
│
└── 👤 3. Pelanggan & Campaign Analytics
    ├── KPI Metrics: Customer Count, Retur %, Avg Frequency, Promo Trans %
    ├── Bar Chart: Segment Omzet Breakdown (Regular, Platinum, Gold, Silver)
    ├── Bar Chart: Metode Pembayaran & Status Transaksi (Selesai, Retur, Pending)
    ├── Bar Chart: Distribusi Omzet Kelompok Umur Pelanggan
    └── Data Table: Evaluasi Performa Kampanye Promosi
