# Analysis of DoD Spend on Ground Combat Systems (GCS)

> **Portfolio demo – notebook + written report included**

## Overview
This project dissects U.S. Department of Defense contract spending across three flagship Ground Combat Systems programs—**Abrams**, **Bradley**, and **Stryker**.  
By mining a 54 k‑row synthetic contract dataset, it surfaces lifecycle trends, dominant vendors, spend concentrations by contracting office, and potential risk hot‑spots.

## Data
| Source | Rows | Description |
|--------|------|-------------|
| Synthetic GCS contracts | 54 390 | Synthetic FY2016‑2020 DoD spend patterns |

## Methods & Libraries
- `pandas` for cleaning, grouping, time‑series pivots  
- `matplotlib` / `seaborn` for trend & vendor bar‑charts  
- Vendor‑name normalisation with `fuzzywuzzy` (string similarity)  
- Simple regex (`re`) utilities for PSC tagging

*(Visuals in notebook; see the DOCX for executive narrative.)*
