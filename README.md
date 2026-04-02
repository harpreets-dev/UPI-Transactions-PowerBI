# 📊 UPI Transactions Data Analysis (Power BI)

## 📌 Project Overview

This project analyzes UPI transaction data to uncover patterns in digital payments, user behavior, and financial trends. The dashboard enables interactive exploration of transactions across multiple dimensions such as banks, cities, payment methods, and user demographics.

---

## 🎯 Business Objectives

* Analyze transaction trends over time (monthly analysis for 2024)
* Identify top-performing banks and cities
* Understand user behavior based on gender, age group, and device usage
* Evaluate transaction success/failure patterns
* Track financial balances across transactions

---

## 📂 Dataset Description

The dataset is sourced from an Excel file and contains transactional-level data with the following key fields:

* **Transaction Details**: TransactionID, Transaction Date, Transaction Time
* **Financial Metrics**: Amount, Remaining Balance
* **Bank Information**: BankNameSent, BankNameReceived
* **User Demographics**: Gender, Age Group
* **Location**: City (Delhi, Bangalore, Hyderabad, Mumbai)
* **Transaction Info**:

  * Transaction Type (Payment / Transfer)
  * Status (Success / Failed)
* **Technology Usage**:

  * Device Type (Mobile, Laptop, Tablet)
  * Payment Method (UPI ID, QR Code, Phone Number)
* **Merchant Data**:

  * Merchant Name (Amazon, Flipkart, Zomato, Swiggy, IRCTC)
  * Purpose (Food, Travel, Shopping, Bill Payment, Others)

---

## 📊 Dashboard Features

### 🔹 1. Monthly Transaction Trend

* Line chart showing **total transaction amount by month**
* Helps identify seasonal patterns in UPI usage

📌 Insight:

* Peak transaction volume observed around mid-year
* Noticeable dip during certain months indicating lower activity

---

### 🔹 2. Interactive Filtering System

The dashboard includes multiple slicers for deep analysis:

* Bank (Sender & Receiver)
* City
* Device Type
* Gender & Age Group
* Merchant Name
* Payment Method
* Purpose
* Transaction Type

➡️ Enables dynamic drill-down and customized analysis

---

### 🔹 3. City-wise Financial Matrix

* Displays:

  * Transaction Amount
  * Remaining Balance
* Organized by:

  * City → Currency → Month

📌 Insight:

* Major cities like Mumbai and Bangalore show higher transaction values
* Variation in balances highlights spending behavior across regions

---

### 🔹 4. Transaction Behavior Analysis

* Comparison of:

  * Payment vs Transfer transactions
  * Success vs Failed transactions

📌 Insight:

* Majority of transactions are successful
* Transfers and payments show different usage patterns

---

### 🔹 5. Payment & Device Trends

* Analysis of:

  * Payment methods (UPI ID, QR Code, Phone Number)
  * Device types (Mobile, Laptop, Tablet)

📌 Insight:

* Mobile devices dominate transaction activity
* QR and UPI ID are widely used payment methods

---

## 🛠 Tools & Technologies Used

* Power BI Desktop
* Power Query (ETL & Data Cleaning)
* DAX (Data Analysis Expressions)

---

## 📈 Key Insights

* 📊 Transaction volume fluctuates across months with clear peaks
* 📍 Metro cities contribute the highest transaction value
* 📱 Mobile is the primary device for UPI transactions
* 💳 QR Code and UPI ID dominate payment methods
* 🏦 Certain banks (SBI, ICICI, HDFC) appear frequently in transactions
* ⚠️ Failed transactions exist but are relatively low compared to successful ones



---
