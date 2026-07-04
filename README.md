# 🌐 Web Scraping and Exploratory Data Analysis of AI Companies

## 📌 Project Overview

This project demonstrates an end-to-end Data Analytics workflow by combining **Web Scraping** and **Exploratory Data Analysis (EDA)**.

Real-time AI company information was extracted from the **There's An AI For That** website using Python. The collected data was cleaned, validated, and analyzed to uncover trends in company valuation, funding, profitability, industry distribution, and country-wise performance.

The project highlights how raw web data can be transformed into meaningful business insights through data analysis and visualization.

---

## 🎯 Project Objectives

- Collect real-time AI company information using Web Scraping.
- Extract structured data from HTML pages.
- Build a clean and organized dataset.
- Perform data cleaning and preprocessing.
- Conduct Exploratory Data Analysis (EDA).
- Generate business insights and recommendations.
- Visualize key trends using charts.

---

## 📂 Dataset Information

**Source:** https://theresanaiforthat.com

The dataset contains information for **50 AI companies**.

### Dataset Features

| Column | Description |
|---------|-------------|
| Company Name | Name of the AI company |
| Country | Country where the company is located |
| Valuation | Company valuation (Billion USD) |
| Profitable | Profitability status |
| Industry | Industry category |
| Money Raised | Total funding raised (Billion USD) |
| Featured AI | Main AI product |
| Models | AI models developed by the company |

---

## 🛠️ Technologies Used

- Python
- Requests
- BeautifulSoup
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---
## 🚀 Project Highlights

- Collected real-time AI company data using Web Scraping.
- Built a structured dataset from raw HTML.
- Cleaned and transformed data using Pandas.
- Performed 8 Exploratory Data Analysis visualizations.
- Generated business insights and recommendations.
- Demonstrated an end-to-end Data Analytics workflow.
  
---

## 🔄 Project Workflow

```text
Website (https://theresanaiforthat.com)
        │
        ▼
Send HTTP Request
        │
        ▼
Parse HTML using BeautifulSoup
        │
        ▼
Extract Company Information
        │
        ▼
Create Python List
        │
        ▼
Convert to Pandas DataFrame
        │
        ▼
Export Raw CSV
        │
        ▼
Data Cleaning & Preprocessing
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Business Insights
        │
        ▼
Business Recommendations
---

## 🧹 Data Cleaning & Preprocessing

The following preprocessing steps were performed:

- Removed unwanted symbols and text
- Converted valuation into numerical format
- Converted funding into numerical format
- Removed country emojis
- Removed unnecessary columns
- Handled missing values
- Checked duplicate records
- Verified data types
- Validated dataset quality

---

## 📊 Exploratory Data Analysis

The following analyses were performed:

### 🌍 Company Distribution by Country

Analyzed the number of AI companies across different countries.

---

### 🏭 Industry Distribution

Visualized the distribution of AI companies across industries.

---

### 💰 Profitability Distribution

Compared profitable, non-profitable, and unknown company statuses.

---

### 📈 Top Companies by Valuation

Identified companies with the highest market valuation.

---

### 💵 Top Companies by Funding

Analyzed companies that received the highest investment.

---

### 📉 Valuation vs Money Raised

Explored the relationship between funding and company valuation using a scatter plot.

---

### 🔥 Correlation Heatmap

Measured the correlation between funding and valuation.

---

### 🌎 Average Valuation by Country

Compared the average valuation of AI companies across different countries.

---

## 💡 Key Business Insights

- The United States dominates the AI industry with the highest number of companies and the highest average valuation.
- Artificial Intelligence is the leading industry among the companies analyzed.
- Most AI companies are still in their growth phase and are not yet profitable.
- Anthropic recorded the highest valuation, while OpenAI secured the highest funding.
- Funding and valuation exhibit a strong positive correlation (0.85).
- Only a few companies account for exceptionally high valuations, while most companies have valuations below 100 Billion USD.

---

## 📈 Business Recommendations

- Focus investments on innovative AI startups with long-term growth potential.
- Encourage AI startup ecosystems outside the United States.
- Promote sustainable business models alongside rapid innovation.
- Increase investment in AI research and product development.
- Support emerging AI companies through funding and policy initiatives.

---

## 📈 Project Outcome

This project successfully demonstrates an end-to-end data analytics workflow by integrating web scraping, data preprocessing, exploratory data analysis, and business intelligence. The analysis provides valuable insights into AI company trends, funding patterns, profitability, and market valuation across different countries.

## 📁 Repository Structure

```
AI-Companies-Web-Scraping-and-EDA
│
├── README.md
├── requirements.txt
├── LICENSE
├── Web_Scraping_AI_Companies.ipynb
├── raw_ai_companies.xls
├── cleaned_ai_companies.xls
├── images
│   ├── country_distribution.png
│   ├── industry_distribution.png
│   ├── profitability_distribution.png
│   ├── top_valuation.png
│   ├── top_funding.png
│   ├── valuation_vs_funding.png
│   ├── correlation_heatmap.png
│   └── average_valuation_country.png
└── .gitignore
```

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/Nikhitha-IT/AI-Companies-Web-Scraping-and-EDA.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```
---
## 💼 Skills Demonstrated

- Python
- Web Scraping
- BeautifulSoup
- Pandas
- NumPy
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Matplotlib
- Seaborn
- Git
- GitHub

---
## 👩‍💻 Author

**Nikhitha Boda**

**Data Analyst Trainee** at **Innomatics Research Labs**

**Skills:** Python • Web Scraping • Data Analytics • Exploratory Data Analysis • Pandas • NumPy • Matplotlib • Seaborn • Git • GitHub

---
