# Extracting and Visualizing Stock Data

## 📊 Project Overview
This project focuses on extracting and visualizing stock data using Python libraries such as **yfinance**, **BeautifulSoup**, and **pandas**. The primary goal is to retrieve historical stock data and revenue information for two popular companies: **Tesla (TSLA)** and **GameStop (GME)**. The data is then analyzed and visualized to gain insights into the performance of these stocks.

---

## 🛠️ Tools & Libraries Used
- **yfinance**: To download historical stock data.
- **BeautifulSoup**: For web scraping revenue data.
- **pandas**: For data manipulation and analysis.
- **matplotlib**: For data visualization.
- **numpy**: For numerical computations.

---

## 🔍 Key Objectives
- Extract Tesla and GameStop stock price data using **yfinance**.
- Scrape Tesla and GameStop revenue data from a website using **BeautifulSoup**.
- Clean and organize the extracted data.
- Visualize the stock price trends and revenue performance over time.

---

## 🚀 Project Structure
```
Extracting-and-Visualizing-Stock-Data/
│
├── data/                        # Directory to store extracted data
│   ├── tesla_stock_data.csv
│   └── gme_stock_data.csv
│
├── notebooks/
│   └── stock_data_analysis.ipynb # Jupyter Notebook containing the entire analysis
│
├── README.md                     # Project documentation (this file)
│
└── requirements.txt              # Required libraries
```

---

## 📝 Data Extraction Process
### 1. **Tesla Stock Data (TSLA)**
- Extracted historical stock prices using **yfinance**.
- Data includes **Open, High, Low, Close, Volume, and Adjusted Close** prices.

### 2. **GameStop Stock Data (GME)**
- Extracted historical stock prices using **yfinance**.
- Data includes **Open, High, Low, Close, Volume, and Adjusted Close** prices.

### 3. **Revenue Data for Tesla and GameStop**
- Revenue data was scraped from a finance website using **BeautifulSoup**.
- The scraped data was cleaned and structured into a tabular format using **pandas**.

---

## 📈 Data Visualization
- Line plots were generated to visualize the **historical stock price trends** for **Tesla** and **GameStop**.
- Bar charts were created to represent **Tesla and GameStop revenue data** over time.
- Combined plots were generated to compare **stock price movement and revenue growth**.

---

## 🔥 Key Insights
- **Tesla** showed consistent growth in both stock price and revenue over time.
- **GameStop** displayed volatile stock price movements, influenced heavily by market sentiment, while its revenue showed fluctuations.

---

## ⚙️ How to Run the Project
1. **Clone the Repository:**
```bash
git clone https://github.com/YOUR_USERNAME/Extracting-and-Visualizing-Stock-Data.git
```
2. **Navigate to the Project Directory:**
```bash
cd Extracting-and-Visualizing-Stock-Data
```
3. **Install Dependencies:**
```bash
pip install -r requirements.txt
```
4. **Open the Jupyter Notebook:**
```bash
jupyter notebook notebooks/stock_data_analysis.ipynb
```
5. **Run the Notebook Cells** to extract data, analyze, and visualize.

---

## 📂 Sample Data Files
- **tesla_stock_data.csv**: Contains Tesla's stock price data.
- **gme_stock_data.csv**: Contains GameStop's stock price data.

---

## 🔧 Requirements
```
yfinance
beautifulsoup4
pandas
matplotlib
numpy
requests
```

