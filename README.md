# Trade Settlement Reconciliation Engine

## Overview
An Excel-based Middle/Back Office financial engine built to automate trade matching, identify reconciliation breaks, and measure Straight-Through Processing (STP) rates.

## Key Features
* **Automated Trade Matching:** Uses `SUMIF` / `SUMPRODUCT` logic to pull custodian figures dynamically.
* **Break & Exception Detection:** Automatically flags `AMOUNT_MISMATCH` and `FAILED_SETTLEMENT` statuses.
* **KPI Dashboard:** Visualizes overall settlement distribution and computes the real-time **STP Rate %**.

## Tech Stack & Domain Knowledge
* **Tool:** Microsoft Excel (Web / Desktop)
* **Functions:** `SUMIF`, `COUNTIF`, `COUNTA`, `IF`, Conditional Formatting
* **Domain:** Middle & Back Office Operations, Trade Reconciliation, STP Analysis
