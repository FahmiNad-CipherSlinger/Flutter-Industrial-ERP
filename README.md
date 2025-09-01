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
- **Networking:** REST API
- **CI/CD:** GitHub Actions
- **Server:** Local Server  
- **Platforms:** Android, iOS, Web, Desktop

---

## Starting server @ localhost:8080
 
Open the application in a browser and test that you can login with the default username and password (admin/admin)


<img width="1366" height="684" alt="login pannel" src="https://github.com/user-attachments/assets/1051af4b-bc94-4697-ac62-c5fe0512a11f" />

Click on the Login button, and the system will redirect you to the dashboard.



## Modules
------------

Below are the fully functional ERP Modules available in NZERP

###  Sales Management (SM)
NZERP allows a multi-segment Sales structure that you can use to represent all segments of a business transaction.
      Ex : 001-100-1020202-0100-100
      Where 001 – Represents a specific company/business unit /legal entity
      100 – Represents a cost center
      1020202 – a Natural account such as Asset, Liability, Expense, Income, or Owners Equity
Manage leads, sales orders, quotations, and client relationships with real-time tracking and automation tools.
1.Sales Order
2.Direct Invoice
3.Payment Receive
4.Sales Order Inquiry
5.Transactions
6.Customers
7.Branch
8.Reports and Analysis

###  Purchase Management (PM) 
Streamline procurement processes, manage suppliers, and track purchase orders efficiently.

1.Purchase Order
2.Receive
3.Supplier Invoice
4.Payments to Suppliers
5.Transactions
6.Suppliers
7.Reports and Analysis

###  Inventory Management (IM)
Maintain accurate stock levels, track product movement, and optimize warehouse operations.
1.Inventory Adjustments
2.Inventory Movements
3.Items
4.Sales Pricing
5.Reports and Analysis


###  Accounts Management (AM)

Handle financial transactions, general ledgers, receivables, payables, and expense tracking with precision.
1.Bank Payments
2.Cash Payments
3.Bank Received
4.Cash Received
5.Journal Entry
6.Bank Account Inquiry
7.GL Account Inquiry
8.Trial Balance
9.Exchange Rates
10.GL Accounts
11.Reports and Analysis
12.Bank Account Received Entry	

### Commercial for Spinning Management (CMS)
Tailored for spinning industries, providing solutions for managing commercial processes and related workflows.
This section is hidden for company purpose.


### Dimension Management (PS)
Handle dimension planning and production standards with accuracy and flexibility.

1.Dimension Entry
2.Dimension Inquiry
3.Reports and Analysis


### Spinning Management (SPM)
Oversee spinning operations with real-time data and production planning tools.

1. Departments
2. Resources
3. Routing
4. BOM
5. Super BOM

### Land Management (LM)
Keep records of assets, properties, and land-related data for streamlined administrative control.

1. Assets
2. Liabilities
3. Properties
4. Resources
5. Standard Cost
7. some parts of this section is private for company purpose

### Dashboard & Setup: 
Gain actionable insights through dynamic dashboards and configure your system to fit your business processes.
1.Company Setup
    * User Accounts Setup
    * Access Setup
    * User Rights Setup
    * Location Access Setup
    * Category Access Setup
    * Supplier Access Setup
    * Dimension Access Setup
    * Department Access Setup
    * Device Access Panel

2.Miscellaneous
    * Payment Terms
    * Shipping Company
    * Vehicle Info
    * Dashboard Setup
    * Reminder Setup
    * Points of Sale
    * Printers
    * Contact Categories
    * User Activity

3.Taxes
           
   * Item Tax Types
   * System and General GL Setup
   * Fiscal Years
   * Print Profiles
   * Access user list
4.Tax Groups
5.Forms Setup
6.Display Setup
7.Maintenance
   * Default Store Location Setup
   * Employee Setup
   * Add And Manage Shift
   * Production Hold Reason
   * Void a Transaction
   * Void a Transaction(New)
   * View or Print Transactions
   * Attach Documents
   * Attach File
   * Approver Setup
   * Footer Setup
   * Back Date Time Setup for Transactions
   * Backup and Restore
   * Create/Update Companies
   * Install/Update Languages
   * Install/Activate Extensions
   * Install/Activate Themes
   * Install/Activate Chart of Accounts
   * Software Upgrade
   * Report Generator
    
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
    



## Modules Under Development
------------
1. Project System
2. HelpDesk


## Dynamic pull System
------------
The idea behind inoERP is to provide a dynamic pull-based system where the demand /supply changes frequently and traditional planning systems (such as MRP or Kanban) are incompetent to provide a good inventory turn.

A dynamic pull system is an advanced version of a pull system that encompasses the best feature of the traditional pull system & MRP. The major disadvantage of the conventional Kanban system is the fixed Kanban size and requirement of at least two bins for the entire operation. In a sudden demand decrease, the Kanban system can result in extra inventory, and the value of unused inventory can go up to 2 bin size. Similarly, In case of unexpected demand increases can result in a line down, and the issue will be severe if the lead times are not short.

The dynamic pull system overcomes this issue by recalculating the bucket size (Kanban size/lot size) before creating any supply (requisitions/purchase order/work order). Each time a new supply is created, the system automatically decides the best supply size per the actual demand.

> *The old PHP version of inoERP is available @ https://github.com/php-inoerp/inoERP*
