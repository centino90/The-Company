# App Requirements

## Multi-faceted System
* Financial Accounting System
    * Records & Reports of
        * Sales orders
        * Customer billing statements
        * Sales analysis reports
        * Purchase requisitions
        * Vendor invoices
        * Check registers
        * General ledger
        * Inventory data
        * Payroll information
        * Timekeeping
        * Tax information
    * Should have operations for
        * Accounts Receivable
        * Accounts Payable
        * Bank Management
        * Financial Reporting
        * Basic Revenue/Sales Recording and Tracking
    * Sales report 
        * average sales per day in a week
        * average sales per week in a month
        * average sales per month in a year
        * overall sales in a day
        * overall sales in a week
        * overall sales in a month
        * overall sales in a year
    * Profit report    
        * average profit per day in a week
        * average profit per week in a month
        * average profit per month in a year
        * overall profit in a day
        * overall profit in a week
        * overall profit in a month
        * overall profit in a year    

* Inventory Management System
    * Records of
        * Products/services produced
        * Products/services bought
    * Reports of
        * average products/services sold per day in a week
        * average products/services sold per week in a month
        * average products/services sold per month in a year
        * overall products/services sold in a day
        * overall products/services sold in a week
        * overall products/services sold in a month
        * overall products/services sold in a year    
    * Handles Manual Inventory Updates (product detail, etc)
    * Manual Insertion of new Information or Products
    * Restrict Deletion Role to Super-User/Admin only
    * Automated Deletion and Updation of records based on specific categories
        * Date
        * Cancellations
    * Heirarchical level of authority based on roles
        * Database user-levels
        * Reflected upon frontend UI
        * App restrictions based on user level

* Purchase Order System
    * Records & Reports of
        * Purchase Invoice
        

* Human Resource Management System
    * Information Records and Performance Reports of
        * Head Department Managers
        * Subordinate Department Managers
        * Supervisors
        * Team leaders
        * members

        this include:

        * Payroll report (By department, managerial, team, individual)
            * overall payroll in a month
            * overall payroll in a year
            * Timekeeping report (By department, managerial, team, individual)
                * average time contributed per day in a week
                * average time contributed per week in a month
                * average time contributed per month in a year
                * total time contributed in a week
                * total time contributed in a month
                * total time contributed in a year
        * Vendors report (By department, managerial, team, individual)
            * average sales per day in a week
            * average sales per week in a month
            * average sales per month in a year
            * total sales in a week
            * total sales in a month
            * total sales in a year

# Definitions

sources:

[List of data needed for accounting systems](https://www.investopedia.com/articles/professionaleducation/11/accounting-information-systems.asp)

[Things to consider in accounting](https://www.bluelinkerp.com/blog/2011/04/25/erp-or-accounting-software-whats-the-difference/)

## Accounting

### Sales order
A sales order is a document generated by the seller upon receiving a purchase order from a buyer specifying the details about the product or service along with price, quantity, buyer details like the shipping address, billing address, mode of payment and terms and conditions.

Things to include in a sales order form: 

* Seller Information: Sales order number, product identifying codes, company name, address, phone, customer number, salesperson, and approver (if required)
* Buyer Information: Name, address, contact information, purchase order number, and approval
* Transaction Information: Product name, quantity, unit price, extended price, subtotal, date ordered, date of delivery, shipping method, tax, delivery charges, and terms, including the method of payment and whether the balance is due or a deposit or partial payment is required

Source: https://www.smartsheet.com/sales-order-process-form

Further readings:
* https://www.godaddy.com/garage/what-to-include-in-a-purchase-order-form-for-your-ecommerce-business/
* https://blog.varstreetinc.com/what-is-a-sales-order/


### Billing statement 
The statement shows all transactions and the total invoiced to the customer for a particular date range. It also shows the amount the customer has paid and the amount outstanding at the end of the period specified.

**Customer Statements** 
* a statement can show all invoices and payments for a date range, or just the items unpaid.

There are two types of statement to choose from:

**Activity statements** show all activity for that customer within a date range. This includes all:

* Sales invoices
* Payments received
* Credit notes
* Prepayments
* Overpayments

**Outstanding statements** show only what's owed by the customer at a certain date. They don't show any transactions that have been fully paid or credited, and never show prepayments.

Source: https://central.xero.com/s/article/Customer-statements

### sales report 
or sales analysis report, gives an overview of the state of the sales activities within a company. It shows the different trends happening in the sales volume over a certain time, but also analyzes the different steps of the sales funnel and the performance of sales executives.

### Purchase requisitions 
are documents used when an employee needs to make a purchase or an order request on behalf of their company. It is a document that is used to inform department managers or the purchasing officer of the decision so that the purchasing department can start the purchasing process.

### Vendor invoices
 are requests for received payment for products and services. Vendor invoices might represent a bill for ongoing services, or they can be based on purchase orders for specific items and services. A supplier prepares and issues an invoice when a customer orders goods and services on credit. Vendor invoices include the amounts owed, sales taxes, freight and delivery charges, the date by which the payment should be made, and where to send the payment.

### check register
or cash disbursements journal, is where you record all of the check and cash transactions your business has during an accounting period. Businesses use a check register to calculate a running balance of their checking account. 
[Check Register Source](https://www.patriotsoftware.com/blog/accounting/what-is-a-check-register/)

A cash disbursements journal usually has columns that help you organize and break down transaction information. Typically, the parts of a check register include the following:

Date of transaction

Check number or category (e.g., electric bill)

Description or notes

Debits and credits associated with the transaction

Account balance

### General Ledger
 is an account or record used to sort, store and summarize a company's transactions. These accounts are arranged in the general ledger (and in the chart of accounts) with the balance sheet accounts appearing first followed by the income statement accounts.

**Examples of General Ledger Accounts**

Some of the more common balance sheet accounts and how they are further arranged in the general ledger include:

* asset accounts such as Cash, Accounts Receivable, Inventory, Investments, Land, and Equipment
* liability accounts including Notes Payable, Accounts Payable, Accrued Expenses Payable, and Customer Deposits
* stockholders' equity accounts such as Common Stock, Retained Earnings, Treasury Stock, and Accumulated Other Comprehensive Income

Some of the general ledger income statement accounts and how they are arranged include:

* operating revenue accounts such as Sales and Service Fee Revenues
* operating expense accounts including Salaries Expense, Rent * Expense, and Advertising Expense
* nonoperating or other income accounts such as Gain on Sale of Assets, Interest Expense, and Loss on Disposal of Assets

Sources:

[General Ledger Account](https://www.accountingcoach.com/blog/what-is-a-general-ledger-account)

### Inventory Data

Inventory data such as records and reports of products and services' details, etc.

**Inventory Data Entry dialog** is where you view and edit the database record for a single inventory item. It appears when you open a record in the Inventory data list.
Sources:

[Inventory data entry](https://www.secureclub.net/Help/acm/UG/ug_Inv_data.htm)

### Payroll Information

As a core function of your business, payroll amasses different types of information. All of this data ties into your relationship with your employees from a compensation standpoint. This includes wages, taxes and deductions, employee benefits and general policies.

**Individual Records**

An employee’s payroll record shows her personal data, such as address, Social Security number and birth date, and her wage and financial information, including hourly pay rate or salary, bank account data for direct deposit, basis for withholding income tax such as a W-4 form, available benefit days such as vacation and sick time and other benefits such as health and life insurance and 401(k) contribution amounts. Access to this data should be restricted to the relevant payroll personnel. If you provide your employees with a self-service system, they may view their paycheck information and make specific changes to their payroll record online.

**Paycheck Stubs**

A pay stub breaks down the employee’s gross-to-net wages for the pay period. It may include gross wages or salary, hourly pay rate, overtime rate and wages, piece work compensation, mandatory deductions, voluntary deductions, additional types of pay -- such as commission, bonus or severance -- and year-to-date wages and deductions. Pay stub abbreviations vary by employer; however, they should be applied in a consistent manner.

**Employee Tax Reporting**

You must pay and report the taxes you withhold from your employees’ paychecks to the federal and applicable state and local governments. You use specific forms to file your reports, which you must maintain for at least four years, according to the Internal Revenue Service. For example, you may be required to file quarterly reports on Form 941 or annual reports on Form 944 with the IRS to report your employees’ federal withholding. Your state or local government has its own form requirements for reporting state and local withholding. You also must file annual W-2s with the Social Security Administration and give the employee a copy to file with her federal tax return. All of these documents include key information about your employees’ withholding.

**Employer Liabilities**

You share the employee’s burden in paying Social Security and Medicare taxes, and, depending on IRS requirements, you report your share with the employees’ portion on either Form 941 or Form 944. You also have other mandatory obligations that your employees do not have, such as federal unemployment tax and, in most cases, state unemployment tax. These liabilities require different forms, on which you include your employees’ wages and your liabilities.

**Internal Policies**

Internal payroll policies may apply strictly to your payroll employees, to managers and supervisors or to your staff as a whole. For example, restrict information regarding to whom you disclose payroll information and procedures for payroll processing to your payroll department. Policies on time card completion, how to enroll in the company’s benefit plans and what to expect on payday apply to all employees. Procedures on time card approval and employee time off for vacation or personal days apply to your managers and supervisors.

**Considerations**

Under the Fair Labor Standards Act, you must keep payroll records for at least three years. This includes the time and day the employee's workweek starts, hours worked each day and week, daily or weekly regular wages and weekly overtime wages. The FLSA requires that you keep documents on which wage calculations are based -- such as time cards and work schedules -- for at least two years.

Sources:

[things to consideer when creating a payroll](https://smallbusiness.chron.com/kinds-payroll-information-59833.html)


### Timekeeping
Time-keeping is concerned with the recording of time of workers for the purpose of attendance and wage calculations whereas time booking is the reporting of each worker's time for each department, operation and job for the purposes of cost analysis and apportionment of labour costs between various jobs and departments.

### Tax information
Tax accounting is a structure of accounting methods focused on taxes rather than the appearance of public financial statements. Tax accounting is governed by the Internal Revenue Code, which dictates the specific rules that companies and individuals must follow when preparing their tax returns.

## Things that are also Important to consider:
- Accounts Receivable
- Accounts Payable
- Bank Management
- Financial Reporting
- Basic Revenue/Sales Recording and Tracking 
- 
- Purchase Orders
- Customer Invoice