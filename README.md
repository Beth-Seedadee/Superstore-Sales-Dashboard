# Superstore Sales Dashboard

This is a Power BI dashboard I built using the Superstore dataset, a
commonly used sample retail dataset with a few years of orders across
products, customers, and regions. I used Power Query to clean and shape
the raw data into a proper star schema, then built a one page dashboard
to explore sales and profitability.

## What's in here

- `Superstore_dataset_dashboard.pbix`, the Power BI file itself, open it
  in Power BI Desktop to see the data model, the Power Query steps, and
  the report
- `Superstore_dataset_dashboard.pdf`, the dashboard exported as a PDF, in
  case you just want to see the result without opening Power BI
- `superstore.csv`, the raw dataset the dashboard is built on

## What I did

I split the raw data into separate Customers, Products, and Order tables
in Power Query, cleaned up the columns, removed duplicates, and set the
right data types, then connected them into a model with proper
relationships instead of working off one flat table. From there I built
the dashboard with a sales trend over time, revenue and profit by
category, and a breakdown of sales by customer segment, plus filters for
segment, category, and year.

## What stood out

Office Supplies brings in the least revenue of the three categories but
by far the most profit, while Furniture sells a reasonable amount but
barely breaks even. If I were advising the business, I'd be asking why
Furniture is being pushed as hard as it is when the margin on it is so
thin.

## Tools

Built with Power BI Desktop, using Power Query for the data prep. 
