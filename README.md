# Capstone-Project-2
# NYC TLC Revenue Loss Analysis Project

## Overview
Analisis komprehensif terhadap potensi kehilangan pendapatan NYC Taxi & Limousine Commission (TLC) dan rekomendasi solusi perbaikan sistem.

## Problem Statement
NYC TLC menghadapi masalah signifikan terkait missing charges dalam transaksi taksi, meliputi:
- Improvement surcharge ($0.30)
- MTA tax ($0.50)
- Congestion surcharge ($2.50)

#### 1. Improvement Surcharge
- Regulasi: NYC TLC Rules §58-26(a)(10)
- Nominal: $0.30 per trip
- Ketentuan: Wajib dikenakan pada SETIAP perjalanan taksi
- Sumber: [NYC TLC Rules Chapter 58](https://www.nyc.gov/assets/tlc/downloads/pdf/rule_book_current_chapter_58.pdf)

#### 2. MTA Tax
- Regulasi: NYC Tax Law §1281(a)
- Nominal: $0.50 per trip
- Ketentuan: Wajib dikenakan pada SETIAP perjalanan taksi di wilayah NYC
- Sumber: [NY State MTA Tax Memo](https://www.tax.ny.gov/pdf/memos/mta_mobility/m19-1mta.pdf)

#### 3. Congestion Surcharge
- Regulasi: NYC TLC Rules
- Nominal: $2.50 per trip
- Ketentuan: Wajib dikenakan untuk SETIAP pickup di Manhattan dibawah 96th Street
- Sumber: [NYC TLC Congestion Surcharge FAQ](https://www.nyc.gov/assets/tlc/downloads/pdf/congestion_surcharge_faq.pdf)

## Key Findings
1. Revenue Loss
   - Current Annual Loss: $1,366,324.52
   - Breakdown per charge type:
     * Improvement Surcharge: $527,242.50
     * MTA Tax: $140,916.49
     * Congestion Surcharge: $698,165.52

2. Pattern Analysis
   - Missing charges tertinggi pada jam sibuk (6-8 AM)
   - Variasi signifikan antar vendor
   - Konsentrasi masalah di area Manhattan

## Implementation Plan
1. **Short-term (6 bulan)**
   - Investment: $525,000
   - Expected Recovery: 30-40%
   - Focus: System stabilization

2. **Medium-term (12 bulan)**
   - Investment: $1,750,000
   - Expected Recovery: 50-70%
   - Focus: Process optimization

3. **Long-term (24+ bulan)**
   - Investment: $5,000,000
   - Expected Recovery: 80-90%
   - Focus: System transformation

## Technologies Used
- Python 3.8+
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
