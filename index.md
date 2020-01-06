---
query: Open-Returns.sql
---


# Query Library for Distributors

Query library for Swagelok distributors on SAP B1.

Below is a quick catalog of queries found useful by Swagelok distributors during and after GBS implementation.

Clone or download for a local copy or copy specific queries to clipboard as needed.

The validity and results of the query are the sole responsibility of the user; please be sure you understand what results are expected before running the query in your environment.


>For queries that require a view (a query that is saved in the database) the comments above query list the name of view which will be in the Views folder below.

## Categories

* [Activities](#activities)
* [Business Partners](#business-partners)
* [Data Governance](#data-governance)
* [Delivery](#delivery)
* [Finance](#finance)
* [Inventory](#inventory)
* [Invoice](#invoice)
* [Marketing](#marketing)
* [Order](#order)
* [Production](#production)
* [Purchasing](#purchasing)
* [Quote](#quote)
* [Reporting](#reporting)
* [Service](#service)
* [Views](#views)
* [Warehouse](#warehouse)

---

### Activities

- [Activities Overview by Date Range](Activities/Activities-Overview-by-Date-Range.sql)
- [All Activities Past Year](Activities/All-Activities-Past-Year.sql)
- [Open Returns](Activities/Open-Returns.md)

### Business-Partners

- [Alliance Codes](Business-Partners/Alliance-Codes.sql)
- [BP Owners and Group and Branch](Business-Partners/BP-Owners-and-Group-and-Branch.sql)
- [Business Partner Group and Owner](Business-Partners/Business-Partner-Group-and-Owner.sql)
- [Business Partner Group PriceList and Territory](Business-Partners/Business-Partner-Group-PriceList-and-Territory.sql)
- [Customer Notes](Business-Partners/Customer-Notes.sql)
- [Default Contacts](Business-Partners/Default-Contacts.sql)
- [Inactive Contacts](Business-Partners/Inactive-Contacts.sql)
- [Missing Industry](Business-Partners/Missing-Industry.sql)

### Data-Governance

- [BP Created Today](Data-Governance/BP-Created-Today.sql)
- [Outsource and Production Parts Created Today](Data-Governance/Outsource-and-Production-Parts-Created-Today.sql)
- [Standard Parts Created Today](Data-Governance/Standard-Parts-Created-Today.sql)

### Delivery

- [Tubing Delivery By Warehouse](Delivery/Tubing-Delivery-By-Warehouse.sql)
- [Closed Deliveries By Customer](Delivery/Closed-Deliveries-By-Customer.sql)

### Finance

- [Average Days Paid in AR](Finance/Average-Days-Paid-in-AR.sql)
- [Customer Aging Detail](Finance/Customer-Aging-Detail.sql)

### Inventory

- [All CS Flag Items](Inventory/All-CS-Flag-Items.sql)
- [All items with minimums](Inventory/All-items-with-minimums.sql)
- [BI Coding All](Inventory/BI-Coding-All.sql)
- [Bin Locations](Inventory/Bin-Locations.sql)
- [Bins with Multiple Parts](Inventory/Bins-with-Multiple-Parts.sql)
- [Count of Warehouses](Inventory/Count-of-Warehouses.sql)
- [Current Warehouse Value](Inventory/Current-Warehouse-Value.sql)
- [Item Notes](Inventory/Item-Notes.sql)
- [Parts in Multiple Bins](Inventory/Parts-in-Multiple-Bins.sql)
- [Top Inventory Stats](Inventory/Top-Inventory-Stats.sql)

### Invoice

- [Current User Invoice Details Union](Invoice/Current-User-Invoice-Details-Union.sql)
- [Gross Profit Info](Invoice/Gross-Profit-Info.sql)
- [Invoice Lines 12mo](Invoice/Invoice-Lines-12mo.sql)
- [Invoice Lines This Month](Invoice/Invoice-Lines-This-Month.sql)

### Marketing

- [Contacts Marketing OptOut](Marketing/Contacts-Marketing-OptOut.sql)
- [Global Survey Extract 2018](Marketing/Global-Survey-Extract-2018.sql)
- [Global Survey Extract 2018 V2](Marketing/Global-Survey-Extract-2018-V2.sql)

### Order

- [All Order Lines](Order/All-Order-Lines.sql)
- [All Orders](Order/All-Orders.sql)
- [Average Number of Closed Orders Past 4 Weeks](Order/Average-Number-of-Closed-Orders-Past-4-Weeks.sql)
- [Average Number of Orders Created Past 4 Weeks By CSR](Order/Average-Number-of-Orders-Created-Past-4-Weeks-By-CSR.sql)
- [Average Order Count By Month](Order/Average-Order-Count-By-Month.sql)
- [Closed Orders Today](Order/Closed-Orders-Today.sql)
- [Items Sold in Production Order](Order/Items-Sold-in-Production-Order.sql)
- [My Open Orders Past Target-Date](Order/My-Open-Orders-Past-Target-Date.sql)
- [My Order Lines Missing Price](Order/My-Order-Lines-Missing-Price.sql)
- [Order by Customer and Part](Order/Order-by-Customer-and-Part.sql)
- [Order Detail Lookup](Order/Order-Detail-Lookup.sql)
- [Order Missing Dates](Order/Order-Missing-Dates.sql)
- [Order Ship Dates](Order/Order-Ship-Dates.sql)
- [Order Stats By Account](Order/Order-Stats-By-Account.sql)
- [Today's Orders](Order/Today's-Orders.sql)
- [User Order Missing Dates](Order/User-Order-Missing-Dates.sql)

### Production

- [All Production Order Lines Past 7 Days](Production/All-Production-Order-Lines-Past-7-Days.sql)
- [All Production Quote Lines Past 7 Days](Production/All-Production-Quote-Lines-Past-7-Days.sql)
- [Difference in Planned Resource](Production/Difference-in-Planned-Resource.sql)
- [Items Sold in Production From Stock](Production/Items-Sold-in-Production-From-Stock.sql)
- [Items Sold in Production Order From Sales Order](Production/Items-Sold-in-Production-Order-From-Sales-Order.sql)
- [Open EDMON Production Order Past Target](Production/Open-EDMON-Production-Order-Past-Target.sql)
- [Production Orders Entered Today](Production/Production-Orders-Entered-Today.sql)
- [Ready To Build Production Orders](Production/Ready-To-Build-Production-Orders.sql)
- [Released for Production Planned Cost](Production/Released-for-Production-Planned-Cost.sql)

### Purchasing

- [All Items on a Purchase Order with Expected Dates](Purchasing/All-Items-on-a-Purchase-Order-with-Expected-Dates.sql)
- [All Reacknowledged POs](Purchasing/All-Reacknowledged-POs.sql)
- [All Swagelok Open PO Lines](Purchasing/All-Swagelok-Open-PO-Lines.sql)
- [Count of Factory PO By Date Range](Purchasing/Count-of-Factory-PO-By-Date-Range.sql)
- [Estimated Delivery Range](Purchasing/Estimated-Delivery-Range.sql)
- [Factory POs and Qty By Date Range](Purchasing/Factory-POs-and-Qty-By-Date-Range.sql)
- [Open POs with Delivery Days](Purchasing/Open-POs-with-Delivery-Days.sql)
- [Open SWGLK PO Lines with 0 Disc](Purchasing/Open-SWGLK-PO-Lines-with-0-Disc.sql)

### Quote

- [All Open Quotes Past Year](Quote/All-Open-Quotes-Past-Year.sql)
- [All Open Quotes](Quote/All-Open-Quotes.sql)
- [All Quotes Past Year](Quote/All-Quotes-Past-Year.sql)
- [My Open Quotes](Quote/My-Open-Quotes.sql)
- [Quotes I Updated](Quote/Quotes-I-Updated.sql)
- [Today's Custom Solution Quote Lines](Quote/Today's-Custom-Solution-Quote-Lines.sql)
- [Yesterday's Quote Lines](Quote/Yesterday's-Quote-Lines.sql)
- [Yesterday's Quotes](Quote/Yesterday's-Quotes.sql)

### Reporting

- [All Invoiced Lines By Date](Reporting/All-Invoiced-Lines-By-Date.sql)
- [Customer Care Service Calls](Reprting/Customer-Care-Service-Calls.sql)
- [Daily Count of Order Lines By CSR](Reporting/Daily-Count-of-Order-Lines-By-CSR.sql)
- [Daily Count of Orders By CSR](Reporting/Daily-Count-of-Orders-By-CSR.sql)
- [Frequency Rank](Reporting/Frequency-Rank.sql)
- [Monetary Rank](Reporting/Monetary-Rank.sql)
- [Order Count By Day](Reportin/Order-Count-By-Day.sql)
- [Recency Rank](Reporting/Recency-Rank.sql)
- [RFM Query](Reporting/RFM-Query.sql)
- [Yesterdays Stats](Reporting/Yesterdays-Stats.sql)

### Service

- [SQS Service Calls](Service/SQS-Service-Calls.sql)

### Views

- [DIST BI Desc](Views/DIST_BI_Desc.sql)
- [DIST Invoice Lines](Views/DIST_Invoice_Lines.sql)
- [DIST MRO Group](Views/DIST_MRO_Group.sql)
- [DIST Order Lines](Views/DIST_Order_Lines.sql)
- [DIST Quote Lines](Views/DIST_Quote_Lines.sql)
- [DIST Customer Aging Receivables](Views/DIST_Customer_Aging_Receivables.sql)

### Warehouse

- [To Be Picked](Warehouse/To-Be-Picked.sql)
