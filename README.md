# 🧾 Money Tracker: AI-Powered Personal Finance Tracker

> An intelligent desktop application for personal budget management that eliminates manual data entry using OCR and predicts future expenses using mathematical models.

## 💡 About the Project
Tracking personal finances manually is tedious and often leads to abandoned spreadsheets. This project aims to automate the boring parts of budgeting. Instead of typing every purchase by hand, users can simply upload a photo of their receipt. The application reads the text, extracts the amounts, automatically categorizes the expenses, and provides data-driven forecasts for future months. 

This is an educational project focused on applying Object-Oriented Programming, mathematical algorithms (Linear Regression, Naive Bayes), and third-party integrations within the Java ecosystem.

## ✨ Key Features
* **Optical Character Recognition (OCR):** Upload a receipt image, and the system extracts items and prices automatically.
* **Smart Categorization:** Automatically assigns tags (e.g., Food, Entertainment, Utilities) based on extracted text.
* **Predictive Analytics:** Uses mathematical forecasting on historical data to predict next month's spending and prevent budget overruns.
* **Interactive Dashboards:** Visualizes spending habits through dynamic charts and graphs.
* **Local & Secure:** All financial data is stored locally in an SQLite database, ensuring complete privacy.

## 🛠️ Tech Stack
* **Language:** Java (JDK 17+)
* **GUI Framework:** JavaFX
* **Database:** SQLite (via JDBC)
* **OCR Engine:** Tess4J (Tesseract API wrapper)
