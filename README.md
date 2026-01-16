# web_scraper
Hockey Teams Web Scraper
Automated web scraping of NHL hockey teams data from scrapethissite.com using Python, BeautifulSoup, and Pandas.

🎯 Project Overview
This repository contains a complete web scraping solution that extracts NHL hockey teams data (Team Name, Year, Wins, Losses, OT Losses) from a structured HTML table and exports it to CSV format. Perfect for learning web scraping fundamentals and data extraction automation.

Scrapes 29 teams with 5 columns of structured data.

✨ Features
✅ Fetches live data from scrapethissite.com
✅ Parses HTML tables using BeautifulSoup
✅ Creates clean Pandas DataFrame
✅ Exports to CSV (ready for Excel/PowerBI)
✅ Full error handling and validation
✅ Jupyter/Colab ready

🛠️ Requirements
pip install requests beautifulsoup4 pandas
Python 3.8+ required

🚀 Quick Start
1. Clone Repository
git clone https://github.com/yourusername/hockey-scraper.git
cd hockey-scraper

2. Run the Scraper
jupyter notebook Hockey_Scraper.ipynb
# OR
python hockey_scraper.py

3. Get Your Data
✅ Scraped 29 rows!
✅ Saved Hockey.csv!
Output: Hockey.csv (29 rows × 5 columns)

📸 Sample Output
       Team Name  Year  Wins  Losses  OT Losses
0  Boston Bruins  2019    49     24         9
1  Toronto Maple  2019    46     28         8
...

🐛 Troubleshooting
| Issue                | Solution                      |
| -------------------- | ----------------------------- |
| requests not defined | Run pip install requests      |
| No table found       | Check internet connection     |
| Empty CSV            | Verify df.shape before export |

📊 Results
29 NHL teams scraped successfully with complete season statistics.

🎓 Learning Objectives
Web scraping with requests + BeautifulSoup
HTML table parsing
Pandas DataFrame manipulation
CSV data export
Jupyter notebook best practices
Error handling in web scraping

Built with ❤️ for data science education
January 2026
