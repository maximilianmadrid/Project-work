# Sales Data Analysis Project

This repository contains three Python scripts for simulating and analyzing sales data for a fictional corporation called "Global Corp."

## Code 1: Sales Data Generation and Reporting

This script simulates sales data for a corporation with multiple stores and customers. It generates random orders for a variety of products, records them in the system, and then produces a sales report.

**Key Features:**

* **Object-Oriented Design:** Uses classes like `Product`, `Order`, `Customer`, `Store`, and `Corporation` to represent entities and their interactions.
* **Random Data Generation:** Creates realistic but synthetic sales data for testing and analysis purposes.
* **Sales Report Generation:** Outputs a formatted report showing order details, total sales per store, and total corporation sales.

**How to Use:**

1. Run the script in a Python environment.
2. The script will generate sales data and print a sales report to the console.

## Code 2: Sales Data Generation with Pandas

This script generates synthetic sales data using a similar approach to Code 1 but leverages the `pandas` library for more efficient data handling. It also organizes the data into a DataFrame for further analysis.

**Key Features:**

* **Pandas Integration:** Utilizes `pandas` DataFrames to store and manipulate sales data.
* **Improved Data Structure:** Provides a more organized and structured representation of sales data.
* **Extensibility:** Offers a solid foundation for conducting more complex data analysis tasks.

**How to Use:**

1. Ensure you have `pandas` installed (`pip install pandas`).
2. Run the script in a Python environment.
3. The script will generate sales data and display the head of the resulting DataFrame.

## Code 3: Market Basket Analysis

This script builds upon the previous codes by incorporating market basket analysis principles to identify best-selling items per store and across the entire corporation.

**Key Features:**

* **Best-Selling Items Analysis:** Determines the top-selling products for each individual store.
* **Overall Bestsellers:** Identifies the most popular products across all stores.
* **Market Basket Insights:** Provides insights into potential product associations and customer purchasing patterns.

# Sales Data Analysis Project

This repository contains three Python scripts for simulating, analyzing, and visualizing sales data for a fictional corporation called "Global Corp."

## How the Systems Work

### Code 1: Sales Data Generation and Reporting

This script utilizes object-oriented programming to represent entities like products, orders, customers, stores, and the corporation itself. It generates realistic but synthetic sales data and outputs a formatted report with order details, total sales per store, and total corporation sales.

### Code 2: Sales Data Generation with Pandas

This script integrates `pandas` DataFrames for data storage and manipulation. It offers a more structured data representation, enabling smoother and more complex data analysis tasks.

### Code 3: Market Basket Analysis

This script employs market basket analysis techniques to discover associations between items frequently purchased together. It identifies best-selling items per store and overall, providing insights into customer buying behavior.

## Usage Instructions

1. Clone this repository to your local machine.
2. Install the required libraries:
3. Replace placeholder data with your own sales data in the scripts (if desired).
4. Run each script individually using a Python environment:
    - `python sales_data_generation.py`
    - `python sales_data_pandas.py`
    - `python market_basket_analysis.py`
5. Review the outputs to understand the sales data, reports, and market basket analysis results.

## Example Output

The scripts will generate various outputs, including:

- Sales reports with order details and total sales.
- Pandas DataFrames for structured data representation.
- Lists of best-selling items per store and overall.
- Association rules highlighting potential product relationships.

## Further Exploration

This project can be extended to include more advanced analytics, visualizations, and predictive modeling to further enhance its capabilities and insights.
