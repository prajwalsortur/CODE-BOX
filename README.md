# 📱 Smartprix Product Data Scraper

A simple Python web-scraping project that extracts product information from Smartprix and converts it into a structured Pandas dataset.

The project collects **product names, stores, prices, and product links** and displays the results in a clean table.

---

## 🚀 Features

* Extracts product data from Smartprix
* Filters out upcoming products
* Extracts the best available store
* Extracts the best price
* Extracts product/store tracking links
* Handles missing store and link information
* Stores the extracted data in a Pandas DataFrame
* Displays the results in a formatted table

---

## 🛠️ Technologies Used

* **Python**
* **Requests** – Fetches data from the Smartprix API
* **BeautifulSoup** – Parses the response
* **JSON** – Processes structured API data
* **Pandas** – Creates and manages the dataset
* **Tabulate** – Displays the results as a table

---

## 📂 Project Structure

```text
Smartprix-Product-Scraper/
│
├── scraper.py
├── requirements.txt
└── README.md
```

---

## 🔄 How It Works

```text
Smartprix API
      ↓
Fetch Product Data
      ↓
Parse JSON Response
      ↓
Extract Product Information
      ↓
Filter Upcoming Products
      ↓
Create Pandas DataFrame
      ↓
Display Results
```

---

## 📊 Data Collected

The scraper extracts the following information:

| Column     | Description                 |
| ---------- | --------------------------- |
| Name       | Product name                |
| Store      | Best available store        |
| Best Price | Current best price          |
| Link       | Product/store tracking link |

---

## 💻 Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/Smartprix-Product-Scraper.git
```

### 2. Navigate to the project

```bash
cd Smartprix-Product-Scraper
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Project

```bash
python scraper.py
```

The extracted product information will be displayed in the terminal as a formatted table.

---

## 📦 Requirements

Create a `requirements.txt` file containing:

```text
requests
beautifulsoup4
pandas
tabulate
```

---

## 📌 Example Output

```text
Name                    Store       Best Price
------------------------------------------------
Samsung Galaxy S25      Amazon      ₹74,999

iPhone 16               Flipkart    ₹69,999

Google Pixel 9          Amazon      ₹62,999
```

---

## 🎯 Project Purpose

This project demonstrates the basic workflow of:

**Web Data Extraction → Data Processing → Structured Dataset → Data Presentation**

It can also serve as a foundation for future projects involving **price analysis, price tracking, machine learning, and product recommendation systems**.

---

## 🔮 Future Improvements

Possible improvements include:

* Store data in CSV or Excel
* Track prices over time
* Create price-history visualizations
* Detect price drops
* Build a price prediction model
* Add product recommendations
* Create a web dashboard
* Add an AI shopping assistant

---

## 👨‍💻 Author

**Prajwal Sortur**

Interested in **Data Science, Machine Learning, AI, and Generative AI**.

---

## ⭐ If You Like This Project

Consider giving the repository a ⭐ on GitHub.
