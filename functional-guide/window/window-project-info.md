
Project Info
# Project Info


Document Information of Project

Window Type
### Window Type

**Query Only**

```
The Sales Transaction checkbox indicates if this item is a Sales Transaction.
```

Tabs
## Tabs


Project
### Project

**Description**
 *Data Project*
**Help**
 *The Project Tab is used to define the Value, Name and Description for each project.  It also is defines the tracks the amounts assigned to, committed to and used for this project. Note that when the project Type is changed, the Phases and Tasks are re-created.*

```
The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.
```
Fields
## Fields


Client
### Client

**Description**
 *Client/Tenant for this installation.*
**Help**
 *A Client is a company or a legal entity. You cannot share data between Clients. Tenant is a synonym for Client.*

Organization
### Organization

**Description**
 *Organizational entity within client*
**Help**
 *An organization is a unit of your client or legal entity - examples are store, department. You can share data between organizations.*

Search Key
### Search Key

**Description**
 *Search key for the record in the format required - must be unique*
**Help**
 *A search key allows you a fast method of finding a particular record.
If you leave the search key empty, the system automatically creates a numeric number.  The document sequence used for this fallback number is defined in the "Maintain Sequence" window with the name "DocumentNo_<TableName>", where TableName is the actual name of the table (e.g. C_Order).*

Summary Level
### Summary Level

**Description**
 *This is a summary entity*
**Help**
 *A summary entity represents a branch in a tree rather than an end-node. Summary entities are used for reporting and do not have own values.*

Name
### Name

**Description**
 *Alphanumeric identifier of the entity*
**Help**
 *The name of an entity (record) is used as an default search option in addition to the search key. The name is up to 60 characters in length.*

Description
### Description

**Description**
 *Optional short description of the record*
**Help**
 *A description is limited to 255 characters.*

Active
### Active

**Description**
 *The record is active in the system*
**Help**
 *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*

Project Manager
### Project Manager

**Description**
 *Project Manager*
**Help**
 *A project manager is a professional in the field of project management. Project managers have the responsibility of the planning, procurement and execution of a project, in any domain of engineering*

Note
### Note

**Description**
 *Optional additional user defined information*
**Help**
 *The Note field allows for optional entry of user defined information regarding this record*

Set Project Type
### Set Project Type

**Description**
 *Set Project Type and for Service Projects copy Phases and Tasks of Project Type into Project*
**Help**
 **

Standard Phase
### Standard Phase

**Description**
 *Standard Phase of the Project Type*
**Help**
 *Phase of the project with standard performance information with standard work*

Project Category
### Project Category

**Description**
 *Project Category*

Project Class
### Project Class

**Description**
 *Project Class*

Project Group
### Project Group

**Description**
 *Project Group*

System Color
### System Color

**Description**
 *Color for backgrounds or indicators*

Project Status
### Project Status

**Description**
 *Status for Project, Phase or Task*

Priority
### Priority

**Description**
 *Priority of a document*
**Help**
 *The Priority indicates the importance (high, medium, low) of this document*

Start Schedule
### Start Schedule

**Description**
 *Scheduled start date for this Order*

Finish Schedule
### Finish Schedule

**Description**
 *Scheduled Finish date for this Order*

Date Start
### Date Start

**Description**
 *Date Start for this Order*

Finish Date
### Finish Date

**Description**
 *Finish or (planned) completion date*
**Help**
 *The finish date is used to indicate when the project is expected to be completed or has been completed.*

Deadline
### Deadline

**Description**
 *Deadline*
**Help**
 *The latest time or date by which something should be completed.*

Indefinite
### Indefinite

**Description**
 *Indefinite*
**Help**
 *lasting for an unknown or unstated length of time.*

Contract Date
### Contract Date

**Description**
 *The (planned) effective date of this document.*
**Help**
 *The contract date is used to determine when the document becomes effective. This is usually the contract date.  The contract date is used in reports and report parameters.*

Duration Unit
### Duration Unit

**Description**
 *Unit of Duration*
**Help**
 *Unit to define the length of time for the execution*

Business Partner
### Business Partner

**Description**
 *Identifies a Business Partner*
**Help**
 *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*

BPartner (Agent)
### BPartner (Agent)

**Description**
 *Business Partner (Agent or Sales Rep)*

Partner Location
### Partner Location

**Description**
 *Identifies the (ship to) address for this Business Partner*
**Help**
 *The Partner address indicates the location of a Business Partner*

Contact
### Contact

**Description**
 *User within the system - Internal or Business Partner Contact*
**Help**
 *The User identifies a unique user in the system. This could be an internal user or a business partner contact*

Payment Term
### Payment Term

**Description**
 *The terms of Payment (timing, discount)*
**Help**
 *Payment Terms identify the method and timing of payment.*

Order Reference
### Order Reference

**Description**
 *Transaction Reference Number (Sales Order, Purchase Order) of your Business Partner*
**Help**
 *The business partner order reference is the order reference for this specific transaction; Often Purchase Order numbers are given to print on Invoices for easier reference.  A standard number can be defined in the Business Partner (Customer) window.*

Sales Representative
### Sales Representative

**Description**
 *Sales Representative or Company Agent*
**Help**
 *The Sales Representative indicates the Sales Rep for this Region.  Any Sales Rep must be a valid internal user.*

Warehouse
### Warehouse

**Description**
 *Storage Warehouse and Service Point*
**Help**
 *The Warehouse identifies a unique Warehouse where products are stored or Services are provided.*

Activity
### Activity

**Description**
 *Business Activity*
**Help**
 *Activities indicate tasks that are performed and used to utilize Activity based Costing*

Campaign
### Campaign

**Description**
 *Marketing Campaign*
**Help**
 *The Campaign defines a unique marketing program.  Projects can be associated with a pre defined Marketing Campaign.  You can then report based on a specific Campaign.*

Trx Organization
### Trx Organization

**Description**
 *Performing or initiating organization*
**Help**
 *The organization which performs or initiates this transaction (for another organization).  The owning Organization may not be the transaction organization in a service bureau environment, with centralized services, and inter-organization transactions.*

User List 1
### User List 1

**Description**
 *User defined list element #1*
**Help**
 *The user defined element displays the optional elements that have been defined for this account combination.*

User List 2
### User List 2

**Description**
 *User defined list element #2*
**Help**
 *The user defined element displays the optional elements that have been defined for this account combination.*

User List 3
### User List 3

**Description**
 *User defined list element #3*
**Help**
 *The user defined element displays the optional elements that have been defined for this account combination.*

User List 4
### User List 4

**Description**
 *User defined list element #4*
**Help**
 *The user defined element displays the optional elements that have been defined for this account combination.*

Price List Version
### Price List Version

**Description**
 *Identifies a unique instance of a Price List*
**Help**
 *Each Price List can have multiple versions.  The most common use is to indicate the dates that a Price List is valid for.*

Currency
### Currency

**Description**
 *The Currency for this record*
**Help**
 *Indicates the Currency to be used when processing or reporting on this record*

Planned Amount
### Planned Amount

**Description**
 *Planned amount for this project*
**Help**
 *The Planned Amount indicates the anticipated amount for this project or project line.*

Planned Quantity
### Planned Quantity

**Description**
 *Planned quantity for this project*
**Help**
 *The Planned Quantity indicates the anticipated quantity for this project or project line*

Planned Margin
### Planned Margin

**Description**
 *Project's planned margin amount*
**Help**
 *The Planned Margin Amount indicates the anticipated margin amount for this project or project line.*

Invoice Rule
### Invoice Rule

**Description**
 *Invoice Rule for the project*
**Help**
 *The Invoice Rule for the project determines how orders (and consequently invoices) are created.  The selection on project level can be overwritten on Phase or Task*

Committed Amount
### Committed Amount

**Description**
 *The (legal) commitment amount*
**Help**
 *The commitment amount is independent from the planned amount. You would use the planned amount for your realistic estimation, which might be higher or lower than the commitment amount.*

Committed Quantity
### Committed Quantity

**Description**
 *The (legal) commitment Quantity*
**Help**
 *The commitment amount is independent from the planned amount. You would use the planned amount for your realistic estimation, which might be higher or lower than the commitment amount.*

Invoiced Amount
### Invoiced Amount

**Description**
 *The amount invoiced*
**Help**
 *The amount invoiced*

Quantity Invoiced
### Quantity Invoiced

**Description**
 *The quantity invoiced*

Project Balance
### Project Balance

**Description**
 *Total Project Balance*
**Help**
 *The project balance is the sum of all invoices and payments*

Members
### Members

**Description**
 *Project Members*
**Help**
 *Project Member*

Fields
## Fields


Client
### Client

**Description**
 *Client/Tenant for this installation.*
**Help**
 *A Client is a company or a legal entity. You cannot share data between Clients. Tenant is a synonym for Client.*

Organization
### Organization

**Description**
 *Organizational entity within client*
**Help**
 *An organization is a unit of your client or legal entity - examples are store, department. You can share data between organizations.*

Project Member
### Project Member

**Description**
 *Project Members*
**Help**
 *The User identifies a unique user in the system. This could be an internal user or a business partner contact*

BP Name
### BP Name


Project Member Type
### Project Member Type

**Description**
 *Define the Member Type for a Project*

Notification Type
### Notification Type

**Description**
 *Type of Notifications*
**Help**
 *Emails or Notification sent out for Request Updates, etc.*

Active
### Active

**Description**
 *The record is active in the system*
**Help**
 *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*

Opportunities
### Opportunities

**Description**
 *Opportunities*

Fields
## Fields


Client
### Client

**Description**
 *Client/Tenant for this installation.*
**Help**
 *A Client is a company or a legal entity. You cannot share data between Clients. Tenant is a synonym for Client.*

Organization
### Organization

**Description**
 *Organizational entity within client*
**Help**
 *An organization is a unit of your client or legal entity - examples are store, department. You can share data between organizations.*

Sales Opportunity
### Sales Opportunity


Document No
### Document No

**Description**
 *Document sequence number of the document*
**Help**
 *The document number is usually automatically generated by the system and determined by the document type of the document. If the document is not saved, the preliminary number is displayed in "<>".

If the document type of your document has no automatic document sequence defined, the field is empty if you create a new document. This is for documents which usually have an external number (like vendor invoice).  If you leave the field empty, the system will generate a document number for you. The document sequence used for this fallback number is defined in the "Maintain Sequence" window with the name "DocumentNo_<TableName>", where TableName is the actual name of the table (e.g. C_Order).*

Business Partner
### Business Partner

**Description**
 *Identifies a Business Partner*
**Help**
 *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*

User/Contact
### User/Contact

**Description**
 *User within the system - Internal or Business Partner Contact*
**Help**
 *The User identifies a unique user in the system. This could be an internal user or a business partner contact*

Campaign
### Campaign

**Description**
 *Marketing Campaign*
**Help**
 *The Campaign defines a unique marketing program.  Projects can be associated with a pre defined Marketing Campaign.  You can then report based on a specific Campaign.*

Sales Representative
### Sales Representative

**Description**
 *Sales Representative or Company Agent*
**Help**
 *The Sales Representative indicates the Sales Rep for this Region.  Any Sales Rep must be a valid internal user.*

Sales Stage
### Sales Stage

**Description**
 *Stages of the sales process*
**Help**
 *Define what stages your sales process will move through*

Probability
### Probability


Expected Close Date
### Expected Close Date

**Description**
 *Expected Close Date*
**Help**
 *The Expected Close Date indicates the expected last or final date*

Opportunity Amount
### Opportunity Amount

**Description**
 *The estimated value of this opportunity.*

Weighted Amount
### Weighted Amount

**Description**
 *The amount adjusted by the probability.*

Currency
### Currency

**Description**
 *The Currency for this record*
**Help**
 *Indicates the Currency to be used when processing or reporting on this record*

Description
### Description

**Description**
 *Optional short description of the record*
**Help**
 *A description is limited to 255 characters.*

Comments
### Comments

**Description**
 *Comments or additional information*
**Help**
 *The Comments field allows for free form entry of additional information.*

Order
### Order

**Description**
 *Order*
**Help**
 *The Order is a control document.  The  Order is complete when the quantity ordered is the same as the quantity shipped and invoiced.  When you close an order, unshipped (backordered) quantities are cancelled.*

Project
### Project

**Description**
 *Financial Project*
**Help**
 *A Project allows you to track and control internal or external activities.*

Close Date
### Close Date

**Description**
 *Close Date*
**Help**
 *The Close Date indicates the last or final date*

Cost
### Cost

**Description**
 *Cost information*

Orders
### Orders

**Description**
 *Orders*

Fields
## Fields


Client
### Client

**Description**
 *Client/Tenant for this installation.*
**Help**
 *A Client is a company or a legal entity. You cannot share data between Clients. Tenant is a synonym for Client.*

Organization
### Organization

**Description**
 *Organizational entity within client*
**Help**
 *An organization is a unit of your client or legal entity - examples are store, department. You can share data between organizations.*

Order
### Order

**Description**
 *Order*
**Help**
 *The Order is a control document.  The  Order is complete when the quantity ordered is the same as the quantity shipped and invoiced.  When you close an order, unshipped (backordered) quantities are cancelled.*

Document No
### Document No

**Description**
 *Document sequence number of the document*
**Help**
 *The document number is usually automatically generated by the system and determined by the document type of the document. If the document is not saved, the preliminary number is displayed in "<>".

If the document type of your document has no automatic document sequence defined, the field is empty if you create a new document. This is for documents which usually have an external number (like vendor invoice).  If you leave the field empty, the system will generate a document number for you. The document sequence used for this fallback number is defined in the "Maintain Sequence" window with the name "DocumentNo_<TableName>", where TableName is the actual name of the table (e.g. C_Order).*

Description
### Description

**Description**
 *Optional short description of the record*
**Help**
 *A description is limited to 255 characters.*

Document Type
### Document Type

**Description**
 *Document type or rules*
**Help**
 *The Document Type determines document sequence and processing rules*

Document Status
### Document Status

**Description**
 *The current status of the document*
**Help**
 *The Document Status indicates the status of a document at this time.  If you want to change the document status, use the Document Action field*

Date Ordered
### Date Ordered

**Description**
 *Date of Order*
**Help**
 *Indicates the Date an item was ordered.*

Account Date
### Account Date

**Description**
 *Accounting Date*
**Help**
 *The Accounting Date indicates the date to be used on the General Ledger account entries generated from this document. It is also used for any currency conversion.*

Date Promised
### Date Promised

**Description**
 *Date Order was promised*
**Help**
 *The Date Promised indicates the date, if any, that an Order was promised for.*

Date printed
### Date printed

**Description**
 *Date the document was printed.*
**Help**
 *Indicates the Date that a document was printed.*

Business Partner
### Business Partner

**Description**
 *Identifies a Business Partner*
**Help**
 *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*

Invoice Partner
### Invoice Partner

**Description**
 *Business Partner to be invoiced*
**Help**
 *If empty the shipment business partner will be invoiced*

Partner Location
### Partner Location

**Description**
 *Identifies the (ship to) address for this Business Partner*
**Help**
 *The Partner address indicates the location of a Business Partner*

Invoice Location
### Invoice Location

**Description**
 *Business Partner Location for invoicing*

Delivery Rule
### Delivery Rule

**Description**
 *Defines the timing of Delivery*
**Help**
 *The Delivery Rule indicates when an order should be delivered. For example should the order be delivered when the entire order is complete, when a line is complete or as the products become available.*

Priority
### Priority

**Description**
 *Priority of a document*
**Help**
 *The Priority indicates the importance (high, medium, low) of this document*

Warehouse
### Warehouse

**Description**
 *Storage Warehouse and Service Point*
**Help**
 *The Warehouse identifies a unique Warehouse where products are stored or Services are provided.*

Drop Shipment
### Drop Shipment

**Description**
 *Drop Shipments are sent from the Vendor directly to the Customer*
**Help**
 *Drop Shipments do not cause any Inventory reservations or movements as the Shipment is from the Vendor's inventory. The Shipment of the Vendor to the Customer must be confirmed.*

Invoice Rule
### Invoice Rule

**Description**
 *Frequency and method of invoicing*
**Help**
 *The Invoice Rule defines how a Business Partner is invoiced and the frequency of invoicing.*

Sales Representative
### Sales Representative

**Description**
 *Sales Representative or Company Agent*
**Help**
 *The Sales Representative indicates the Sales Rep for this Region.  Any Sales Rep must be a valid internal user.*

Price List
### Price List

**Description**
 *Unique identifier of a Price List*
**Help**
 *Price Lists are used to determine the pricing, margin and cost of items purchased or sold.*

Currency
### Currency

**Description**
 *The Currency for this record*
**Help**
 *Indicates the Currency to be used when processing or reporting on this record*

Sales Transaction
### Sales Transaction

**Description**
 *This is a Sales Transaction*
**Help**
 *The Sales Transaction checkbox indicates if this item is a Sales Transaction.*

Self-Service
### Self-Service

**Description**
 *This is a Self-Service entry or this entry can be changed via Self-Service*
**Help**
 *Self-Service allows users to enter data or update their data.  The flag indicates, that this record was entered or created via Self-Service or that the user can change it via the Self-Service functionality.*

Payment Rule
### Payment Rule

**Description**
 *How you pay the invoice*
**Help**
 *The Payment Rule indicates the method of invoice payment.*

Payment Term
### Payment Term

**Description**
 *The terms of Payment (timing, discount)*
**Help**
 *Payment Terms identify the method and timing of payment.*

Project
### Project

**Description**
 *Financial Project*
**Help**
 *A Project allows you to track and control internal or external activities.*

Campaign
### Campaign

**Description**
 *Marketing Campaign*
**Help**
 *The Campaign defines a unique marketing program.  Projects can be associated with a pre defined Marketing Campaign.  You can then report based on a specific Campaign.*

Total Lines
### Total Lines

**Description**
 *Total of all document lines*
**Help**
 *The Total amount displays the total of all lines in document currency*

Grand Total
### Grand Total

**Description**
 *Total amount of document*
**Help**
 *The Grand Total displays the total amount including Tax and Freight in document currency*

Shipments/Receipts
### Shipments/Receipts

**Description**
 *Shipments/Receipts*

Fields
## Fields


Client
### Client

**Description**
 *Client/Tenant for this installation.*
**Help**
 *A Client is a company or a legal entity. You cannot share data between Clients. Tenant is a synonym for Client.*

Organization
### Organization

**Description**
 *Organizational entity within client*
**Help**
 *An organization is a unit of your client or legal entity - examples are store, department. You can share data between organizations.*

Shipment/Receipt
### Shipment/Receipt

**Description**
 *Material Shipment Document*
**Help**
 *The Material Shipment / Receipt*

Project
### Project

**Description**
 *Financial Project*
**Help**
 *A Project allows you to track and control internal or external activities.*

Ship Date
### Ship Date

**Description**
 *Shipment Date/Time*
**Help**
 *Actual Date/Time of Shipment (pick up)*

Account Date
### Account Date

**Description**
 *Accounting Date*
**Help**
 *The Accounting Date indicates the date to be used on the General Ledger account entries generated from this document. It is also used for any currency conversion.*

Date Ordered
### Date Ordered

**Description**
 *Date of Order*
**Help**
 *Indicates the Date an item was ordered.*

Pick Date
### Pick Date

**Description**
 *Date/Time when picked for Shipment*

Date received
### Date received

**Description**
 *Date a product was received*
**Help**
 *The Date Received indicates the date that product was received.*

Date printed
### Date printed

**Description**
 *Date the document was printed.*
**Help**
 *Indicates the Date that a document was printed.*

Document Type
### Document Type

**Description**
 *Document type or rules*
**Help**
 *The Document Type determines document sequence and processing rules*

Document No
### Document No

**Description**
 *Document sequence number of the document*
**Help**
 *The document number is usually automatically generated by the system and determined by the document type of the document. If the document is not saved, the preliminary number is displayed in "<>".

If the document type of your document has no automatic document sequence defined, the field is empty if you create a new document. This is for documents which usually have an external number (like vendor invoice).  If you leave the field empty, the system will generate a document number for you. The document sequence used for this fallback number is defined in the "Maintain Sequence" window with the name "DocumentNo_<TableName>", where TableName is the actual name of the table (e.g. C_Order).*

Document Status
### Document Status

**Description**
 *The current status of the document*
**Help**
 *The Document Status indicates the status of a document at this time.  If you want to change the document status, use the Document Action field*

Movement Type
### Movement Type

**Description**
 *Method of moving the inventory*
**Help**
 *The Movement Type indicates the type of movement (in, out, to production, etc)*

Movement Date
### Movement Date

**Description**
 *Date a product was moved in or out of inventory*
**Help**
 *The Movement Date indicates the date that a product moved in or out of inventory.  This is the result of a shipment, receipt or inventory movement.*

Sales Representative
### Sales Representative

**Description**
 *Sales Representative or Company Agent*
**Help**
 *The Sales Representative indicates the Sales Rep for this Region.  Any Sales Rep must be a valid internal user.*

Business Partner
### Business Partner

**Description**
 *Identifies a Business Partner*
**Help**
 *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*

Partner Location
### Partner Location

**Description**
 *Identifies the (ship to) address for this Business Partner*
**Help**
 *The Partner address indicates the location of a Business Partner*

User/Contact
### User/Contact

**Description**
 *User within the system - Internal or Business Partner Contact*
**Help**
 *The User identifies a unique user in the system. This could be an internal user or a business partner contact*

Priority
### Priority

**Description**
 *Priority of a document*
**Help**
 *The Priority indicates the importance (high, medium, low) of this document*

Description
### Description

**Description**
 *Optional short description of the record*
**Help**
 *A description is limited to 255 characters.*

Warehouse
### Warehouse

**Description**
 *Storage Warehouse and Service Point*
**Help**
 *The Warehouse identifies a unique Warehouse where products are stored or Services are provided.*

In Transit
### In Transit

**Description**
 *Movement is in transit*
**Help**
 *Material Movement is in transit - shipped, but not received.
The transaction is completed, if confirmed.*

Sales Transaction
### Sales Transaction

**Description**
 *This is a Sales Transaction*
**Help**
 *The Sales Transaction checkbox indicates if this item is a Sales Transaction.*

In Dispute
### In Dispute

**Description**
 *Document is in dispute*
**Help**
 *The document is in dispute. Use Requests to track details.*

Delivery Rule
### Delivery Rule

**Description**
 *Defines the timing of Delivery*
**Help**
 *The Delivery Rule indicates when an order should be delivered. For example should the order be delivered when the entire order is complete, when a line is complete or as the products become available.*

Delivery Via
### Delivery Via

**Description**
 *How the order will be delivered*
**Help**
 *The Delivery Via indicates how the products should be delivered. For example, will the order be picked up or shipped.*

Order
### Order

**Description**
 *Order*
**Help**
 *The Order is a control document.  The  Order is complete when the quantity ordered is the same as the quantity shipped and invoiced.  When you close an order, unshipped (backordered) quantities are cancelled.*

Order Reference
### Order Reference

**Description**
 *Transaction Reference Number (Sales Order, Purchase Order) of your Business Partner*
**Help**
 *The business partner order reference is the order reference for this specific transaction; Often Purchase Order numbers are given to print on Invoices for easier reference.  A standard number can be defined in the Business Partner (Customer) window.*

Shipper
### Shipper

**Description**
 *Method or manner of product delivery*
**Help**
 *The Shipper indicates the method of delivering product*

Tracking No
### Tracking No

**Description**
 *Number to track the shipment*

Trx Organization
### Trx Organization

**Description**
 *Performing or initiating organization*
**Help**
 *The organization which performs or initiates this transaction (for another organization).  The owning Organization may not be the transaction organization in a service bureau environment, with centralized services, and inter-organization transactions.*

Campaign
### Campaign

**Description**
 *Marketing Campaign*
**Help**
 *The Campaign defines a unique marketing program.  Projects can be associated with a pre defined Marketing Campaign.  You can then report based on a specific Campaign.*

User List 1
### User List 1

**Description**
 *User defined list element #1*
**Help**
 *The user defined element displays the optional elements that have been defined for this account combination.*

User List 2
### User List 2

**Description**
 *User defined list element #2*
**Help**
 *The user defined element displays the optional elements that have been defined for this account combination.*

User List 3
### User List 3

**Description**
 *User defined list element #3*
**Help**
 *The user defined element displays the optional elements that have been defined for this account combination.*

User List 4
### User List 4

**Description**
 *User defined list element #4*
**Help**
 *The user defined element displays the optional elements that have been defined for this account combination.*

Posted
### Posted

**Description**
 *Posting status*
**Help**
 *The Posted field indicates the status of the Generation of General Ledger Accounting Lines*

Invoices
### Invoices

**Description**
 *Invoices*

Fields
## Fields


Client
### Client

**Description**
 *Client/Tenant for this installation.*
**Help**
 *A Client is a company or a legal entity. You cannot share data between Clients. Tenant is a synonym for Client.*

Organization
### Organization

**Description**
 *Organizational entity within client*
**Help**
 *An organization is a unit of your client or legal entity - examples are store, department. You can share data between organizations.*

Invoice
### Invoice

**Description**
 *Invoice Identifier*
**Help**
 *The Invoice Document.*

Document No
### Document No

**Description**
 *Document sequence number of the document*
**Help**
 *The document number is usually automatically generated by the system and determined by the document type of the document. If the document is not saved, the preliminary number is displayed in "<>".

If the document type of your document has no automatic document sequence defined, the field is empty if you create a new document. This is for documents which usually have an external number (like vendor invoice).  If you leave the field empty, the system will generate a document number for you. The document sequence used for this fallback number is defined in the "Maintain Sequence" window with the name "DocumentNo_<TableName>", where TableName is the actual name of the table (e.g. C_Order).*

Document Type
### Document Type

**Description**
 *Document type or rules*
**Help**
 *The Document Type determines document sequence and processing rules*

Document Status
### Document Status

**Description**
 *The current status of the document*
**Help**
 *The Document Status indicates the status of a document at this time.  If you want to change the document status, use the Document Action field*

Sales Transaction
### Sales Transaction

**Description**
 *This is a Sales Transaction*
**Help**
 *The Sales Transaction checkbox indicates if this item is a Sales Transaction.*

Self-Service
### Self-Service

**Description**
 *This is a Self-Service entry or this entry can be changed via Self-Service*
**Help**
 *Self-Service allows users to enter data or update their data.  The flag indicates, that this record was entered or created via Self-Service or that the user can change it via the Self-Service functionality.*

Date Invoiced
### Date Invoiced

**Description**
 *Date printed on Invoice*
**Help**
 *The Date Invoice indicates the date printed on the invoice.*

Account Date
### Account Date

**Description**
 *Accounting Date*
**Help**
 *The Accounting Date indicates the date to be used on the General Ledger account entries generated from this document. It is also used for any currency conversion.*

Business Partner
### Business Partner

**Description**
 *Identifies a Business Partner*
**Help**
 *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*

Partner Location
### Partner Location

**Description**
 *Identifies the (ship to) address for this Business Partner*
**Help**
 *The Partner address indicates the location of a Business Partner*

User/Contact
### User/Contact

**Description**
 *User within the system - Internal or Business Partner Contact*
**Help**
 *The User identifies a unique user in the system. This could be an internal user or a business partner contact*

Sales Representative
### Sales Representative

**Description**
 *Sales Representative or Company Agent*
**Help**
 *The Sales Representative indicates the Sales Rep for this Region.  Any Sales Rep must be a valid internal user.*

Description
### Description

**Description**
 *Optional short description of the record*
**Help**
 *A description is limited to 255 characters.*

Paid
### Paid

**Description**
 *The document is paid*

In Dispute
### In Dispute

**Description**
 *Document is in dispute*
**Help**
 *The document is in dispute. Use Requests to track details.*

Payment Rule
### Payment Rule

**Description**
 *How you pay the invoice*
**Help**
 *The Payment Rule indicates the method of invoice payment.*

Payment Term
### Payment Term

**Description**
 *The terms of Payment (timing, discount)*
**Help**
 *Payment Terms identify the method and timing of payment.*

Price List
### Price List

**Description**
 *Unique identifier of a Price List*
**Help**
 *Price Lists are used to determine the pricing, margin and cost of items purchased or sold.*

Currency
### Currency

**Description**
 *The Currency for this record*
**Help**
 *Indicates the Currency to be used when processing or reporting on this record*

Total Lines
### Total Lines

**Description**
 *Total of all document lines*
**Help**
 *The Total amount displays the total of all lines in document currency*

Grand Total
### Grand Total

**Description**
 *Total amount of document*
**Help**
 *The Grand Total displays the total amount including Tax and Freight in document currency*

Order
### Order

**Description**
 *Order*
**Help**
 *The Order is a control document.  The  Order is complete when the quantity ordered is the same as the quantity shipped and invoiced.  When you close an order, unshipped (backordered) quantities are cancelled.*

Order Reference
### Order Reference

**Description**
 *Transaction Reference Number (Sales Order, Purchase Order) of your Business Partner*
**Help**
 *The business partner order reference is the order reference for this specific transaction; Often Purchase Order numbers are given to print on Invoices for easier reference.  A standard number can be defined in the Business Partner (Customer) window.*

Date Ordered
### Date Ordered

**Description**
 *Date of Order*
**Help**
 *Indicates the Date an item was ordered.*

Date printed
### Date printed

**Description**
 *Date the document was printed.*
**Help**
 *Indicates the Date that a document was printed.*

Project
### Project

**Description**
 *Financial Project*
**Help**
 *A Project allows you to track and control internal or external activities.*

Activity
### Activity

**Description**
 *Business Activity*
**Help**
 *Activities indicate tasks that are performed and used to utilize Activity based Costing*

User List 1
### User List 1

**Description**
 *User defined list element #1*
**Help**
 *The user defined element displays the optional elements that have been defined for this account combination.*

User List 2
### User List 2

**Description**
 *User defined list element #2*
**Help**
 *The user defined element displays the optional elements that have been defined for this account combination.*

User List 3
### User List 3

**Description**
 *User defined list element #3*
**Help**
 *The user defined element displays the optional elements that have been defined for this account combination.*

User List 4
### User List 4

**Description**
 *User defined list element #4*
**Help**
 *The user defined element displays the optional elements that have been defined for this account combination.*

Campaign
### Campaign

**Description**
 *Marketing Campaign*
**Help**
 *The Campaign defines a unique marketing program.  Projects can be associated with a pre defined Marketing Campaign.  You can then report based on a specific Campaign.*

Trx Organization
### Trx Organization

**Description**
 *Performing or initiating organization*
**Help**
 *The organization which performs or initiates this transaction (for another organization).  The owning Organization may not be the transaction organization in a service bureau environment, with centralized services, and inter-organization transactions.*

Posted
### Posted

**Description**
 *Posting status*
**Help**
 *The Posted field indicates the status of the Generation of General Ledger Accounting Lines*

Approved
### Approved

**Description**
 *Indicates if this document requires approval*
**Help**
 *The Approved checkbox indicates if this document requires approval before it can be processed.*

Payments
### Payments

**Description**
 *Payments*

Fields
## Fields


Client
### Client

**Description**
 *Client/Tenant for this installation.*
**Help**
 *A Client is a company or a legal entity. You cannot share data between Clients. Tenant is a synonym for Client.*

Organization
### Organization

**Description**
 *Organizational entity within client*
**Help**
 *An organization is a unit of your client or legal entity - examples are store, department. You can share data between organizations.*

Payment
### Payment

**Description**
 *Payment identifier*
**Help**
 *The Payment is a unique identifier of this payment.*

Document No
### Document No

**Description**
 *Document sequence number of the document*
**Help**
 *The document number is usually automatically generated by the system and determined by the document type of the document. If the document is not saved, the preliminary number is displayed in "<>".

If the document type of your document has no automatic document sequence defined, the field is empty if you create a new document. This is for documents which usually have an external number (like vendor invoice).  If you leave the field empty, the system will generate a document number for you. The document sequence used for this fallback number is defined in the "Maintain Sequence" window with the name "DocumentNo_<TableName>", where TableName is the actual name of the table (e.g. C_Order).*

Transaction Date
### Transaction Date

**Description**
 *Transaction Date*
**Help**
 *The Transaction Date indicates the date of the transaction.*

Bank Account
### Bank Account

**Description**
 *Account at the Bank*
**Help**
 *The Bank Account identifies an account at this Bank.*

Description
### Description

**Description**
 *Optional short description of the record*
**Help**
 *A description is limited to 255 characters.*

Receipt
### Receipt

**Description**
 *This is a sales transaction (receipt)*

Self-Service
### Self-Service

**Description**
 *This is a Self-Service entry or this entry can be changed via Self-Service*
**Help**
 *Self-Service allows users to enter data or update their data.  The flag indicates, that this record was entered or created via Self-Service or that the user can change it via the Self-Service functionality.*

Document Type
### Document Type

**Description**
 *Document type or rules*
**Help**
 *The Document Type determines document sequence and processing rules*

Document Status
### Document Status

**Description**
 *The current status of the document*
**Help**
 *The Document Status indicates the status of a document at this time.  If you want to change the document status, use the Document Action field*

Business Partner
### Business Partner

**Description**
 *Identifies a Business Partner*
**Help**
 *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*

Partner Bank Account
### Partner Bank Account

**Description**
 *Bank Account of the Business Partner*
**Help**
 *The Partner Bank Account identifies the bank account to be used for this Business Partner*

Tender type
### Tender type

**Description**
 *Method of Payment*
**Help**
 *The Tender Type indicates the method of payment (ACH or Direct Deposit, Credit Card, Check, Direct Debit)*

Transaction Type
### Transaction Type

**Description**
 *Type of credit card transaction*
**Help**
 *The Transaction Type indicates the type of transaction to be submitted to the Credit Card Company.*

Account No
### Account No

**Description**
 *Account Number*
**Help**
 *The Account Number indicates the Number assigned to this bank account.*

Account Name
### Account Name

**Description**
 *Name on Credit Card or Account holder*
**Help**
 *The Name of the Credit Card or Account holder.*

Check No
### Check No

**Description**
 *Check Number*
**Help**
 *The Check Number indicates the number on the check.*

Original Transaction ID
### Original Transaction ID

**Description**
 *Original Transaction ID*
**Help**
 *The Original Transaction ID is used for reversing transactions and indicates the transaction that has been reversed.*

Authorization Code
### Authorization Code

**Description**
 *Authorization Code returned*
**Help**
 *The Authorization Code indicates the code returned from the electronic transmission.*

Authorization Code (DC)
### Authorization Code (DC)

**Description**
 *Authorization Code Delayed Capture returned*
**Help**
 *The Authorization Code indicates the code returned from the electronic transmission.*

Reference
### Reference

**Description**
 *Payment reference*
**Help**
 *The Payment Reference indicates the reference returned from the Credit Card Company for a payment*

Reference (DC)
### Reference (DC)

**Description**
 *Payment Reference Delayed Capture*
**Help**
 *The Payment Reference indicates the reference returned from the Credit Card Company for a payment*

Credit Card
### Credit Card

**Description**
 *Credit Card (Visa, MC, AmEx)*
**Help**
 *The Credit Card drop down list box is used for selecting the type of Credit Card presented for payment.*

Voice authorization code
### Voice authorization code

**Description**
 *Voice Authorization Code from credit card company*
**Help**
 *The Voice Authorization Code indicates the code received from the Credit Card Company.*

Currency
### Currency

**Description**
 *The Currency for this record*
**Help**
 *Indicates the Currency to be used when processing or reporting on this record*

Payment amount
### Payment amount

**Description**
 *Amount being paid*
**Help**
 *Indicates the amount this payment is for.  The payment amount can be for single or multiple invoices or a partial payment for an invoice.*

Discount Amount
### Discount Amount

**Description**
 *Calculated amount of discount*
**Help**
 *The Discount Amount indicates the discount amount for a document or line.*

Write-off Amount
### Write-off Amount

**Description**
 *Amount to write-off*
**Help**
 *The Write Off Amount indicates the amount to be written off as uncollectible.*

Order
### Order

**Description**
 *Order*
**Help**
 *The Order is a control document.  The  Order is complete when the quantity ordered is the same as the quantity shipped and invoiced.  When you close an order, unshipped (backordered) quantities are cancelled.*

Invoice
### Invoice

**Description**
 *Invoice Identifier*
**Help**
 *The Invoice Document.*

Over/Under Payment
### Over/Under Payment

**Description**
 *Over-Payment (unallocated) or Under-Payment (partial payment)*
**Help**
 *Overpayments (negative) are unallocated amounts and allow you to receive money for more than the particular invoice. 
Underpayments (positive) is a partial payment for the invoice. You do not write off the unpaid amount.*

Over/Under Payment
### Over/Under Payment

**Description**
 *Over-Payment (unallocated) or Under-Payment (partial payment) Amount*
**Help**
 *Overpayments (negative) are unallocated amounts and allow you to receive money for more than the particular invoice. 
Underpayments (positive) is a partial payment for the invoice. You do not write off the unpaid amount.*

Approved
### Approved

**Description**
 *Indicates if this document requires approval*
**Help**
 *The Approved checkbox indicates if this document requires approval before it can be processed.*

Prepayment
### Prepayment

**Description**
 *The Payment/Receipt is a Prepayment*
**Help**
 *Payments not allocated to an invoice with a charge are posted to Unallocated Payments. When setting this flag, the payment is posted to the Customer or Vendor Prepayment account.*

Project
### Project

**Description**
 *Financial Project*
**Help**
 *A Project allows you to track and control internal or external activities.*

Activity
### Activity

**Description**
 *Business Activity*
**Help**
 *Activities indicate tasks that are performed and used to utilize Activity based Costing*

Campaign
### Campaign

**Description**
 *Marketing Campaign*
**Help**
 *The Campaign defines a unique marketing program.  Projects can be associated with a pre defined Marketing Campaign.  You can then report based on a specific Campaign.*

Trx Organization
### Trx Organization

**Description**
 *Performing or initiating organization*
**Help**
 *The organization which performs or initiates this transaction (for another organization).  The owning Organization may not be the transaction organization in a service bureau environment, with centralized services, and inter-organization transactions.*

User List 1
### User List 1

**Description**
 *User defined list element #1*
**Help**
 *The user defined element displays the optional elements that have been defined for this account combination.*

User List 2
### User List 2

**Description**
 *User defined list element #2*
**Help**
 *The user defined element displays the optional elements that have been defined for this account combination.*

User List 3
### User List 3

**Description**
 *User defined list element #3*
**Help**
 *The user defined element displays the optional elements that have been defined for this account combination.*

User List 4
### User List 4

**Description**
 *User defined list element #4*
**Help**
 *The user defined element displays the optional elements that have been defined for this account combination.*

Allocated
### Allocated

**Description**
 *Indicates if the payment has been allocated*
**Help**
 *The Allocated checkbox indicates if a payment has been allocated or associated with an invoice or invoices.*

Posted
### Posted

**Description**
 *Posting status*
**Help**
 *The Posted field indicates the status of the Generation of General Ledger Accounting Lines*

Requests
### Requests

**Description**
 *Requests*

Fields
## Fields


Client
### Client

**Description**
 *Client/Tenant for this installation.*
**Help**
 *A Client is a company or a legal entity. You cannot share data between Clients. Tenant is a synonym for Client.*

Organization
### Organization

**Description**
 *Organizational entity within client*
**Help**
 *An organization is a unit of your client or legal entity - examples are store, department. You can share data between organizations.*

Request
### Request

**Description**
 *Request from a Business Partner or Prospect*
**Help**
 *The Request identifies a unique request from a Business Partner or Prospect.*

Document No
### Document No

**Description**
 *Document sequence number of the document*
**Help**
 *The document number is usually automatically generated by the system and determined by the document type of the document. If the document is not saved, the preliminary number is displayed in "<>".

If the document type of your document has no automatic document sequence defined, the field is empty if you create a new document. This is for documents which usually have an external number (like vendor invoice).  If you leave the field empty, the system will generate a document number for you. The document sequence used for this fallback number is defined in the "Maintain Sequence" window with the name "DocumentNo_<TableName>", where TableName is the actual name of the table (e.g. C_Order).*

Request Type
### Request Type

**Description**
 *Type of request (e.g. Inquiry, Complaint, ..)*
**Help**
 *Request Types are used for processing and categorizing requests. Options are Account Inquiry, Warranty Issue, etc.*

Group
### Group

**Description**
 *Request Group*
**Help**
 *Group of requests (e.g. version numbers, responsibility, ...)*

Category
### Category

**Description**
 *Request Category*
**Help**
 *Category or Topic of the Request*

Related Request
### Related Request

**Description**
 *Related Request (Master Issue, ..)*
**Help**
 *Request related to this request*

Status
### Status

**Description**
 *Request Status*
**Help**
 *Status if the request (open, closed, investigating, ..)*

Resolution
### Resolution

**Description**
 *Request Resolution*
**Help**
 *Resolution status (e.g. Fixed, Rejected, ..)*

Priority
### Priority

**Description**
 *Indicates if this request is of a high, medium or low priority.*
**Help**
 *The Priority indicates the importance of this request.*

User Importance
### User Importance

**Description**
 *Priority of the issue for the User*

Summary
### Summary

**Description**
 *Textual summary of this request*
**Help**
 *The Summary allows free form text entry of a recap of this request.*

Confidentiality
### Confidentiality

**Description**
 *Type of Confidentiality*

Invoiced
### Invoiced

**Description**
 *Is this invoiced?*
**Help**
 *If selected, invoices are created*

Escalated
### Escalated

**Description**
 *This request has been escalated*
**Help**
 *The Escalated checkbox indicates that this request has been escalated or raised in importance.*

Self-Service
### Self-Service

**Description**
 *This is a Self-Service entry or this entry can be changed via Self-Service*
**Help**
 *Self-Service allows users to enter data or update their data.  The flag indicates, that this record was entered or created via Self-Service or that the user can change it via the Self-Service functionality.*

Sales Representative
### Sales Representative

**Description**
 *Sales Representative or Company Agent*
**Help**
 *The Sales Representative indicates the Sales Rep for this Region.  Any Sales Rep must be a valid internal user.*

Role
### Role

**Description**
 *Responsibility Role*
**Help**
 *The Role determines security and access a user who has this Role will have in the System.*

Date next action
### Date next action

**Description**
 *Date that this request should be acted on*
**Help**
 *The Date Next Action indicates the next scheduled date for an action to occur for this request.*

Entry Confidentiality
### Entry Confidentiality

**Description**
 *Confidentiality of the individual entry*

Standard Response
### Standard Response

**Description**
 *Request Standard Response*
**Help**
 *Text blocks to be copied into request response text*

Mail Template
### Mail Template

**Description**
 *Text templates for mailings*
**Help**
 *The Mail Template indicates the mail template for return messages. Mail text can include variables.  The priority of parsing is User/Contact, Business Partner and then the underlying business object (like Request, Dunning, Workflow object).
So, @Name@ would resolve into the User name (if user is defined defined), then Business Partner name (if business partner is defined) and then the Name of the business object if it has a Name.
For Multi-Lingual systems, the template is translated based on the Business Partner's language selection.*

Result
### Result

**Description**
 *Result of the action taken*
**Help**
 *The Result indicates the result of any action taken on this request.*

Product Used
### Product Used

**Description**
 *Product/Resource/Service used in Request*
**Help**
 *Invoicing uses the Product used.*

Quantity Used
### Quantity Used

**Description**
 *Quantity used for this event*

Quantity Invoiced
### Quantity Invoiced

**Description**
 *Invoiced Quantity*
**Help**
 *The Invoiced Quantity indicates the quantity of a product that have been invoiced.*

Task Status
### Task Status

**Description**
 *Status of the Task*
**Help**
 *Completion Rate and Status of the Task*

Quantity Plan
### Quantity Plan

**Description**
 *Planned Quantity*
**Help**
 *Planned Quantity*

Start Plan
### Start Plan

**Description**
 *Planned Start Date*
**Help**
 *Date when you plan to start*

Complete Plan
### Complete Plan

**Description**
 *Planned Completion Date*
**Help**
 *Date when the task is planned to be complete*

Start Date
### Start Date

**Description**
 *First effective day (inclusive)*
**Help**
 *The Start Date indicates the first or starting date*

Close Date
### Close Date

**Description**
 *Close Date*
**Help**
 *The Close Date indicates the last or final date*

Business Partner
### Business Partner

**Description**
 *Identifies a Business Partner*
**Help**
 *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*

User/Contact
### User/Contact

**Description**
 *User within the system - Internal or Business Partner Contact*
**Help**
 *The User identifies a unique user in the system. This could be an internal user or a business partner contact*

Product
### Product

**Description**
 *Product, Service, Item*
**Help**
 *Identifies an item which is either purchased or sold in this organization.*

Fixed Asset
### Fixed Asset

**Description**
 *Fixed Asset used internally or by customers*
**Help**
 *A Fixed Asset is either created by purchasing or by delivering a product.  A Fixed Asset can be used internally or be a customer Fixed Asset.*

Project
### Project

**Description**
 *Financial Project*
**Help**
 *A Project allows you to track and control internal or external activities.*

Activity
### Activity

**Description**
 *Business Activity*
**Help**
 *Activities indicate tasks that are performed and used to utilize Activity based Costing*

Project Phase
### Project Phase

**Description**
 *Phase of a Project*

Project Task
### Project Task

**Description**
 *Actual Project Task in a Phase*
**Help**
 *A Project Task in a Project Phase represents the actual work.*

Campaign
### Campaign

**Description**
 *Marketing Campaign*
**Help**
 *The Campaign defines a unique marketing program.  Projects can be associated with a pre defined Marketing Campaign.  You can then report based on a specific Campaign.*

Trx Organization
### Trx Organization

**Description**
 *Performing or initiating organization*
**Help**
 *The organization which performs or initiates this transaction (for another organization).  The owning Organization may not be the transaction organization in a service bureau environment, with centralized services, and inter-organization transactions.*

User List 1
### User List 1

**Description**
 *User defined list element #1*
**Help**
 *The user defined element displays the optional elements that have been defined for this account combination.*

User List 2
### User List 2

**Description**
 *User defined list element #2*
**Help**
 *The user defined element displays the optional elements that have been defined for this account combination.*

User List 3
### User List 3

**Description**
 *User defined list element #3*
**Help**
 *The user defined element displays the optional elements that have been defined for this account combination.*

User List 4
### User List 4

**Description**
 *User defined list element #4*
**Help**
 *The user defined element displays the optional elements that have been defined for this account combination.*

Order
### Order

**Description**
 *Order*
**Help**
 *The Order is a control document.  The  Order is complete when the quantity ordered is the same as the quantity shipped and invoiced.  When you close an order, unshipped (backordered) quantities are cancelled.*

Sales Order Line
### Sales Order Line

**Description**
 *Sales Order Line*
**Help**
 *The Sales Order Line is a unique identifier for a line in an order.*

Shipment/Receipt
### Shipment/Receipt

**Description**
 *Material Shipment Document*
**Help**
 *The Material Shipment / Receipt*

Shipment/Receipt Line
### Shipment/Receipt Line

**Description**
 *Line on Shipment or Receipt document*
**Help**
 *The Shipment/Receipt Line indicates a unique line in a Shipment/Receipt document*

Invoice
### Invoice

**Description**
 *Invoice Identifier*
**Help**
 *The Invoice Document.*

Invoice Line
### Invoice Line

**Description**
 *Invoice Detail Line*
**Help**
 *The Invoice Line uniquely identifies a single line of an Invoice.*

Distribution Order
### Distribution Order


Distribution Order Line
### Distribution Order Line


Manufacturing Order
### Manufacturing Order

**Description**
 *Manufacturing Order*

Manufacturing Cost Collector
### Manufacturing Cost Collector


Requisition
### Requisition

**Description**
 *Material Requisition*

Requisition Line
### Requisition Line

**Description**
 *Material Requisition Line*

RMA
### RMA

**Description**
 *Return Material Authorization*
**Help**
 *A Return Material Authorization may be required to accept returns and to create Credit Memos*

RMA Line
### RMA Line

**Description**
 *Return Material Authorization Line*
**Help**
 *Detail information about the returned goods*

Payment
### Payment

**Description**
 *Payment identifier*
**Help**
 *The Payment is a unique identifier of this payment.*

Request Amount
### Request Amount

**Description**
 *Amount associated with this request*
**Help**
 *The Request Amount indicates any amount that is associated with this request.  For example, a warranty amount or refund amount.*

Table
### Table

**Description**
 *Database Table information*
**Help**
 *The Database Table provides the information of the table definition*

Record ID
### Record ID

**Description**
 *Direct internal record ID*
**Help**
 *The Record ID is the internal unique identifier of a record. Please note that zooming to the record may not be successful for Orders, Invoices and Shipment/Receipts as sometimes the Sales Order type is not known.*

Date last action
### Date last action

**Description**
 *Date this request was last acted on*
**Help**
 *The Date Last Action indicates that last time that the request was acted on.*

Last Alert
### Last Alert

**Description**
 *Date when last alert were sent*
**Help**
 *The last alert date is updated when a reminder email is sent*

Last Result
### Last Result

**Description**
 *Result of last contact*
**Help**
 *The Last Result identifies the result of the last contact made.*

Created
### Created

**Description**
 *Date this record was created*
**Help**
 *The Created field indicates the date that this record was created.*

Created By
### Created By

**Description**
 *User who created this records*
**Help**
 *The Created By field indicates the user who created this record.*

Updated
### Updated

**Description**
 *Date this record was updated*
**Help**
 *The Updated field indicates the date that this record was updated.*

Updated By
### Updated By

**Description**
 *User who updated this records*
**Help**
 *The Updated By field indicates the user who updated this record.*

Change Request
### Change Request

**Description**
 *BOM (Engineering) Change Request*
**Help**
 *Change requests for a Bill of Materials. They can be automatically created from Requests, if enabled in the Request Type and the Request Group refers to a Bill of Materials*

Request Invoice
### Request Invoice

**Description**
 *The generated invoice for this request*
**Help**
 *The optionally generated invoice for the request*

Processed
### Processed

**Description**
 *The document has been processed*
**Help**
 *The Processed checkbox indicates that a document has been processed.*

Fixed in
### Fixed in

**Description**
 *Fixed in Change Notice*

Assets
### Assets

**Description**
 *Assets*

Fields
## Fields


Client
### Client

**Description**
 *Client/Tenant for this installation.*
**Help**
 *A Client is a company or a legal entity. You cannot share data between Clients. Tenant is a synonym for Client.*

Organization
### Organization

**Description**
 *Organizational entity within client*
**Help**
 *An organization is a unit of your client or legal entity - examples are store, department. You can share data between organizations.*

Search Key
### Search Key

**Description**
 *Search key for the record in the format required - must be unique*
**Help**
 *A search key allows you a fast method of finding a particular record.
If you leave the search key empty, the system automatically creates a numeric number.  The document sequence used for this fallback number is defined in the "Maintain Sequence" window with the name "DocumentNo_<TableName>", where TableName is the actual name of the table (e.g. C_Order).*

Asset Group
### Asset Group

**Description**
 *Group of Assets*
**Help**
 *The group of assets determines default accounts.  If an asset group is selected in the product category, assets are created when delivering the asset.*

Name
### Name

**Description**
 *Alphanumeric identifier of the entity*
**Help**
 *The name of an entity (record) is used as an default search option in addition to the search key. The name is up to 60 characters in length.*

Description
### Description

**Description**
 *Optional short description of the record*
**Help**
 *A description is limited to 255 characters.*

Product
### Product

**Description**
 *Product, Service, Item*
**Help**
 *Identifies an item which is either purchased or sold in this organization.*

Attribute Set Instance
### Attribute Set Instance

**Description**
 *Product Attribute Set Instance*
**Help**
 *The values of the actual Product Attribute Instances.  The product level attributes are defined on Product level.*

Lot No
### Lot No

**Description**
 *Lot number (alphanumeric)*
**Help**
 *The Lot Number indicates the specific lot that a product was part of.*

Serial No
### Serial No

**Description**
 *Product Serial Number*
**Help**
 *The Serial Number identifies a tracked, warranted product.  It can only be used when the quantity is 1.*

Quantity
### Quantity

**Description**
 *Quantity*
**Help**
 *The Quantity indicates the number of a specific product or item for this document.*

In Service Date
### In Service Date

**Description**
 *Date when Asset was put into service*
**Help**
 *The date when the asset was put into service - usually used as start date for depreciation.*

Guarantee Date
### Guarantee Date

**Description**
 *Date when guarantee expires*
**Help**
 *Date when the normal guarantee or availability expires*

Distribution Orders
### Distribution Orders

**Description**
 *Distribution Orders*

Fields
## Fields


Client
### Client

**Description**
 *Client/Tenant for this installation.*
**Help**
 *A Client is a company or a legal entity. You cannot share data between Clients. Tenant is a synonym for Client.*

Organization
### Organization

**Description**
 *Organizational entity within client*
**Help**
 *An organization is a unit of your client or legal entity - examples are store, department. You can share data between organizations.*

Distribution Order
### Distribution Order


Order
### Order

**Description**
 *Order*
**Help**
 *The Order is a control document.  The  Order is complete when the quantity ordered is the same as the quantity shipped and invoiced.  When you close an order, unshipped (backordered) quantities are cancelled.*

Document No
### Document No

**Description**
 *Document sequence number of the document*
**Help**
 *The document number is usually automatically generated by the system and determined by the document type of the document. If the document is not saved, the preliminary number is displayed in "<>".

If the document type of your document has no automatic document sequence defined, the field is empty if you create a new document. This is for documents which usually have an external number (like vendor invoice).  If you leave the field empty, the system will generate a document number for you. The document sequence used for this fallback number is defined in the "Maintain Sequence" window with the name "DocumentNo_<TableName>", where TableName is the actual name of the table (e.g. C_Order).*

Order Reference
### Order Reference

**Description**
 *Transaction Reference Number (Sales Order, Purchase Order) of your Business Partner*
**Help**
 *The business partner order reference is the order reference for this specific transaction; Often Purchase Order numbers are given to print on Invoices for easier reference.  A standard number can be defined in the Business Partner (Customer) window.*

Description
### Description

**Description**
 *Optional short description of the record*
**Help**
 *A description is limited to 255 characters.*

Document Type
### Document Type

**Description**
 *Document type or rules*
**Help**
 *The Document Type determines document sequence and processing rules*

Company Agent
### Company Agent

**Description**
 *Company Agent*
**Help**
 *Company Agent to Distribution Order*

Date Ordered
### Date Ordered

**Description**
 *Date of Order*
**Help**
 *Indicates the Date an item was ordered.*

Date Promised
### Date Promised

**Description**
 *Date Order was promised*
**Help**
 *The Date Promised indicates the date, if any, that an Order was promised for.*

Business Partner
### Business Partner

**Description**
 *Identifies a Business Partner*
**Help**
 *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*

User/Contact
### User/Contact

**Description**
 *User within the system - Internal or Business Partner Contact*
**Help**
 *The User identifies a unique user in the system. This could be an internal user or a business partner contact*

Transit Warehouse
### Transit Warehouse

**Description**
 *Storage Warehouse and Service Point*
**Help**
 *The Warehouse identifies a unique Warehouse where products are stored or Services are provided.*

Partner Location
### Partner Location

**Description**
 *Identifies the (ship to) address for this Business Partner*
**Help**
 *The Partner address indicates the location of a Business Partner*

Delivery Rule
### Delivery Rule

**Description**
 *Defines the timing of Delivery*
**Help**
 *The Delivery Rule indicates when an order should be delivered. For example should the order be delivered when the entire order is complete, when a line is complete or as the products become available.*

Drop Shipment
### Drop Shipment

**Description**
 *Drop Shipments are sent from the Vendor directly to the Customer*
**Help**
 *Drop Shipments do not cause any Inventory reservations or movements as the Shipment is from the Vendor's inventory. The Shipment of the Vendor to the Customer must be confirmed.*

Ship Date
### Ship Date

**Description**
 *Shipment Date/Time*
**Help**
 *Actual Date/Time of Shipment (pick up)*

Date received
### Date received

**Description**
 *Date a product was received*
**Help**
 *The Date Received indicates the date that product was received.*

Pick Date
### Pick Date

**Description**
 *Date/Time when picked for Shipment*

Date printed
### Date printed

**Description**
 *Date the document was printed.*
**Help**
 *Indicates the Date that a document was printed.*

Delivery Via
### Delivery Via

**Description**
 *How the order will be delivered*
**Help**
 *The Delivery Via indicates how the products should be delivered. For example, will the order be picked up or shipped.*

Shipper
### Shipper

**Description**
 *Method or manner of product delivery*
**Help**
 *The Shipper indicates the method of delivering product*

Freight Cost Rule
### Freight Cost Rule

**Description**
 *Method for charging Freight*
**Help**
 *The Freight Cost Rule indicates the method used when charging for freight.*

Freight Category
### Freight Category

**Description**
 *Category of the Freight*
**Help**
 *Freight Categories are used to calculate the Freight for the Shipper selected*

Freight Amount
### Freight Amount

**Description**
 *Freight Amount*
**Help**
 *The Freight Amount indicates the amount charged for Freight in the document currency.*

Tracking No
### Tracking No

**Description**
 *Number to track the shipment*

Priority
### Priority

**Description**
 *Priority of a document*
**Help**
 *The Priority indicates the importance (high, medium, low) of this document*

Weight
### Weight

**Description**
 *Weight of a product*
**Help**
 *The Weight indicates the weight  of the product in the Weight UOM of the Client*

Volume
### Volume

**Description**
 *Volume of a product*
**Help**
 *The Volume indicates the volume of the product in the Volume UOM of the Client*

Project
### Project

**Description**
 *Financial Project*
**Help**
 *A Project allows you to track and control internal or external activities.*

Activity
### Activity

**Description**
 *Business Activity*
**Help**
 *Activities indicate tasks that are performed and used to utilize Activity based Costing*

Campaign
### Campaign

**Description**
 *Marketing Campaign*
**Help**
 *The Campaign defines a unique marketing program.  Projects can be associated with a pre defined Marketing Campaign.  You can then report based on a specific Campaign.*

Trx Organization
### Trx Organization

**Description**
 *Performing or initiating organization*
**Help**
 *The organization which performs or initiates this transaction (for another organization).  The owning Organization may not be the transaction organization in a service bureau environment, with centralized services, and inter-organization transactions.*

User List 1
### User List 1

**Description**
 *User defined list element #1*
**Help**
 *The user defined element displays the optional elements that have been defined for this account combination.*

User List 2
### User List 2

**Description**
 *User defined list element #2*
**Help**
 *The user defined element displays the optional elements that have been defined for this account combination.*

User List 3
### User List 3

**Description**
 *User defined list element #3*
**Help**
 *The user defined element displays the optional elements that have been defined for this account combination.*

User List 4
### User List 4

**Description**
 *User defined list element #4*
**Help**
 *The user defined element displays the optional elements that have been defined for this account combination.*

Document Status
### Document Status

**Description**
 *The current status of the document*
**Help**
 *The Document Status indicates the status of a document at this time.  If you want to change the document status, use the Document Action field*

In Transit
### In Transit

**Description**
 *Movement is in transit*
**Help**
 *Material Movement is in transit - shipped, but not received.
The transaction is completed, if confirmed.*

Approved
### Approved

**Description**
 *Indicates if this document requires approval*
**Help**
 *The Approved checkbox indicates if this document requires approval before it can be processed.*

Printed
### Printed

**Description**
 *Indicates if this document / line is printed*
**Help**
 *The Printed checkbox indicates if this document or line will included when printing.*

Delivered
### Delivered


Manufacturing Orders
### Manufacturing Orders

**Description**
 *Manufacturing Orders*

Fields
## Fields


Client
### Client

**Description**
 *Client/Tenant for this installation.*
**Help**
 *A Client is a company or a legal entity. You cannot share data between Clients. Tenant is a synonym for Client.*

Organization
### Organization

**Description**
 *Organizational entity within client*
**Help**
 *An organization is a unit of your client or legal entity - examples are store, department. You can share data between organizations.*

Manufacturing Order
### Manufacturing Order

**Description**
 *Manufacturing Order*

Document No
### Document No

**Description**
 *Document sequence number of the document*
**Help**
 *The document number is usually automatically generated by the system and determined by the document type of the document. If the document is not saved, the preliminary number is displayed in "<>".

If the document type of your document has no automatic document sequence defined, the field is empty if you create a new document. This is for documents which usually have an external number (like vendor invoice).  If you leave the field empty, the system will generate a document number for you. The document sequence used for this fallback number is defined in the "Maintain Sequence" window with the name "DocumentNo_<TableName>", where TableName is the actual name of the table (e.g. C_Order).*

Line No
### Line No

**Description**
 *Unique line for this document*
**Help**
 *Indicates the unique line for a document.  It will also control the display order of the lines within a document.*

Target Document Type
### Target Document Type

**Description**
 *Target document type for conversing documents*
**Help**
 *You can convert document types (e.g. from Offer to Order or Invoice).  The conversion is then reflected in the current type.  This processing is initiated by selecting the appropriate Document Action.*

Active
### Active

**Description**
 *The record is active in the system*
**Help**
 *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*

Description
### Description

**Description**
 *Optional short description of the record*
**Help**
 *A description is limited to 255 characters.*

Product
### Product

**Description**
 *Product, Service, Item*
**Help**
 *Identifies an item which is either purchased or sold in this organization.*

Attribute Set Instance
### Attribute Set Instance

**Description**
 *Product Attribute Set Instance*
**Help**
 *The values of the actual Product Attribute Instances.  The product level attributes are defined on Product level.*

Resource/Plant
### Resource/Plant

**Description**
 *Resource/Plant*

Workflow
### Workflow

**Description**
 *Workflow or combination of tasks*
**Help**
 *The Workflow field identifies a unique Workflow in the system.*

Warehouse
### Warehouse

**Description**
 *Storage Warehouse and Service Point*
**Help**
 *The Warehouse identifies a unique Warehouse where products are stored or Services are provided.*

BOM & Formula
### BOM & Formula

**Description**
 *BOM & Formula*

Planner
### Planner

**Description**
 *Company Agent for Planning*
**Help**
 *The Master Planner indicates the company agent in charge of the MPS management. Any Master Planner must be a valid internal user.*

Priority
### Priority

**Description**
 *Priority of a document*
**Help**
 *The Priority indicates the importance (high, medium, low) of this document*

Date Ordered
### Date Ordered

**Description**
 *Date of Order*
**Help**
 *Indicates the Date an item was ordered.
Date Ordered is the date when the order was generated. If the MO is created manually the default date ordered is the system date. If the MO was generated by MRP the default date ordered is the day of the MRP process.*

Date Promised
### Date Promised

**Description**
 *Date Order was promised*
**Help**
 *The Date Promised indicates the date, if any, that an Order was promised for.
Date Promised Is the date we commit to give the order to the warehouse. If the MO is created manually the default date promised is the system date. If the MO was generated by MRP this date is filled automatically using its algorithm calculation.*

Date Confirm
### Date Confirm

**Description**
 *Date Confirm of this Order*

Date Delivered
### Date Delivered

**Description**
 *Date when the product was delivered*

Start Schedule
### Start Schedule

**Description**
 *Scheduled start date for this Order*

Finish Schedule
### Finish Schedule

**Description**
 *Scheduled Finish date for this Order*

Date Start
### Date Start

**Description**
 *Indicate the real date to start*
**Help**
 *It is the date when the first manufacturing order movement is reported, this movement can be an inventory or labor movement.*

Finish Date
### Finish Date

**Description**
 *Finish or (planned) completion date*
**Help**
 *The finish date is used to indicate when the project is expected to be completed or has been completed.

To Manufacturing Order is the date when the last manufacturing order movement is reported, It is the closing order date.*

Float Befored
### Float Befored


Float After
### Float After


Delivery Via
### Delivery Via

**Description**
 *How the order will be delivered*
**Help**
 *The Delivery Via indicates how the products should be delivered. For example, will the order be picked up or shipped.*

Freight Cost Rule
### Freight Cost Rule

**Description**
 *Method for charging Freight*
**Help**
 *The Freight Cost Rule indicates the method used when charging for freight.*

Shipper
### Shipper

**Description**
 *Method or manner of product delivery*
**Help**
 *The Shipper indicates the method of delivering product*

Tracking No
### Tracking No

**Description**
 *Number to track the shipment*

Freight Category
### Freight Category

**Description**
 *Category of the Freight*
**Help**
 *Freight Categories are used to calculate the Freight for the Shipper selected*

Quantity
### Quantity

**Description**
 *The Quantity Entered is based on the selected UoM*
**Help**
 *The Quantity Entered is converted to base product UoM quantity*

UOM
### UOM

**Description**
 *Unit of Measure*
**Help**
 *The UOM defines a unique non monetary Unit of Measure*

Qty Batchs
### Qty Batchs


Qty Batch Size
### Qty Batch Size


Ordered Quantity
### Ordered Quantity

**Description**
 *Ordered Quantity*
**Help**
 *The Ordered Quantity indicates the quantity of a product that was ordered.*

Delivered Quantity
### Delivered Quantity

**Description**
 *Delivered Quantity*
**Help**
 *The Delivered Quantity indicates the quantity of a product that has been delivered.*

Yield %
### Yield %

**Description**
 *The Yield is the percentage of a lot that is expected to be of acceptable wuality may fall below 100 percent*
**Help**
 *ADempiere Calculate the total yield for a product from the yield for each activity when the process Workflow Cost Roll-Up is executed.

The expected yield for an Activity can be expressed as:

Yield = Acceptable Units at Activity End x 100

The Total manufacturing yield for a product is determined by multiplying the yied percentage for each activity.

Manufacturing Yield = Yield % for Activity 10 x Yied % for Activity 20 , etc

Take care when setting yield to anything but 100% particularly when yied is used for multiples activities*

Qty Reject
### Qty Reject


Scrap %
### Scrap %

**Description**
 *Scrap % Quantity for this componet*
**Help**
 *Scrap % Quantity for this componet*

Project
### Project

**Description**
 *Financial Project*
**Help**
 *A Project allows you to track and control internal or external activities.*

Project Phase
### Project Phase

**Description**
 *Phase of a Project*

User List 3
### User List 3

**Description**
 *User defined list element #3*
**Help**
 *The user defined element displays the optional elements that have been defined for this account combination.*

Project Task
### Project Task

**Description**
 *Actual Project Task in a Phase*
**Help**
 *A Project Task in a Project Phase represents the actual work.*

User List 4
### User List 4

**Description**
 *User defined list element #4*
**Help**
 *The user defined element displays the optional elements that have been defined for this account combination.*

Campaign
### Campaign

**Description**
 *Marketing Campaign*
**Help**
 *The Campaign defines a unique marketing program.  Projects can be associated with a pre defined Marketing Campaign.  You can then report based on a specific Campaign.*

Document Status
### Document Status

**Description**
 *The current status of the document*
**Help**
 *The Document Status indicates the status of a document at this time.  If you want to change the document status, use the Document Action field*

Document Type
### Document Type

**Description**
 *Document type or rules*
**Help**
 *The Document Type determines document sequence and processing rules*

Activity
### Activity

**Description**
 *Business Activity*
**Help**
 *Activities indicate tasks that are performed and used to utilize Activity based Costing*

Trx Organization
### Trx Organization

**Description**
 *Performing or initiating organization*
**Help**
 *The organization which performs or initiates this transaction (for another organization).  The owning Organization may not be the transaction organization in a service bureau environment, with centralized services, and inter-organization transactions.*

User List 1
### User List 1

**Description**
 *User defined list element #1*
**Help**
 *The user defined element displays the optional elements that have been defined for this account combination.*

Approved
### Approved

**Description**
 *Indicates if this document requires approval*
**Help**
 *The Approved checkbox indicates if this document requires approval before it can be processed.*

User List 2
### User List 2

**Description**
 *User defined list element #2*
**Help**
 *The user defined element displays the optional elements that have been defined for this account combination.*

Printed
### Printed

**Description**
 *Indicates if this document / line is printed*
**Help**
 *The Printed checkbox indicates if this document or line will included when printing.*

Selected
### Selected


Processed
### Processed

**Description**
 *The document has been processed*
**Help**
 *The Processed checkbox indicates that a document has been processed.*

Internal Use Inventory
### Internal Use Inventory

**Description**
 *Internal Use Inventory*

Fields
## Fields


Client
### Client

**Description**
 *Client/Tenant for this installation.*
**Help**
 *A Client is a company or a legal entity. You cannot share data between Clients. Tenant is a synonym for Client.*

Organization
### Organization

**Description**
 *Organizational entity within client*
**Help**
 *An organization is a unit of your client or legal entity - examples are store, department. You can share data between organizations.*

Phys.Inventory
### Phys.Inventory

**Description**
 *Parameters for a Physical Inventory*
**Help**
 *The Physical Inventory indicates a unique parameters for a physical inventory.*

Document No
### Document No

**Description**
 *Document sequence number of the document*
**Help**
 *The document number is usually automatically generated by the system and determined by the document type of the document. If the document is not saved, the preliminary number is displayed in "<>".

If the document type of your document has no automatic document sequence defined, the field is empty if you create a new document. This is for documents which usually have an external number (like vendor invoice).  If you leave the field empty, the system will generate a document number for you. The document sequence used for this fallback number is defined in the "Maintain Sequence" window with the name "DocumentNo_<TableName>", where TableName is the actual name of the table (e.g. C_Order).*

Description
### Description

**Description**
 *Optional short description of the record*
**Help**
 *A description is limited to 255 characters.*

Warehouse
### Warehouse

**Description**
 *Storage Warehouse and Service Point*
**Help**
 *The Warehouse identifies a unique Warehouse where products are stored or Services are provided.*

Movement Date
### Movement Date

**Description**
 *Date a product was moved in or out of inventory*
**Help**
 *The Movement Date indicates the date that a product moved in or out of inventory.  This is the result of a shipment, receipt or inventory movement.*

Document Type
### Document Type

**Description**
 *Document type or rules*
**Help**
 *The Document Type determines document sequence and processing rules*

Project
### Project

**Description**
 *Financial Project*
**Help**
 *A Project allows you to track and control internal or external activities.*

Activity
### Activity

**Description**
 *Business Activity*
**Help**
 *Activities indicate tasks that are performed and used to utilize Activity based Costing*

Campaign
### Campaign

**Description**
 *Marketing Campaign*
**Help**
 *The Campaign defines a unique marketing program.  Projects can be associated with a pre defined Marketing Campaign.  You can then report based on a specific Campaign.*

Trx Organization
### Trx Organization

**Description**
 *Performing or initiating organization*
**Help**
 *The organization which performs or initiates this transaction (for another organization).  The owning Organization may not be the transaction organization in a service bureau environment, with centralized services, and inter-organization transactions.*

User List 1
### User List 1

**Description**
 *User defined list element #1*
**Help**
 *The user defined element displays the optional elements that have been defined for this account combination.*

User List 2
### User List 2

**Description**
 *User defined list element #2*
**Help**
 *The user defined element displays the optional elements that have been defined for this account combination.*

User List 3
### User List 3

**Description**
 *User defined list element #3*
**Help**
 *The user defined element displays the optional elements that have been defined for this account combination.*

User List 4
### User List 4

**Description**
 *User defined list element #4*
**Help**
 *The user defined element displays the optional elements that have been defined for this account combination.*

Approved
### Approved

**Description**
 *Indicates if this document requires approval*
**Help**
 *The Approved checkbox indicates if this document requires approval before it can be processed.*

Approval Amount
### Approval Amount

**Description**
 *Document Approval Amount*
**Help**
 *Approval Amount for Workflow*

Document Status
### Document Status

**Description**
 *The current status of the document*
**Help**
 *The Document Status indicates the status of a document at this time.  If you want to change the document status, use the Document Action field*

Posted
### Posted

**Description**
 *Posting status*
**Help**
 *The Posted field indicates the status of the Generation of General Ledger Accounting Lines*

Inventory Move
### Inventory Move

**Description**
 *Inventory Move*

Fields
## Fields


Client
### Client

**Description**
 *Client/Tenant for this installation.*
**Help**
 *A Client is a company or a legal entity. You cannot share data between Clients. Tenant is a synonym for Client.*

Organization
### Organization

**Description**
 *Organizational entity within client*
**Help**
 *An organization is a unit of your client or legal entity - examples are store, department. You can share data between organizations.*

Inventory Move
### Inventory Move

**Description**
 *Movement of Inventory*
**Help**
 *The Inventory Movement uniquely identifies a group of movement lines.*

Distribution Order
### Distribution Order


Order Reference
### Order Reference

**Description**
 *Transaction Reference Number (Sales Order, Purchase Order) of your Business Partner*
**Help**
 *The business partner order reference is the order reference for this specific transaction; Often Purchase Order numbers are given to print on Invoices for easier reference.  A standard number can be defined in the Business Partner (Customer) window.*

Document No
### Document No

**Description**
 *Document sequence number of the document*
**Help**
 *The document number is usually automatically generated by the system and determined by the document type of the document. If the document is not saved, the preliminary number is displayed in "<>".

If the document type of your document has no automatic document sequence defined, the field is empty if you create a new document. This is for documents which usually have an external number (like vendor invoice).  If you leave the field empty, the system will generate a document number for you. The document sequence used for this fallback number is defined in the "Maintain Sequence" window with the name "DocumentNo_<TableName>", where TableName is the actual name of the table (e.g. C_Order).*

Sales Representative
### Sales Representative

**Description**
 *Sales Representative or Company Agent*
**Help**
 *The Sales Representative indicates the Sales Rep for this Region.  Any Sales Rep must be a valid internal user.*

Description
### Description

**Description**
 *Optional short description of the record*
**Help**
 *A description is limited to 255 characters.*

Movement Date
### Movement Date

**Description**
 *Date a product was moved in or out of inventory*
**Help**
 *The Movement Date indicates the date that a product moved in or out of inventory.  This is the result of a shipment, receipt or inventory movement.*

Document Type
### Document Type

**Description**
 *Document type or rules*
**Help**
 *The Document Type determines document sequence and processing rules*

Business Partner
### Business Partner

**Description**
 *Identifies a Business Partner*
**Help**
 *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*

Partner Location
### Partner Location

**Description**
 *Identifies the (ship to) address for this Business Partner*
**Help**
 *The Partner address indicates the location of a Business Partner*

Shipper
### Shipper

**Description**
 *Method or manner of product delivery*
**Help**
 *The Shipper indicates the method of delivering product*

User/Contact
### User/Contact

**Description**
 *User within the system - Internal or Business Partner Contact*
**Help**
 *The User identifies a unique user in the system. This could be an internal user or a business partner contact*

Delivery Via
### Delivery Via

**Description**
 *How the order will be delivered*
**Help**
 *The Delivery Via indicates how the products should be delivered. For example, will the order be picked up or shipped.*

Delivery Rule
### Delivery Rule

**Description**
 *Defines the timing of Delivery*
**Help**
 *The Delivery Rule indicates when an order should be delivered. For example should the order be delivered when the entire order is complete, when a line is complete or as the products become available.*

Priority
### Priority

**Description**
 *Priority of a document*
**Help**
 *The Priority indicates the importance (high, medium, low) of this document*

Freight Cost Rule
### Freight Cost Rule

**Description**
 *Method for charging Freight*
**Help**
 *The Freight Cost Rule indicates the method used when charging for freight.*

Project
### Project

**Description**
 *Financial Project*
**Help**
 *A Project allows you to track and control internal or external activities.*

Activity
### Activity

**Description**
 *Business Activity*
**Help**
 *Activities indicate tasks that are performed and used to utilize Activity based Costing*

Campaign
### Campaign

**Description**
 *Marketing Campaign*
**Help**
 *The Campaign defines a unique marketing program.  Projects can be associated with a pre defined Marketing Campaign.  You can then report based on a specific Campaign.*

Trx Organization
### Trx Organization

**Description**
 *Performing or initiating organization*
**Help**
 *The organization which performs or initiates this transaction (for another organization).  The owning Organization may not be the transaction organization in a service bureau environment, with centralized services, and inter-organization transactions.*

User List 1
### User List 1

**Description**
 *User defined list element #1*
**Help**
 *The user defined element displays the optional elements that have been defined for this account combination.*

User List 2
### User List 2

**Description**
 *User defined list element #2*
**Help**
 *The user defined element displays the optional elements that have been defined for this account combination.*

User List 3
### User List 3

**Description**
 *User defined list element #3*
**Help**
 *The user defined element displays the optional elements that have been defined for this account combination.*

User List 4
### User List 4

**Description**
 *User defined list element #4*
**Help**
 *The user defined element displays the optional elements that have been defined for this account combination.*

Approved
### Approved

**Description**
 *Indicates if this document requires approval*
**Help**
 *The Approved checkbox indicates if this document requires approval before it can be processed.*

Approval Amount
### Approval Amount

**Description**
 *Document Approval Amount*
**Help**
 *Approval Amount for Workflow*

In Transit
### In Transit

**Description**
 *Movement is in transit*
**Help**
 *Material Movement is in transit - shipped, but not received.
The transaction is completed, if confirmed.*

Date received
### Date received

**Description**
 *Date a product was received*
**Help**
 *The Date Received indicates the date that product was received.*

Document Status
### Document Status

**Description**
 *The current status of the document*
**Help**
 *The Document Status indicates the status of a document at this time.  If you want to change the document status, use the Document Action field*

Processed
### Processed

**Description**
 *The document has been processed*
**Help**
 *The Processed checkbox indicates that a document has been processed.*

Posted
### Posted

**Description**
 *Posting status*
**Help**
 *The Posted field indicates the status of the Generation of General Ledger Accounting Lines*

Accounts Facts
### Accounts Facts

**Description**
 *Accounts Facts*

Fields
## Fields


Client
### Client

**Description**
 *Client/Tenant for this installation.*
**Help**
 *A Client is a company or a legal entity. You cannot share data between Clients. Tenant is a synonym for Client.*

Organization
### Organization

**Description**
 *Organizational entity within client*
**Help**
 *An organization is a unit of your client or legal entity - examples are store, department. You can share data between organizations.*

Accounting Schema
### Accounting Schema

**Description**
 *Rules for accounting*
**Help**
 *An Accounting Schema defines the rules used in accounting such as costing method, currency and calendar*

Table
### Table

**Description**
 *Database Table information*
**Help**
 *The Database Table provides the information of the table definition*

Record ID
### Record ID

**Description**
 *Direct internal record ID*
**Help**
 *The Record ID is the internal unique identifier of a record. Please note that zooming to the record may not be successful for Orders, Invoices and Shipment/Receipts as sometimes the Sales Order type is not known.*

Description
### Description

**Description**
 *Optional short description of the record*
**Help**
 *A description is limited to 255 characters.*

Period
### Period

**Description**
 *Period of the Calendar*
**Help**
 *The Period indicates an exclusive range of dates for a calendar.*

Account Date
### Account Date

**Description**
 *Accounting Date*
**Help**
 *The Accounting Date indicates the date to be used on the General Ledger account entries generated from this document. It is also used for any currency conversion.*

Posting Type
### Posting Type

**Description**
 *The type of posted amount for the transaction*
**Help**
 *The Posting Type indicates the type of amount (Actual, Budget, Reservation, Commitment, Statistical) the transaction.*

Transaction Date
### Transaction Date

**Description**
 *Transaction Date*
**Help**
 *The Transaction Date indicates the date of the transaction.*

Account
### Account

**Description**
 *Account used*
**Help**
 *The (natural) account used*

Sub Account
### Sub Account

**Description**
 *Sub account for Element Value*
**Help**
 *The Element Value (e.g. Account) may have optional sub accounts for further detail. The sub account is dependent on the value of the account, so a further specification. If the sub-accounts are more or less the same, consider using another accounting dimension.*

Business Partner
### Business Partner

**Description**
 *Identifies a Business Partner*
**Help**
 *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*

Project
### Project

**Description**
 *Financial Project*
**Help**
 *A Project allows you to track and control internal or external activities.*

Project Phase
### Project Phase

**Description**
 *Phase of a Project*

Project Task
### Project Task

**Description**
 *Actual Project Task in a Phase*
**Help**
 *A Project Task in a Project Phase represents the actual work.*

Sales Region
### Sales Region

**Description**
 *Sales coverage region*
**Help**
 *The Sales Region indicates a specific area of sales coverage.*

Campaign
### Campaign

**Description**
 *Marketing Campaign*
**Help**
 *The Campaign defines a unique marketing program.  Projects can be associated with a pre defined Marketing Campaign.  You can then report based on a specific Campaign.*

Trx Organization
### Trx Organization

**Description**
 *Performing or initiating organization*
**Help**
 *The organization which performs or initiates this transaction (for another organization).  The owning Organization may not be the transaction organization in a service bureau environment, with centralized services, and inter-organization transactions.*

Location From
### Location From

**Description**
 *Location that inventory was moved from*
**Help**
 *The Location From indicates the location that a product was moved from.*

Location To
### Location To

**Description**
 *Location that inventory was moved to*
**Help**
 *The Location To indicates the location that a product was moved to.*

Activity
### Activity

**Description**
 *Business Activity*
**Help**
 *Activities indicate tasks that are performed and used to utilize Activity based Costing*

User List 1
### User List 1

**Description**
 *User defined list element #1*
**Help**
 *The user defined element displays the optional elements that have been defined for this account combination.*

User List 2
### User List 2

**Description**
 *User defined list element #2*
**Help**
 *The user defined element displays the optional elements that have been defined for this account combination.*

User List 3
### User List 3

**Description**
 *User defined list element #3*
**Help**
 *The user defined element displays the optional elements that have been defined for this account combination.*

User List 4
### User List 4

**Description**
 *User defined list element #4*
**Help**
 *The user defined element displays the optional elements that have been defined for this account combination.*

User Element 1
### User Element 1

**Description**
 *User defined accounting Element*
**Help**
 *A user defined accounting element refers to a Adempiere table. This allows to use any table content as an accounting dimension (e.g. Project Task).  Note that User Elements are optional and are populated from the context of the document (i.e. not requested)*

User Element 2
### User Element 2

**Description**
 *User defined accounting Element*
**Help**
 *A user defined accounting element refers to a Adempiere table. This allows to use any table content as an accounting dimension (e.g. Project Task).  Note that User Elements are optional and are populated from the context of the document (i.e. not requested)*

GL Category
### GL Category

**Description**
 *General Ledger Category*
**Help**
 *The General Ledger Category is an optional, user defined method of grouping journal lines.*

Budget
### Budget

**Description**
 *General Ledger Budget*
**Help**
 *The General Ledger Budget identifies a user defined budget.  These can be used in reporting as a comparison against your actual amounts.*

Tax
### Tax

**Description**
 *Tax identifier*
**Help**
 *The Tax indicates the type of tax used in document line.*

Locator
### Locator

**Description**
 *Warehouse Locator*
**Help**
 *The Locator indicates where in a Warehouse a product is located.*

Currency
### Currency

**Description**
 *The Currency for this record*
**Help**
 *Indicates the Currency to be used when processing or reporting on this record*

Source Debit
### Source Debit

**Description**
 *Source Debit Amount*
**Help**
 *The Source Debit Amount indicates the credit amount for this line in the source currency.*

Source Credit
### Source Credit

**Description**
 *Source Credit Amount*
**Help**
 *The Source Credit Amount indicates the credit amount for this line in the source currency.*

Accounted Debit
### Accounted Debit

**Description**
 *Accounted Debit Amount*
**Help**
 *The Account Debit Amount indicates the transaction amount converted to this organization's accounting currency*

Accounted Credit
### Accounted Credit

**Description**
 *Accounted Credit Amount*
**Help**
 *The Account Credit Amount indicates the transaction amount converted to this organization's accounting currency*

Product
### Product

**Description**
 *Product, Service, Item*
**Help**
 *Identifies an item which is either purchased or sold in this organization.*

UOM
### UOM

**Description**
 *Unit of Measure*
**Help**
 *The UOM defines a unique non monetary Unit of Measure*

Quantity
### Quantity

**Description**
 *Quantity*
**Help**
 *The Quantity indicates the number of a specific product or item for this document.*
