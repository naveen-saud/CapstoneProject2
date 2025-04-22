# Capstone Project 2: Web Scraping and Data Visualization

## Objective
The goal of this project is to scrape data from the e-commerce website [Web Scraper Test Site](https://webscraper.io/test-sites/e-commerce/allinone/computers/laptops) and perform the following tasks:
1. Extract specific product details.
2. Create a DataFrame for analysis.
3. Visualize the data using charts and graphs.

---

## Data to Extract
The following details are scraped for each product:
- **Product Name**: The name of the product.
- **Price**: The price of the product.
- **Description**: A brief description of the product.
- **Rating**: The product's rating (out of 5).
- **Review Count**: The number of reviews for the product.

---

## Steps to Complete the Project
### 1. **Web Scraping**
- Used Python libraries like `requests` and `BeautifulSoup` to scrape the data from the given URL.
- Extracted the required fields (name, price, description, rating, and review count) from the HTML structure of the webpage.

### 2. **Data Cleaning**
- Converted the scraped data into a structured format using `pandas`.
- Cleaned the data:
    - Removed unnecessary characters (e.g., `$` from prices).
    - Converted data types (e.g., price to `float`, ratings and reviews to `int`).

### 3. **Data Analysis**
- Sorted the data to identify:
    - Top 10 products by price.
    - Top 10 products by rating.
    - Top 10 products by the number of reviews.

### 4. **Data Visualization**
- Used `plotly.express` to create interactive visualizations:
    - **Bar Charts**: Displayed the top 10 products for each category (price, rating, reviews).
    - **Treemaps**: Provided a hierarchical view of the top 10 products.

---

## Deliverables
1. **DataFrame**: A structured table containing the scraped and cleaned data.
2. **Visualizations**:
     - Bar charts for top 10 products by price, rating, and reviews.
     - Treemaps for top 10 products by price and reviews.
3. **Insights**: Key observations from the data analysis.

---

## Tools and Libraries
- **Web Scraping**: `requests`, `BeautifulSoup`
- **Data Manipulation**: `pandas`
- **Data Visualization**: `plotly.express`

---

## How to Run the Project
1. Clone the repository or download the project files.
2. Install the required Python libraries:
   ```bash
   pip install requests pandas beautifulsoup4 plotly
   ```
3. Run the Jupyter Notebook to execute the code and generate the visualizations.

---

## Summary
This project demonstrates the ability to:
1. Scrape and process data from a website.
2. Perform data cleaning and analysis.
3. Create meaningful visualizations to derive insights.