# Bank-Loan-Application-Tracking-Dashboard-in-Excel
Bank Loan Applications Tracking Dashboard is designed to analyze loan application trends, approval rates, interest rate performance.

##Introduction:
The process begins with data preparation, where raw information is organized into tables and categorized using formulas to distinguish between good and bad loans. 
Multiple pivot tables are generated to calculate essential metrics like funded amounts, interest rates, and debt-to-income ratios.
These figures are visualized through various elements, including donut charts, line graphs, and geographic maps to show loan distribution by state and purpose. 
Final touches include the addition of interactive slicers and a full screen macro to ensure the dashboard is both user-friendly and visually appealing.

##Steps:
I have completed the process of creating the bank loan application tracking dashboard by following these steps:

## **1. Data Structuring and Preparation**
I began by renaming my primary worksheet to **"data"** and converting the dataset into a **table format** to ensure better clarity and organization. I **froze the top row** so the headers remained visible while scrolling and **removed gridlines** to create a cleaner workspace. To categorize the loans, I inserted a new column and used an **IF formula** to create a **"good versus bad loan flag,"** classifying "fully paid" or "current" loans as good and "charged off" loans as bad.

## **2. Building Pivot Tables for Metrics**
I inserted a pivot table into a new sheet named **"pivot"** and summarized core metrics, including the **count of Loan IDs**, **total funded amounts**, and **average interest rates**. I carefully formatted these values to display as **thousands (K)** or **millions (M)** and adjusted interest rates and DTI ratios to **percentages with one decimal place**. From there, I generated additional pivot tables to analyze:
*   **Good vs. Bad Loans** (including percentages of the total).
*   **Monthly trends** using the loan issue date.
*   **Employee experience** (sorted in ascending order by application count).
*   **Loan purposes and terms**.
*   **Geographic distribution** by state.

## **3. Designing the Dashboard Layout**
I created a dedicated **"dashboard" sheet**, removed its gridlines, and set the zoom level to **80%** for optimal visibility. I inserted **rectangular shapes** to form the background and added a title text box labeled **"bank loan applications dashboard"** using a bold Calibri font. I also integrated **functional icons** for zooming, data refreshing, and representing key metrics.

## **4. Constructing Visualizations**
To display live totals for applications and funded amounts, I **linked text boxes** directly to the pivot table values using the **equals (=) formula**. I then developed the following visual components:
*   **Donut Charts:** I created these for **Good/Bad Loan Issued** and **Loan Application by Term**, setting the donut hole size to **71%** and placing percentage values in the center.
*   **Clustered Column Chart:** I used this for **interest rate analysis**, hiding all field buttons and placing data labels at the center of each bar.
*   **Trend and Distribution Charts:** I inserted a **line chart with markers** for monthly trends, **bar charts** for employee experience and loan purpose (setting the gap width to 60%), and a **map chart** to highlight applications by state.

### **5. Implementing Interactivity and Macros**
I added **slicers for "Grade" and "Purpose,"** customizing their appearance to match the dashboard theme. I used **"Report Connections"** to link these slicers to all relevant pivot tables, ensuring the entire dashboard updates simultaneously when a filter is applied. Finally, I **assigned macros** to a zoom icon, allowing for automated screen adjustments with a single click.
