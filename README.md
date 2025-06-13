# News-Extraction-Pipeline

## 📌 Objective
This project builds a data pipeline in Python that **incrementally extracts** the latest news articles from **Skift** and **PhocusWire**, stores them in a **SQLite database**, and displays the **top 5 latest articles** sorted by publication timestamp.

---

## 🚀 Features
- 🔍 **Web scraping** using `requests` and `BeautifulSoup`
- 🧠 **Incremental loading** using unique article URLs
- 🗃️ **SQLite** database to store structured article data
- 📈 Displays **top 5 latest articles** on every execution
- 🧯 Robust **error handling** for network and duplicate issues

---

## 🛠️ Technologies Used
- Python 3.x
- SQLite
- Requests
- BeautifulSoup4
- Pandas
- Jupyter Notebook
