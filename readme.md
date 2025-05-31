I embarked on this project as a learning opportunity, inspired by a YouTube video from Alex Freberg, widely known as Alex The Analyst. In his tutorial, Alex demonstrated how to use Python to scrape the names of t-shirts from Amazon, which introduced me to the fundamentals of web scraping.

Building on Alex's example, I decided to extend the project by incorporating additional attributes, such as **Brand Name, Discounted Price, Original Price, Ratings, Sponsorship Status,** etc.

After gathering the data, I exported it into a CSV file to enable further analysis. I performed basic cleaning on the dataset to ensure consistency and accuracy. Finally, I used **Tableau** to visualize the data and uncover specific insights, such as price trends, popular brands, and customer preferences.

This project allowed me to deepen my understanding of web scraping, data handling in Python, and visualization techniques.

## **🛠️ Requirements**
Python 3.6 or higher
Packages:
requests
beautifulsoup4
lxml (optional, for faster parsing)
pandas (for CSV export)
Install all dependencies with:
`pip install -r requirements.txt`

## **Project Structure**
```
project-folder/
│
├── Amazonscrape.ipynb       # Jupyter notebook with full workflow
├── Amazonscrapedataset.csv  # Example output data
├── requirements.txt           # List of dependencies
└── README.md                  # This file```

## **How to Use**

### 1. Clone the repository:

'''git clone https://github.com/yourusername/Amazon-Webscraping-using-python.git

cd Amazon-Webscraping-using-python'''

### 2. Install dependencies:
'pip install -r requirements.txt'

### 3. Set your Amazon search URL and User-Agent:

Copy your Amazon search results URL.
Find your browser’s User-Agent string (search "my user agent" on Google).

### 4. Run the scraper:

Run the Jupyter notebook step by step

### 5. Find your results:

Scraped data will be saved as Amazonscrapedataset.csv

## 📝 **Notes**

I respect Amazon’s Terms of Service. This project is for educational purposes only.

Amazon may block requests from scripts; using a valid User-Agent and handling request headers is important.

The HTML structure of Amazon pages may change, requiring updates to the scraping selectors.

## 📚 **References**

[BeautifulSoup Documentation](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)

[Requests Documentation](https://requests.readthedocs.io/en/latest/)

[Alex Freberg's Youtube video](https://www.youtube.com/watch?v=HiOtQMcI5wg)

## 📄 Full Documentation

For complete documentation and a detailed walkthrough of this project, please visit my Notion page: 

[Amazon Webscraping using Python – Full Documentation](https://www.notion.so/Amazon-Webscraping-using-Python-169b0a834e2680799e41e882bfc0bd74)

