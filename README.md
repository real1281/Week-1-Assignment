# Week-1-Assignment

1. Excel Basics
A. Navigation

Useful shortcuts:

Action	Shortcut
Move to beginning of worksheet	Ctrl + Home
Move to last used cell	Ctrl + End
Find data	Ctrl + F
Go to specific cell	Ctrl + G
AutoSum	Alt + =
B. Basic Formulas
SUM

Calculates total revenue.

Excel
=SUM(B2:B100)
AVERAGE

Calculates average sales.

Excel
=AVERAGE(B2:B100)
COUNT

Counts numeric entries.

Excel
=COUNT(B2:B100)
2. Data Cleaning Techniques

Before creating the dashboard:

Remove Duplicates
Select data.
Go to Data → Remove Duplicates.
Handle Missing Values

Use:

Excel
=IF(A2="","Missing",A2)
Remove Extra Spaces
Excel
=TRIM(A2)
Standardize Text
Excel
=UPPER(A2)

or

Excel
=PROPER(A2)
Check Blank Cells
Excel
=COUNTBLANK(A:A)
3. Descriptive Statistics

Assume Revenue is in column E.

Mean
Excel
=AVERAGE(E:E)
Median
Excel
=MEDIAN(E:E)
Mode
Excel
=MODE.SNGL(E:E)
Variance

Sample Variance:

Excel
=VAR.S(E:E)

Population Variance:

Excel
=VAR.P(E:E)
4. Create Pivot Tables
Pivot Table 1: Total Revenue
Select entire dataset.
Insert → Pivot Table.
Drag:
Revenue → Values

This gives total revenue.

Pivot Table 2: Sales by Category

Drag:

Category → Rows
Revenue → Values

Result:

Category	Total Revenue
Electronics	₹xxx
Clothing	₹xxx
Furniture	₹xxx
Pivot Table 3: Department-wise Revenue

Drag:

Department → Rows
Revenue → Values

Result:

Department	Revenue
HR	₹xxx
Marketing	₹xxx
Sales	₹xxx
Pivot Table 4: Yearly Sales Trend

If Date exists:

Place Date in Rows.
Right-click Date → Group.
Select Years.
Place Revenue in Values.

Result:

Year	Revenue
2021	₹xxx
2022	₹xxx
2023	₹xxx
5. Create Dashboard

Create a new sheet named Dashboard.

KPI Cards

Display:

Total Revenue
Average Revenue
Highest Revenue Department
Number of Transactions

Use linked cells from Pivot Tables.

Recommended Charts
Revenue by Category
Pivot Table: Category vs Revenue
Insert → Clustered Column Chart
Department-wise Revenue
Insert → Bar Chart
Yearly Sales Trend
Insert → Line Chart
Category Contribution
Insert → Pie Chart
Dashboard Layout Example
Plain Text
------------------------------------------------
| Total Revenue | Avg Revenue | Transactions |
------------------------------------------------
| Sales by Category (Column Chart) |
------------------------------------------------
| Department Revenue (Bar Chart) |
------------------------------------------------
| Yearly Sales Trend (Line Chart) |
------------------------------------------------
| Category Share (Pie Chart) |
------------------------------------------------
Expected Insights to Mention in Report
Which department generated the highest revenue.
Which category contributes most to sales.
Revenue growth year-over-year.
Average revenue per transaction.
Sales distribution across departments.
