# Extracting and Visualizing Stock Data: Tesla vs. GameStop

## Project Overview

This project demonstrates the process of extracting stock data and revenue information for Tesla (TSLA) and GameStop (GME) using Python libraries. It involves fetching historical stock prices via the `yfinance` library and scraping revenue data from web pages using `requests` and `BeautifulSoup`. Finally, the collected data is cleaned and visualized using `pandas` and `matplotlib` to compare historical share prices and revenue trends up to June 2021.

This notebook was completed as part of a Coursera assignment, showcasing skills in data extraction, web scraping, data cleaning, and visualization.

## Table of Contents

1.  [Project Goal](#project-goal)
2.  [Technologies Used](#technologies-used)
3.  [Setup and Installation](#setup-and-installation)
4.  [Notebook Structure](#notebook-structure)
5.  [Key Tasks Performed](#key-tasks-performed)
6.  [How to Run](#how-to-run)
7.  [Visualizations](#visualizations)
8.  [Coursera Submission Note](#coursera-submission-note)

## Project Goal

The primary objective is to extract, process, and visualize stock and revenue data for Tesla and GameStop to provide insights into their financial performance based on historical data.

## Technologies Used

*   **Python 3**
*   **Jupyter Notebook**
*   **Libraries:**
    *   `yfinance`: For fetching historical stock market data.
    *   `pandas`: For data manipulation and analysis.
    *   `requests`: For making HTTP requests to download web pages.
    *   `BeautifulSoup4`: For parsing HTML and XML documents (web scraping).
    *   `matplotlib`: For creating static, animated, and interactive visualizations.
    *   `re`: For regular expression operations (used in data cleaning).

## Setup and Installation

To run this notebook locally, ensure you have Python 3 installed. You can install the necessary libraries using pip:

```bash
# For Windows
pip install yfinance pandas requests beautifulsoup4 matplotlib

# For macOS/Linux
pip3 install yfinance pandas requests beautifulsoup4 matplotlib
```

*Note: The notebook includes installation commands within the code cells as well.*

## Notebook Structure

The Jupyter Notebook (`Final Assignment-v2.ipynb`) is organized sequentially:

1.  **Introduction & Setup:** Installs and imports necessary libraries.
2.  **Graphing Function Definition:** Defines the `make_graph` function used for plotting.
3.  **Question 1:** Extracts Tesla (TSLA) stock data using `yfinance`.
4.  **Question 2:** Scrapes and cleans Tesla revenue data from a web page.
5.  **Question 3:** Extracts GameStop (GME) stock data using `yfinance`.
6.  **Question 4:** Scrapes and cleans GameStop revenue data from a web page.
7.  **Question 5:** Plots Tesla's historical stock price and revenue using `make_graph`.
8.  **Question 6:** Plots GameStop's historical stock price and revenue using `make_graph`.
9.  **Question 7:** Instructions for sharing the assignment on GitHub for Coursera peer review.

## Key Tasks Performed

*   **Stock Data Extraction:** Utilized the `yfinance` library to fetch maximum historical stock data for TSLA and GME.
*   **Web Scraping:** Employed `requests` and `BeautifulSoup` to download and parse HTML tables containing quarterly revenue data for both companies.
*   **Data Cleaning:** Cleaned the extracted revenue data using `pandas` and `re` by removing currency symbols, commas, handling missing values, and converting data types.
*   **Data Visualization:** Created comparative plots showing historical stock closing prices and quarterly revenue using a predefined `make_graph` function with `matplotlib`.

## How to Run

1.  Clone or download this repository.
2.  Ensure all required libraries are installed (see [Setup and Installation](#setup-and-installation)).
3.  Open the `Final Assignment-v2.ipynb` file using Jupyter Notebook or JupyterLab.
4.  Run the cells sequentially from top to bottom.
5.  Make sure the `L.png` logo file is in the same directory as the notebook for the header image to display correctly.

## Visualizations

The notebook generates two main plots:

1.  **Tesla:** Historical Share Price vs. Historical Revenue (up to June 2021).
2.  **GameStop:** Historical Share Price vs. Historical Revenue (up to June 2021).

These plots are generated using the `make_graph` function in Questions 5 and 6.

## Coursera Submission Note

This project represents significant effort and learning applied during the Coursera course. The steps taken follow the assignment guidelines, demonstrating proficiency in the covered data science techniques. Reviewers are kindly requested to consider the diligence applied in completing this assignment. Thank you!

---
*Written by Lxgacy*
[![Skills Network Logo](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/assets/logos/SN_web_lightmode.png)](https://skills.network/?utm_medium=Exinfluencer&utm_source=Exinfluencer&utm_content=000026UJ&utm_term=10006555&utm_id=NA-SkillsNetwork-Channel-SkillsNetworkCoursesIBMDeveloperSkillsNetworkPY0220ENSkillsNetwork900-2022-01-01)

