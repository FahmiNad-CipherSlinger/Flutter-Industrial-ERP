# 🏭 Flutter Industrial ERP Suite

![Flutter](https://img.shields.io/badge/Flutter-3.x-blue.svg)
![Dart](https://img.shields.io/badge/Dart-3.x-0175C2.svg)


NZ ERP is an  **Industrial** (Go back-end & Flutter front-end) based enterprise management system & also actively runnning in NZ Tex Group. The ERP systems contain all the required modules for running industrial-grade businesses. The features are advanced and 

The application uses MySQL database and  JavaScript APIs to create business logic. All the database and javascript codes are available on GitHub.

The client is available for Andriod, iOS, macOS, Windows, and Web.

The server is available for Windows, macOS, and Linux.


Contact : forhad.it@nztexgroupbd.com, farhadahamed7492@gmail.com

---

## 🚀 Features

This ERP suite provides **10 specialized modules** tailored for industrial operations:

- **SM – Sales Management:** Handle sales, orders, quotations, and client relationships.  
- **PM – Purchase Management:** Streamline procurement and supplier processes.  
- **IM – Inventory Management:** Track stock, manage warehouses, and monitor movements.  
- **AM – Accounts Management:** Manage finances, ledgers, receivables, and payables.  
- **HRM – Human Resource Management:** HR tools for employees, payroll, and attendance.  
- **CMS – Commercial for Spinning Management:** Specialized workflows for spinning industries.  
- **PS – Dimension Management:** Configure and manage production dimensions.  
- **SPM – Spinning Management:** Oversee spinning processes and production data.  
- **LM – Land Management:** Manage land, assets, and property records.  
- **Dashboard & Setup:** Real-time analytics dashboards and system configuration.

---

## 🛠 Tech Stack

- **Frontend:** Flutter 3.x (Dart 3.x)  
- **State Management:** Riverpod  
- **Database:** SQLite
- **Networking:** REST API / GraphQL (based on your backend)  
- **CI/CD:** GitHub Actions
- **Server:** Local Server  
- **Platforms:** Android, iOS, Web, Desktop

---

## Starting server @ localhost:8080
 
Open the application in a browser and test that you can login with the default username and password (admin/admin)

<img src="[https://drive.google.com/drive/folders/1Ie4U34-goZiOFw28JnLcOhdKiLGXQe23](https://drive.google.com/file/d/1wWx9wDJEvQu_4mKX8acdG7FZ9W6M21Bv/view?usp=sharing)"/>

Click on the Login button, and the system will redirect you to the dashboard.



## Modules
------------

Below are the fully functional ERP Modules available in NZERP

###  General Ledger (GL)
Chart of Accounts
inoERP allows a multi-segment accounting structure that you can use to represent all segments of a business transaction.
      Ex : 001-100-1020202-0100-100
      Where 001 – Represents a specific company/business unit /legal entity
      100 – Represents a cost center
      1020202 – a Natural account such as Asset, Liability, Expense, Income, or Owners Equity

2. Calendars 
Define as many different financial calendars as required
Ex: One calendar INO_CORP for Corporate and INO_USA, INO_UK for specific countries
3. Account Combinations
4. Currency & Conversions
5. Ledger:  A set of a calendar, currency, and chart of accounts
6. Banks
7. Journal 


###  Accounts Payable(AP)
1. Suppliers
2. AP Transactions
 -  2.1 Invoices
 -  2.2 Debit Memo
 -  2.3 Credit Memo
3. PO/Transaction Matching 
4. Multi select matching
5. AP Payments
 -  5.1 Single Invoice Payment
 -  5.2 Multi select Payment
6. Transfer Journals to GL

###  Accounts Receivable(AR)
1.  Customer
2.  AR Transactions
 -  2.1 Invoices
 -  2.2 Debit Memo
 -  2.3 Credit Memo
 -  2.4 Deposit
 -  2.5 Guarantee
 -  2.6 Charge Back
3.  AR Payments
 -  3.1 Single Invoice Payment
 -  3.2 Multi select Payment
4. Transfer Journals to GL

###  Fixed Asset Accounting(FA)
1. Asset
2. Depreciation
3. Transactions
4. Configuration

### Organizations(ORG)
1. Enterprise Org
2. Legal Org
3. Business Org
4. Inventory Org
5   Address

### Inventory (INV)
1. Item Master
2. Unit of Measure
3. Sub inventory
4. Locator
5. Inventory Transactions
6. Material Receipts
     * PO Receipt  
     * IR Receipt  
     * RMA Receipt  
7. Onhand Value
8. Cycle Count
    * Cycle Count Adjustment
    * Cycle Count Approval 
9. ABC Analysis

### Purchasing (PO)
1. Purchase Order
    * Standard
    * Blanket Agreement
    * Planned PO
2. Requisitions
    * External
    * Internal

3. RFQ / Quote
4. Approval for PO, Requisition

### Sales & Distributions (SD)
1. Sales Order - Creation & Auto Booking
2. Sales Picking
3. Delivery & Shipment
4. Auto AR Invoice

### Bills Of Material (BOM)
1. Departments
2. Resources
3. Routing
4. BOM
5. Super BOM

### Costing (CST)
1. Material Element
2. Material OH 
3. Overhead
4. Resources
5. Standard Cost
6. Cost Roll Up
7. Cost Update

### Work in Process (WIP)
1. Work Order 
2. WIP Move Transactions
3. WIP Resource Transactions
4. WIP Material Transaction
5. WO Completion/Return

### Supply Chain Planning (SCP)
1. Forecast
2. MDS
3. MRP
4. Min-Max Planning
    * Multi Bin Min Max
    
### Human Resource (HR)
1. Employee
    * Education
    * Experience
    * Planned PO
2. Job
3. Position
4. Compensation & Payroll
4. Leave System
4. Approval Hierarchy
    
### Basic Features
1.   Options
2.   Value Groups
3.   Transaction Types
4.   Custom Reporting
5.   Search
5.   Multi Select
6.   Mass Upload    

### Admin
1. User 
2. Roles and Role Base Access Control
3. Notification
4. Document Approval

## Modules Under Development
------------
1. Project System
2. Asset Maintenance
3. HelpDesk


## Dynamic pull System
------------
The idea behind inoERP is to provide a dynamic pull-based system where the demand /supply changes frequently and traditional planning systems (such as MRP or Kanban) are incompetent to provide a good inventory turn.

A dynamic pull system is an advanced version of a pull system that encompasses the best feature of the traditional pull system & MRP. The major disadvantage of the conventional Kanban system is the fixed Kanban size and requirement of at least two bins for the entire operation. In a sudden demand decrease, the Kanban system can result in extra inventory, and the value of unused inventory can go up to 2 bin size. Similarly, In case of unexpected demand increases can result in a line down, and the issue will be severe if the lead times are not short.

The dynamic pull system overcomes this issue by recalculating the bucket size (Kanban size/lot size) before creating any supply (requisitions/purchase order/work order). Each time a new supply is created, the system automatically decides the best supply size per the actual demand.

> *The old PHP version of inoERP is available @ https://github.com/php-inoerp/inoERP*
