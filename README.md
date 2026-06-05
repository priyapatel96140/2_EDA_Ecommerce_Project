# E-Commerce Purchase Behavior - Exploratory Data Analysis (EDA)

This project is an exploratory data analysis (EDA) focused on analyzing online shopping behavior. Using a dataset of e-commerce transactions, the notebook answers key business questions about customer demographics, buying habits, payment methods, and when users are most active.


## Project Structure

The repository includes:
* **`2-EDA-Ecommerce-Project-question.ipynb`**: The Jupyter Notebook containing the analysis questions and step-by-step Python code.
* **`ecommercepurchases.csv`**: The dataset containing user profiles, browser data, and purchase amounts.


## Tech Stack & Dependencies

* **Language:** Python 3.x
* **Libraries Used:** Pandas, NumPy
* **Environment:** Jupyter Notebook / JupyterLab


## Dataset Overview

The `ecommercepurchases.csv` dataset contains information across 14 columns:

| Column Name | Description |
| :--- | :--- |
| `Address` | Customer's billing/shipping address |
| `Lot` | Internal tracking code |
| `AM or PM` | Time block of the purchase (Morning vs. Evening) |
| `Browser Info` | Browser and device information used for the purchase |
| `Company` | The company associated with the customer |
| `Credit Card` | Credit card identifier digits |
| `CC Exp Date` | Credit card expiration date (`MM/YY`) |
| `CC Security Code` | Security validation value (CVV) |
| `CC Provider` | Card provider (Visa, Mastercard, JCB, Maestro, etc.) |
| `Email` | Customer's email address |
| `Job` | Profession of the shopper |
| `IP Address` | IP address used during the transaction |
| `Language` | Language setting of the user's interface |
| `Purchase Price`| Final amount spent on the order ($) |


## Key Questions Answered

The notebook goes through the data step-by-step to find insights on:
1. **Data Discovery:** Checking total rows, column types, and identifying missing values.
2. **Financial Highlights:** Finding the average, highest, and lowest purchase prices.
3. **Language Preferences:** Counting how many transactions were made in different languages.
4. **Job Demographics:** Finding out which professions spend the most or buy most frequently.
5. **Time Patterns:** Comparing total sales made during AM vs. PM hours to see when traffic peaks.
6. **Browser Tracking:** Parsing the browser information strings to find out what browsers (Chrome, Safari, Firefox, etc.) shoppers use.
7. **Payment & Expiration Audits:** Checking which credit card providers are most popular and tracking how many cards expired in specific years (like 2020).


## How to Run This Project

Choose the option below that works best for you:

### Option 1: The Quick Way (No Git Required)
1. Click the green **Code** button at the top right of this GitHub page.
2. Click **Download ZIP** and unzip the files into a folder on your computer.
3. Move your dataset (`ecommercepurchases.csv`) into the same folder if it isn't already there.
4. Open your terminal or command prompt, navigate to that folder, and run:
   ```bash
   pip install pandas numpy notebook
   jupyter notebook


## Author

Priya Patel  
Aspiring Data Analyst  
Email: patelpriya18217@gmail.com   
GitHub: [priyapatel96140](https://github.com/priyapatel96140)  

If you like this project, feel free to give it a star!
