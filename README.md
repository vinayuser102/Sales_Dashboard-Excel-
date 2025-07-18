# Sales_Dashboard-Excel-
coffee sales dashboard project:

---

**Coffee Sales Dashboard in Excel**

This project demonstrates the creation of an interactive and dynamic coffee sales dashboard entirely within Microsoft Excel, leveraging advanced Excel functionalities for data gathering, transformation, analysis, and visualisation.

**Project Overview & Purpose:**
The primary goal of this project was to build an end-to-end Excel solution to analyse coffee bean sales data. This involved consolidating data from multiple tables, performing necessary transformations and calculations, and then visualising key sales metrics through interactive charts and filters.

<img width="1195" height="668" alt="image" src="https://github.com/user-attachments/assets/ae0121ef-56f5-432e-ad79-8729a5e98d39" />




**Key Features of the Dashboard:**
The dashboard provides a comprehensive view of coffee sales, featuring:
*   **Total Sales Over Time Line Chart:** Displays total sales trends over time, segmented by four different coffee types: Arabica, Excelsa, Liberica, and Robusta.
*   **Sales by Country Bar Chart:** Visualises sales performance across the three countries where sales are made: U.S., Ireland, and the UK.
*   **Top Five Customers Bar Chart:** Highlights the top-performing customers based on their sales contributions.
*   **Interactive Timeline:** Allows users to dynamically filter all visuals by specific time periods (years and months).
*   **Dynamic Slicers:**
    *   **Roast Type Slicer:** Filters data by dark, light, or medium roasts.
    *   **Size Slicer:** Filters by coffee bean package sizes (0.2 kilo, 0.5 kilo, 1 kilo, 2.5 kilo).
    *   **Loyalty Card Slicer:** Filters customers based on whether they possess a loyalty card.





https://github.com/user-attachments/assets/ee3d47c1-1e7c-4be8-a28f-b3155452da8c




**Data Sources & Handling:**
The dashboard uses a dataset on coffee bean sales, drawing information from three main tables: 'orders', 'customers', and 'products'.
*   **Data Gathering:** Customer information (customer name, email, country) was gathered using the **XLOOKUP formula**. Product information (coffee type, roast type, size, unit price, profit) was gathered using the **INDEX MATCH formula**, chosen for its dynamic capabilities to populate multiple columns with a single formula.
*   **Data Transformation:**
    *   A 'sales' column was calculated by multiplying 'unit price' by 'quantity sold'.
    *   Abbreviated coffee types (e.g., 'ROB') were converted to full names (e.g., 'Robusta') using **IF functions** for improved readability.
    *   Abbreviated roast types (e.g., 'M') were converted to full names (e.g., 'Medium') using **IF functions** for improved readability.
    *   A 'loyalty card' column was dynamically added to the 'orders' table using **XLOOKUP** to link customer loyalty status from the 'customers' table.
*   **Data Formatting:**
    *   **Order dates** were formatted to display months as abbreviations (e.g., '05-Sep-2023') for clarity across different date formats.
    *   **Size** values were formatted to include 'kilo' (e.g., '1.0 kilo') for better understanding of units.
    *   **Unit price and sales** columns were formatted to US Dollars.
*   **Data Quality:** Duplicate values were checked for and confirmed as absent in the dataset.
*   **Excel Tables:** The entire data range was converted into an **Excel Table** named 'orders table'. This crucial step ensures that any new columns or updated data automatically expand the table's range, allowing pivot tables to refresh seamlessly without manual range adjustments.

**Dashboard Creation Process:**
*   **Pivot Tables:** Sales data was summarised using **Pivot Tables** to prepare the data for charting.
*   **Pivot Charts:** **Line charts and Bar charts** were created from the pivot tables.
*   **Chart & Slicer Customisation:** Extensive customisation was applied to chart colours, titles, axes, and data labels to enhance visual appeal and readability. Timelines and slicers were also custom-styled to match the dashboard's aesthetic.
*   **Interactivity:** A critical step involved connecting all slicers and the timeline to all three pivot charts using the **"Report Connections"** feature. This ensures that filtering one element updates all relevant visuals on the dashboard simultaneously, providing a dynamic user experience.
*   **Dashboard Layout:** Visuals were arranged on a dedicated dashboard worksheet. The overall dashboard appearance was refined by removing gridlines, the formula bar, scroll bars, and row/column headers to create a clean, professional look.

**Recreation/Customisation:**
This project is designed to be recreatable. All necessary resources and detailed steps are typically provided alongside the project (e.g., in the video description if this were from a tutorial). Users are encouraged to explore and apply their own visual preferences to customise the dashboard.

---
