# 📱 CODE-BOX — Smartprix Product Data Scraper

A simple Python web-scraping project that extracts product information from **Smartprix** and presents it as a clean, structured dataset.

## 🚀 Features

* 🔍 Extracts product information from Smartprix
* 🏪 Finds the available store
* 💰 Extracts the best price
* 🔗 Extracts product links
* 🚫 Filters upcoming products
* 📊 Stores data using Pandas
* 📋 Displays results in a clean table
* ⚡ Handles missing data

## 🛠️ Technologies

* **Python**
* **Requests**
* **BeautifulSoup**
* **JSON**
* **Pandas**
* **Tabulate**

## 📂 Project Structure

```text
CODE-BOX/
│
├── bestpricefinder.py
└── README.md
```

## 🔄 How It Works

```text
Smartprix
    ↓
Fetch Product Data
    ↓
Parse Response
    ↓
Extract Product Details
    ↓
Filter Products
    ↓
Create Pandas DataFrame
    ↓
Display Results
```

## 📊 Data Collected

| Data         | Description                  |
| ------------ | ---------------------------- |
| Product Name | Name of the product          |
| Store        | Available store              |
| Best Price   | Current best available price |
| Link         | Product/store link           |

## 💻 Installation

### 1. Clone the repository

```bash
git clone https://github.com/prajwalsortur/CODE-BOX.git
```

### 2. Open the project

```bash
cd CODE-BOX
```

### 3. Install dependencies

```bash
pip install requests beautifulsoup4 pandas tabulate
```

## ▶️ Run

```bash
python bestpricefinder.py
```

The extracted product information will be displayed as a formatted table in the terminal.

## 🎯 Purpose

This project demonstrates a basic data workflow:

**Web Data Extraction → Data Processing → Structured Data → Data Presentation**

It can also serve as a starting point for future **price analysis, price tracking, and recommendation systems**.

## 👨‍💻 Author

**Prajwal Sortur**

Data Science • AI/ML • Generative AI • Data Analytics

[GitHub](https://github.com/prajwalsortur)

---

⭐ If you find this project useful, consider giving the repository a star.
