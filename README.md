# 🧸 Flipkart Toys Scraper & Power BI Dashboard

This project scrapes toys data from Flipkart, saves it in a CSV file, and visualizes the data using an interactive Power BI dashboard.

## 📌 Features

- Scrapes product **title**, **price**, **rating**, and **discount** from Flipkart's search results.
- Saves the data into a clean and structured **CSV file**.
- Visualizes the data in a **Power BI dashboard** with various insights.
- Built with Python and BeautifulSoup.

## 📁 Project Structure

flipkart-toys-dashboard/
├── flipkart_toys_scraper.py # Python script to scrape and save data
├── products.csv # Scraped dataset (generated after running script)
├── Flipkart_Toys_Dashboard.pbix # Power BI dashboard file (optional)
└── README.md # This file

markdown
Copy
Edit

## 🛠️ Tools & Technologies

- **Python**
  - `requests`
  - `BeautifulSoup`
  - `csv`
- **Power BI** (for dashboard)
- **Flipkart.com** (data source)

## 🚀 How to Run

1. **Clone the repository**

   ```bash
   git clone https://github.com/yourusername/flipkart-toys-dashboard.git
   cd flipkart-toys-dashboard
Install dependencies

Make sure you have Python installed. Then install required packages:

bash
Copy
Edit
pip install requests beautifulsoup4
Run the scraper

bash
Copy
Edit
python flipkart_toys_scraper.py
This will scrape multiple pages and generate a products.csv file.

Open Power BI

Import the products.csv file.

Use it to build your visualizations (Bar chart for price comparison, pie chart for discount distribution, etc.)

Or open the pre-made Flipkart_Toys_Dashboard.pbix file (if available).

📊 Sample Dashboard Insights
Top-rated toys

Price distribution

Discount offers comparison

Rating vs. Price analysis

📷 Screenshots
![WhatsApp Image 2025-05-28 at 17 02 37_8111d81f](https://github.com/user-attachments/assets/c5c963fb-cb26-4e61-8c7e-688d1508f953)


📄 License
This project is for educational and research purposes only. Respect Flipkart's terms of service.

