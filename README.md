# Biscuit-Brand-Sales-Analysis-Excel-Dashboard
Excel dashboard analysing 12,000 biscuit sales transactions by brand, location, customer segment and sales rep.
An interactive Excel dashboard that analyses one year of biscuit sales (12,000 transactions, 10 brands, 10 US cities) to show which products, locations, customers and sales reps drive revenue and profit.

## Business Problem
A biscuit company wants to know where its money comes from and where margins are being lost. This project answers:
- Which brands earn the most revenue and the most profit?
- Which cities, customer groups and payment methods contribute most?
- Who are the top sales reps?
- How did sales change month by month?

## Dataset
- **Records:** 12,000 transactions, 1 Jan 2024 to 31 Dec 2024
- **Fields:** transaction date, buyer name, location, date of birth, age, payment method, quantity, product code, sales rep, gender, brand, cost price, unit price, revenue, cost, profit and profit %
- **Lookup table:** product code, brand, cost price and unit price

## Tools and Techniques
- **Microsoft Excel**
- Formulas: `VLOOKUP`, `SUBSTITUTE`, `DATEDIF`, nested `IF` (age groups), `OFFSET`, `AVERAGE`
- Pivot tables and pivot charts
- Slicers and sparklines for interactive filtering
- Data cleaning (trailing spaces in names, calculated age and age-group columns)

## Workbook Structure
| Sheet | What it shows |
|---|---|
| Transaction Data | Cleaned data with calculated age, age group, revenue, cost, profit |
| Products | Product code to brand, cost and price lookup |
| Revenue / Profit / Quantity by Product | Brand-level performance |
| Profit Percentage | Margin by brand |
| Gender, Age wise sales | Customer segment analysis |
| Revenue by Location, Payment Type | Regional and payment analysis |
| Top 3 Buyers, Top 3 Salesmen | Leaders by revenue |
| Charts, DashBoard | Final visuals and interactive dashboard |

## Key Insights
- **Total revenue: 61.57M | Total profit: 26.78M | Overall margin: 43.5%** on 3.05M units sold.
- **Unibic is the top brand** with 13.97M revenue and the highest margin (77.8%), earning about 40% of all profit.
- **Little Hearts and Oreo** follow with 11.58M and 8.98M revenue, both at a 50% margin.
- **Good Day has the lowest margin (9.1%)** and Tiger and Britannia are under 20%, so these have the most room for pricing or cost improvement.
- **San Antonio is the top city** (7.34M, 11.9% of revenue); the other nine cities each contribute between 9% and 10%.
- **Male buyers account for 84% of revenue** (Female 9.5%, Other 6.1%).
- **Payment methods are evenly split** (about 25% each across debit card, mobile payment, credit card and cash).
- **Top sales reps by revenue:** Travis Doyle (10.88M), Joseph Hill (10.54M) and April Watkins (9.40M).
- **Monthly revenue falls sharply after July**, from 6.6M to 7.9M per month (Jan to Jul) to about 2M per month (Aug to Dec). This is worth investigating as a possible demand drop or a data gap.

## Recommendations
1. Protect and promote high-margin brands (Unibic, Little Hearts, Oreo).
2. Review pricing and costs for Good Day, Tiger and Britannia.
3. Investigate the sales drop from August and set up monthly tracking.
4. Target female and younger customer segments, which are currently under-served.

## How to Use
1. Download `Sales_Data_of_Biscuit_Brand.xlsx`
2. Open in Microsoft Excel and go to the **DashBoard** sheet
3. Use the slicers to filter by product, location and more

## Author
**C Jones Paulraj** | MBA (Marketing) | Aspiring Business Analyst
Bangalore | jonesjoel2002@gmail.com
