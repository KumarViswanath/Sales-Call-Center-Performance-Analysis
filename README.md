# Sales-Call-Center-Performance-Analysis
Week 5 Assignment

This project analyzes sales call data to uncover key insights and provide data-driven recommendations for improving call center efficiency and sales performance. The analysis focuses on understanding call purpose, comparing sales success rates between different branches, and examining call volume across various shifts.

---

## Data Source
The analysis is based on a CSV file named **SalesCallData.csv**.  
This dataset contains detailed information about individual sales calls, including:

- **Call metadata**: Branch, Shift, Queue, Rep ID, and Incoming or Outgoing.  
- **Performance metrics**: Total Wait Time, Lost Call, Sales, and Calls.  
- **Call context**: Call Purpose.  

---

## Data Visualizations & Analysis

### 1. Distribution of Call Purposes
This bar chart shows the frequency of different reasons customers contact the call center. It highlights that while **Sales Support** is the primary reason, a significant number of calls are also related to **Complaints** and other service issues.

### 2. Sales Success Rate by Branch
This visualization compares the sales conversion rate between the **North** and **South** branches. It reveals a major performance difference, with the **South branch significantly outperforming** the North branch in converting calls into sales. This suggests different strategies or operational efficiencies are at play.

### 3. Call Volume by Shift and Branch
This stacked bar chart illustrates how call volume is distributed across different shifts and branches. It identifies the **Evening shift** as the busiest period, indicating where additional resources might be needed to handle peak demand. The **North branch** also consistently handles a higher volume of calls overall.

---

## Key Conclusions

Based on the analysis, we can conclude the following:

- **Operational Focus**: While sales support is the core function, the volume of complaints indicates a potential need to improve customer service or address underlying product/service issues.  
- **Performance Disparity**: There is a considerable performance gap between the two branches. The successful strategies of the South branch should be studied and implemented in the North branch to boost sales.  
- **Resource Allocation**: The call center should reallocate resources to better support the **Evening shift**, which experiences the highest call volume. This will help maintain service quality and reduce customer wait times.  

---

## How to Use

1. Make sure you have Python installed.  
2. Install the required libraries:  
   ```bash
   pip install pandas matplotlib
