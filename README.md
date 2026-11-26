# E-Commerce Sales Analyzer

## Project Description
The E-Commerce Sales Analyzer is a Python-based project that analyzes online sales data stored in a CSV file. It helps calculate total revenue, total units sold, product-wise revenue, and category-wise revenue. It also identifies the top five products based on revenue and presents sales information through graphical visualizations.

## Problem Statement
E-commerce businesses generate a large amount of sales data through online transactions. Analyzing this data manually can be time-consuming and make it difficult to identify popular products and category-wise revenue. This project aims to process and analyze sales records efficiently using Python.

## Features
- Reads sales data from a CSV file.
- Checks required columns and validates records.
- Removes duplicate rows.
- Handles missing and invalid values.
- Calculates revenue using Quantity × Price.
- Displays total revenue, orders, and units sold.
- Shows product-wise and category-wise revenue.
- Identifies the top five products by revenue.
- Generates a pie chart for category-wise revenue.
- Generates a bar chart for the top five products.
- Provides a menu-driven console interface.

## Technologies Used
- Python 3
- Pandas
- Matplotlib
- CSV

## Project Structure
```text
E-Commerce-Sales-Analyzer/
│
├── Source_Code/
│   ├── main.py
│   └── orders.csv
│
├── Project_Documentation/
│   ├── Project_Report.docx
│   └── Project_Presentation.pptx
│
└── README.md
```

## Installation Requirements
Make sure Python 3 is installed on your system.

Install the required libraries using:

```bash
pip install pandas matplotlib
```

## How to Run the Project
1. Download or clone this repository.
2. Open the project folder in VS Code or a terminal.
3. Navigate to the source code folder:

```bash
cd Source_Code
```

4. Run the Python program:

```bash
python main.py
```

**Note:** Keep `main.py` and `orders.csv` in the same folder.

## CSV Dataset Format
The input CSV file must contain the following columns:

| Column | Description |
|---|---|
| Order_ID | Unique order identifier |
| Product | Name of the product |
| Category | Product category |
| Quantity | Number of units sold |
| Price | Price per unit |

Revenue is calculated using:

`Revenue = Quantity × Price`

## Menu Options
1. **Sales Summary:** Displays total revenue, total orders, total units sold, and top products.
2. **Category-wise Revenue:** Displays revenue and percentage contribution of each category with a pie chart.
3. **Top 5 Products Chart:** Displays a bar chart of the five products with the highest revenue.
4. **Exit:** Closes the program.

## Visualizations
The project generates two types of charts:
- Pie Chart – Represents the percentage contribution of each product category to total revenue.
- Bar Chart – Represents the revenue of the top five products.

## Future Enhancements
- Database integration for storing sales records.
- Graphical User Interface (GUI).
- Real-time sales analysis.
- Exporting reports to PDF or Excel.
- Advanced sales trend analysis.

## Author
**Mahima Jain**  
BCA (AI & ML)  
Rungta International Skills University
