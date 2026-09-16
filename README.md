# CodeAlpha Data Analytics Internship

## Task 1: Web Scraping Using Python and BeautifulSoup

### Objective
The objective of this project is to extract book information from a public website using Python and BeautifulSoup and organize the collected information into a structured dataset.

### Website Used
Books to Scrape  
https://books.toscrape.com/

### Tools and Libraries Used
- Python
- Requests
- BeautifulSoup
- Pandas
- Google Colab

### Data Collected
The following information was extracted:
- Book Title
- Price
- Rating
- Availability

### Methodology
1. Selected a publicly available website for web scraping.
2. Sent a request to the website using the Requests library.
3. Parsed the HTML structure using BeautifulSoup.
4. Identified the required book information.
5. Extracted the title, price, rating, and availability.
6. Stored the extracted information in a Pandas DataFrame.
7. Checked the dataset for missing values and data types.
8. Saved the final dataset as a CSV file.

### Dataset
The dataset contains **20 book records** collected from the first page of the website.
The final dataset is available as:
`books_dataset.csv`

### Project Files
- `CodeAlpha_Task1_Web_Scraping.ipynb` – Google Colab notebook containing the complete scraping process.
- `books_dataset.csv` – Scraped book dataset.

### Result

The web scraping process successfully collected and organized book information into a structured dataset using Python and BeautifulSoup.
