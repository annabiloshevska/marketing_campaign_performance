# Marketing Campaign Performance Analysis

This project analyzes the performance of multi-channel marketing campaigns, focusing on ROI, conversion rates, and cost efficiency. Key contributions include engineered metrics (CPC, CTR, CPM), web-scraped industry benchmarks, Excel-based insights, and a lightweight ML prediction tool.

## Project Overview

The analysis covers Facebook, Instagram, Google Ads, YouTube, and Email channels. Data cleaning handles raw campaign datasets, web scraping fetches benchmarks, and ML models predict outcomes. Excel analysis uncovers actionable patterns like Facebook's superior ROI despite low spend.

## Key Findings

- **ROI by Channel**: Facebook leads at 501.87%, Instagram trails at 498.87%—a tight ~3% spread.
- **Benchmark Performance**: All channels exceed market averages; overall CR hits 8.01% vs. 7.80% benchmark. Google Ads shines at 8.02% vs. 6.81%.
- **Surprises**: Facebook's low acquisition cost (~$410.6M) drives top ROI; Email's high spend ($420M+) underperforms.
- **Efficiency Notes**: High spend ≠ high ROI (Email vs. Facebook). YouTube/Instagram excel in CTR (14.1%+) but lag in final conversions.
- **Stability**: Monthly CTR holds steady at ~14%, validating creative consistency.

## Recommendations

- **Budget Shifts**: Boost Facebook by 10-15% ($40M-$60M) for max ROI; cut Email by 5% and redirect.
- **Optimization**: Lift YouTube/Instagram CVR from 7.99% to 8.01% via landing page fixes (mobile speed, one-click checkout)—unlocking thousands of conversions.

## Notebooks

- **[Data Cleaning](notebooks/Data_cleaning_for_hackathon.ipynb)**: Cleans raw data, engineers metrics (CPC, CTR, CPM).
- **[Web Scraping](notebooks/WebScraping_for_hackathon.ipynb)**: Scrapes benchmarks for CTR comparisons.
- **[ML Prediction](notebooks/MLpart_for_hackathon.ipynb)**: Builds prediction tool for campaign outcomes.

## Tech Stack

- Python (Pandas, NumPy for cleaning; Scikit-learn for ML)
- BeautifulSoup/Scrapy for web scraping
- Excel/Jupyter for visualization and insights

## Setup & Run

1. Clone: `git clone https://github.com/annabiloshevska/marketing_campaign_performance.git`
2. Install: `pip install -r requirements.txt` (create from notebook envs)
3. Run notebooks sequentially: Data cleaning → Scraping → ML.
4. Excel analysis: (click "Raw" → saves to your device → open in Google Sheets).

