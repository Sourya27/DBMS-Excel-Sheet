# DBMS-Excel-Sheet
This project compares four DBMS options (A to D) based on performance, cost, maintenance time, and men required. Using SUMIF formulas, I calculated a performance-to-resource ratio (Rating) and identified the best DBMS. Results are visualized through a clustered column chart for easy comparison.


# Problem Statement :
DBMS Comparison Analysis for Optimal Selection

As a company grows, choosing the right database management system (DBMS) becomes critical to optimizing operational performance, reducing costs, and ensuring resource efficiency. In this scenario, the company has four DBMS options—DBMS A, DBMS B, DBMS C, and DBMS D—and seeks to identify the best one based on key performance aspects, including:
Performance: How well each DBMS handles tasks.
Cost: The financial expenses associated with maintenance.
Time Taken: Hours spent on upkeep and management.
Men Required: Number of personnel needed to maintain the DBMS.


# Analysis Process:
To start, data from January to December was collected for each DBMS on the aspects mentioned. The goal was to sum up these values for each DBMS and identify the best one based on an analysis that maximizes performance while minimizing cost, time taken, and men required.

I used the SUMIF formula to aggregate data for each aspect (Performance, Cost, Time Taken, and Men Required) separately for each DBMS. The formula allowed me to conditionally sum values, simplifying the process of evaluating each DBMS across these metrics.

# SUMIF Formula:
For DBMS A Performance:


=SUMIF(A:A, "DBMS A", C:C)
For DBMS A Cost:
=SUMIF(A:A, "DBMS A", E:E)
The same formula was applied to DBMS B, C, and D across all aspects (Performance, Cost, Time Taken, Men Required).
Creating a Consolidated Table:
After calculating the sums of each aspect for each DBMS, I compiled the results into a smaller table. This table serves as the basis for further analysis.

However, selecting the best DBMS involves more than just aggregating these values. The Performance should be high, while Cost, Time Taken, and Men Required should be as low as possible. To quantify this balance, I created a ratio for each DBMS, using:


# Rating= Performance/(Cost+ Time Taken+ Men Required)
​
 
This formula helps determine the DBMS that offers the highest performance relative to its resource demands.

# Visualization:
To make the comparison more visual, I created a clustered column chart to represent the costs of each DBMS. The chart focuses on column Q, which contains the summed cost data for DBMS A to DBMS D. This provides a quick, visual reference for comparing how cost-efficient each system is in relation to the others.

# Conclusion:
By calculating the performance-to-resource ratio and visualizing the costs, the company can easily identify the best DBMS. The system with the highest Rating (best performance and least resource consumption) is recommended for implementation.
