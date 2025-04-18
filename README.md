# Online Sales Data Analysis

## Objective
This project focuses on analyzing sales data using Python to calculate total boxes shipped and revenue for each product category. The analysis includes data aggregation and visualization to provide clear insights into product performance.

---

## Dataset Overview
The analysis is based on the `online_sales.csv` dataset, which contains sales transaction records. Below is an overview of the dataset structure:

- `order_id`: Unique identifier for each transaction.
- `sales_person`: Name of the salesperson handling the transaction.
- `country`: Country of the sale.
- `product`: Product category (e.g., Laptop, Tablet, Monitor).
- `order_date`: Date when the order was placed.
- `amount`: Revenue generated from the transaction.
- `boxes_shipped`: Number of boxes shipped for the order.

The dataset spans multiple countries and products, offering a rich scope for analysis.

---

## Steps Taken

1. **Data Loading**:
   - Imported the `online_sales.csv` file into a Pandas DataFrame for manipulation and analysis.

2. **Data Inspection and Cleaning**:
   - Ensured the dataset was complete and accurate by:
     - Checking for missing values and duplicate entries.
     - Verifying column types and converting them if necessary (e.g., ensuring numeric columns like `amount` were correctly typed).

3. **Data Aggregation**:
   - Grouped data by the `product` column to calculate:
     - `total_boxes`: The sum of boxes shipped for each product.
     - `revenue`: The total revenue generated for each product.

4. **Data Presentation**:
   - Displayed the aggregated data as a clean, formatted table using Pandas' `print()` function.

5. **Data Visualization**:
   - Created a bar chart with Matplotlib to visualize:
     - X-axis: Product categories.
     - Y-axis: Total revenue for each product.
   - Saved the visualization as `sales_chart.png`.

6. **Exporting Results**:
   - Saved the aggregated data as a CSV file named `sales_summary.csv` for easy reference and sharing.

7. **Code Documentation**:
   - Added comments to the Python script to explain each step and improve readability.

---

## Tools and Libraries

This project utilizes the following technologies and libraries:

- **Python 3.10**
  - **Pandas**: For data manipulation and aggregation.
  - **Matplotlib**: For data visualization.
- **GitHub**: To document and share the project.
- **CSV Format**: Used for both input and output datasets.

---

## How to Run the Code

Follow these steps to execute the code on your local machine:

1. **Install Python**:
   - Download and install Python from the [official website](https://www.python.org/).

2. **Install Required Libraries**:
   - Run the following command in your terminal to install Pandas and Matplotlib:
     ```bash
     pip install pandas matplotlib
     ```

3. **Prepare the Dataset**:
   - Place the `online_sales.csv` file in the same directory as the Python script.

4. **Execute the Script**:
   - Run the script using the following command:
     ```bash
     python script.py
     ```

5. **View Results**:
   - Check the console for the printed sales summary.
   - Open `sales_chart.png` to view the bar chart.
   - Refer to `sales_summary.csv` for the exported aggregated data.

---

## Output

The project generates the following outputs:
1. **Sales Summary Table**:
   - Displays total boxes shipped and revenue for each product.
2. **Bar Chart**:
   - Visualizes the revenue distribution among products.
3. **CSV File**:
   - `sales_summary.csv` contains the aggregated data for reference.

---

## Results

### Summary Table (Sample Output):
| Product   | Total Boxes | Revenue |
|-----------|-------------|---------|
| Laptop    | 6           | 10,500  |
| Tablet    | 12          | 5,850   |
| Monitor   | 10          | 2,700   |

### Bar Chart:
- The bar chart illustrates that laptops generate the highest revenue, followed by tablets and monitors.

---

## Learning Outcome

This project provided valuable insights into:
- Using Python for end-to-end data analysis.
- Aggregating and summarizing data with Pandas.
- Creating effective visualizations with Matplotlib.
- Exporting processed data for reporting and sharing.
- Documenting and publishing projects on GitHub.

---

## License (Optional)
You can add a license here if you’d like to specify how others can use or contribute to your project.

---
