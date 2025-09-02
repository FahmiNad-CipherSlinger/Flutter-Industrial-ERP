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
    
### Human Resource Management(HRM)

Manage employees, payroll, attendance, and performance from a centralized module.This is the most important of this industrial Project.
1.Transactions
    * Employee Information Entry
    * Employee Information
    * Bangla Employee Informaton
    * Employee Explorer
    * Increment And Promotion Explorer
    * Resign Explorer
    * Employee inactive Explorer
    * Employee Salary Structure
    * Employee Extra Salary
    * Extra Salary Deduction Entry
    * Salary Basic Info
    * Extra Salary Info
    * Salary Process Month
    * Rollback Process Month
    * Salary Editor
    * JV Salary Process Month
    * JV Settlement
    * Employee Info Upload
    * Partial to Advance Salary
    * Re-Partial to Advance Salary
    * Advance Salary Upload
    * Leave Information Upload
    * Upload CV
    * Salary Unlock
    * Bonus Salary Backup
    * Opening Earning Leave Upload
    * Gazetted Salary Process
    * Employee ID Card
    * Leave Application Form
    * Early Leave Application Form
    * Resignation Application Form
    * Loan Application Form
    * Loan Installment Postponing Application Form
    * Loan Exceptions
    * Advance Salary Application Form
    * Employee Evaluation Form
    * Employee Increment And Promotion Form
    * Multiple Employee Increment And Promotion Form
    * Daily OT Payment
    * Advance EPD Payment
    * Single Employee OT Approve
    * Date Wise Employee OT Approve
    * Piece Information
    * Employee Running shift
    * Employee Running shift Correction
    * Turn holiday to absent
    * Turn holiday to absent Correction
    * Salary Held Up
    * Letter Explorer
    * Salary Acknowledgment
    * Bonus Process
    * Bonus Salary Held Up
2. Employee Attendance
	* Employee Attendance For Head Office
	* Employee Attendance Nz Head Office
	* Employee Attendance Nz Factory
	* Employee Attendance For RS
	* Manual Attendance Entry
	* Manual Attendance Entry (Multiple)
	* Manual Attendance Entry by Department(Multiple)
	* Manual Attendance Entry by Dimension(Multiple)
	* Manual Attendance Entry Special(Multiple)
	* Absent to Attendance List
	* Selective Attendance List Show
	* Single Employee Attendance Correction Form
	* Date Wise Employee Attendance Correction Form
	* Remove Unwanted Attendance
	* Modify Attendance
	* Data Synchronization
	* Compensation Leave Explorer
	* All Employee Monthly Summary
	* All Employee Monthly Summary Information
	* Summary of Daily Man Power Attendance Report
	* Single Employee Monthly Summary
	* Single Employee Monthly Summary NC
	* Attendance List
	* Show Attendance List
	* Employee Attendance List
	* Compensation Leave
	* Absent List
	* Individual Job Card
	* Individual Attendance History
	* All job cards
	* All job cards Report
 3.Inquiries and Reports
  	* Employee Job Info Approval
    * Job Approval Explorer
    * Employee Remaining Leave Inquiry
    * Monthly Leave summary
    * Leave Approve Inquiry
    * Resignation Approve Inquiry
    * Leave Explorer
    * Holiday to Absent Explorer
    * Over Time Explorer
    * Loan Approve Inquiry
    * Loan Installment Postponing Approve Inquiry
    * Loan Explorer
    * Loan Installment Change Explorer
    * Loan Exceptions Inquiry
    * Loan Postpond Explorer
    * Advance Salary Approve Inquiry
    * Increment And Promotion Inquiry
    * OT Payment Explorer
	* Advance Salary Explorer
 	* Increment And Promotion Approval
    * Bonus Salary Explorer
    * Multiple Employee Increment And Promotion Inquiry
    * Multiple Increment And Promotion Approval
    * Salary Lock Explorer
    * Late Attendance List
    * Food Information
    * Tax Information
    * Tax Challan
    * Top 50 Early Leave
    * Less Work Explorer
    * Employee Running shift Inquiry
    * Salary Held Up Inquiry
    * Re-Joining Approve Inquiry
    * Last Increment Inquiry
    * Earn Leave Balance
    * Mobile bill Explorer
    * Salary Sheet View
    * Salary Summary
    * ALL Unit Salary Summary
    * Bonus Summary
    * Bonus Summary All Unit
    * Bonus Fund Requirement All Unit
    * Salary Sheet View Garments
    * Overtime Sheet
    * Extra Overtime Sheet
    * Holiday Overtime Sheet
    * Night Over Time Sheet
    * Tiffin Sheet
    * Fund Requirement
   	* New Fund Requirement
    * All Unit Fund Requirement
    * Proposed Increment Summary
    * Gazetted Salary Summary
    * Cash Salary
    * Cash Salary All Unit
    * Salary/Wage Summary
    * Salary Sheet Summary
    * Salary Sheet Summary Comparison
    * Salary Sheet Summary(OT)
    * Monthly Salary Forms
    * Challan Bangla
    * Salary Sheet
    * Real Time Salary Sheet Summary
    * Real Time OT Summary
    * Pay Slip Generation
    * Pay Slip Generation Bangla
    * Pay Slip
    * Bank Statements
    * Monthly Salary Process Acknowledgement
    * Payroll Reports
    * Employee - Final Settlement
    * Gazetted Salary
    * Employee Status Explorer
    * Custom Reports
4. Maintenance
  	* Approver Setup
    * Attendance Type
    * Attendance Buffering Time
    * Income Tax Setup
   	*  Location
    * Nationality
    * Religion
    * Marital Status
    * Department
    * Add Site/Unit/Office/Section
    * Total Stand & Attendance per shift Setup
    * Designation Group
    * Designation
    * Grade
    * Institute Entry
    * Educational Degree
    * Major Subject
    * Bank Accounts
    * OT Setup
    * Maximum OT Setup
    * Employee Type
    * Employee Type Change
    * Late Count Setup
    * Salary Report Setup
    * Salarysheet Head Setup
    * Salarysheet Setup
    * Cash Amount
    * Mobile Bill
    * Percent Information
    * Salary Acknowledgment Setup
   	* Breakup Formula
    * Loan Type Setup
    * Stamp Setup
    * Bonus Settings
    * Attendance Bonus Setting
    * Extra Salary For Fund Requirement
    * Extra Salary Head Setting
    * Relation Type
    * Office/Shift Setup
    * Running shift Setup
    * Grade Leave Setup
    * Earnings Leave Setup
    * Special Medical Leave
    * Compensation Leave Setup
    * Gazetted Holidays
    * Weekend Setup
    * Monthly Offday Settings
    * Employee Auto Retirement Days
    * Employee Salary Calculation Setup
    * Employee Provident Fund Setup
    * Employee Gratuity Fund Setup
    * Employee Job Info Change
    * D Card Authorize Signature
    * Employee Signature Entry
    * Notice
    * Real Time Salarysheet footer Setup
    * Employee ID Change
    * Leave Year Setup
    * Salarysheet Summary Head Setup
    * Report Formating
    * Report Maping
5. Employee Self Service
  	* Personal Information
    * My Monthly Summary
    * My Leave Information
    * My Loan Information
    * My Notification



## Modules Under Development
------------
1. Project System
2. HelpDesk



