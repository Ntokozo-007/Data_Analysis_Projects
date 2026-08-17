# Methodology

## 1. Source Data

The analysis uses the `Customer_Data` worksheet containing **10,936 records** and **16 fields**.

## 2. Data Structure

The data is stored as the Excel table `tbl_CustomerData` and includes identifiers, dates, sales agents, lead sources, call outcomes, follow-up status, conversion status, revenue, region, product/service, customer type, and calendar fields.

## 3. KPI Calculations

### Total Leads

Count of `Lead ID` records.

### Converted Leads

Count of records where `Conversion Status = Converted`.

### Conversion Rate

Converted Leads divided by Total Leads.

### Total Revenue

Sum of `Revenue Generated`.

### Average Revenue per Lead

Total Revenue divided by Total Leads.

## 4. Analysis Dimensions

Performance was reviewed by:

- Lead Source
- Product/Service
- Region
- Customer Type
- Agent
- Year
- Quarter
- Follow-up Status

## 5. Validation

Headline metrics were independently recalculated from the full `Customer_Data` worksheet to validate the portfolio findings against the source records.
