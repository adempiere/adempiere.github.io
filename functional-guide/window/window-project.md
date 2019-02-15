
Project
# Project


Maintain Projects

Help
## Help

The Project Window is used to define the projects which will can be tracked by phases and tasks.

Window Type
### Window Type

**Transaction**


Tabs
## Tabs


Project
### Project

**Description**
 *Define Project*
**Help**
 *The Project Tab is used to define the Value, Name and Description for each project.  It also is defines the tracks the amounts assigned to, committed to and used for this project. Note that when the project Type is changed, the Phases and Tasks are re-created.*

```
The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.
If not selected, the user cannot create a new Record.  This is automatically disabled, if the Tab is Read Only.
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

Assign members
### Assign members

**Description**
 *Assign members to Project*
**Help**
 *Assign members to Project*

Note
### Note

**Description**
 *Optional additional user defined information*
**Help**
 *The Note field allows for optional entry of user defined information regarding this record*

Line Level
### Line Level

**Description**
 *Project Line Level*
**Help**
 *Level on which Project Lines are maintained*

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
 *Identifies the (ship from) address for this Business Partner*
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

Company Agent
### Company Agent

**Description**
 *Purchase or Company Agent*
**Help**
 *Purchase agent for the document. Any Sales Rep must be a valid internal user.*

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

Copy Details
### Copy Details

**Description**
 *Copy Lines/Phases/Tasks from other Project*

Close Project
### Close Project


Project Line
### Project Line

**Description**
 *Maintain Project Lines*
**Help**
 *Maintain Project Level Lines*

```
If not selected, the user cannot create a new Record.  This is automatically disabled, if the Tab is Read Only.
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

Project
### Project

**Description**
 *Financial Project*
**Help**
 *A Project allows you to track and control internal or external activities.*

Line No
### Line No

**Description**
 *Unique line for this document*
**Help**
 *Indicates the unique line for a document.  It will also control the display order of the lines within a document.*

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

Product Category
### Product Category

**Description**
 *Category of a Product*
**Help**
 *Identifies the category which this product belongs to.  Product categories are used for pricing and selection.*

Purchased
### Purchased

**Description**
 *Organization purchases this product*
**Help**
 *The Purchased check box indicates if this product is purchased by this organization.*

Vendor
### Vendor

**Description**
 *The Vendor of the product/service*

Bill of Materials
### Bill of Materials

**Description**
 *Bill of Materials*
**Help**
 *The Bill of Materials check box indicates if this product consists of a bill of materials.*

BOM & Formula
### BOM & Formula

**Description**
 *BOM & Formula*

Workflow
### Workflow

**Description**
 *Workflow or combination of tasks*
**Help**
 *The Workflow field identifies a unique Workflow in the system.*

Resource Assignment
### Resource Assignment

**Description**
 *Resource Assignment*

Planned Price
### Planned Price

**Description**
 *Planned price for this project line*
**Help**
 *The Planned Price indicates the anticipated price for this project line.*

Planned Quantity
### Planned Quantity

**Description**
 *Planned quantity for this project*
**Help**
 *The Planned Quantity indicates the anticipated quantity for this project or project line*

Get Price
### Get Price

**Description**
 *Get Price for Project Line based on Project Price List*

Planned Amount
### Planned Amount

**Description**
 *Planned amount for this project*
**Help**
 *The Planned Amount indicates the anticipated amount for this project or project line.*

Printed
### Printed

**Description**
 *Indicates if this document / line is printed*
**Help**
 *The Printed checkbox indicates if this document or line will included when printing.*

Planned Margin
### Planned Margin

**Description**
 *Project's planned margin amount*
**Help**
 *The Planned Margin Amount indicates the anticipated margin amount for this project or project line.*

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

Sales Order
### Sales Order

**Description**
 *Sales Order*
**Help**
 *The Order is a control document.  The  Order is complete when the quantity ordered is the same as the quantity shipped and invoiced.  When you close an order, unshipped (backordered) quantities are cancelled.*

Purchase Order
### Purchase Order

**Description**
 *Purchase Order*

Manufacturing Order
### Manufacturing Order

**Description**
 *Manufacturing Order*

Project Issue
### Project Issue

**Description**
 *Project Issues (Material, Labor)*
**Help**
 *Issues to the project initiated by the "Issue to Project" process. You can issue Receipts, Time and Expenses, or Stock.*

Processed
### Processed

**Description**
 *The document has been processed*
**Help**
 *The Processed checkbox indicates that a document has been processed.*

Members
### Members

**Description**
 *Project Members*
**Help**
 *Maintenance Project Member*

```
If not selected, the user cannot create a new Record.  This is automatically disabled, if the Tab is Read Only.
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

Phase
### Phase

**Description**
 *Maintain Actual Project Phase*
**Help**
 *Actual Phase of the Project with Status information - generated from Phase of Project Type.*

```
If not selected, the user cannot create a new Record.  This is automatically disabled, if the Tab is Read Only.
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

Project
### Project

**Description**
 *Financial Project*
**Help**
 *A Project allows you to track and control internal or external activities.*

Standard Phase
### Standard Phase

**Description**
 *Standard Phase of the Project Type*
**Help**
 *Phase of the project with standard performance information with standard work*

Sequence
### Sequence

**Description**
 *Method of ordering records; lowest number comes first*
**Help**
 *The Sequence indicates the order of records*

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

Comment/Help
### Comment/Help

**Description**
 *Comment or Hint*
**Help**
 *The Help field contains a hint, comment or help about the use of this item.*

Active
### Active

**Description**
 *The record is active in the system*
**Help**
 *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*

Responsible
### Responsible

**Description**
 *Responsible*
**Help**
 *Having an obligation to do something, or having control over or care for someone, as part of one's job or role.*

Priority
### Priority

**Description**
 *Priority of a document*
**Help**
 *The Priority indicates the importance (high, medium, low) of this document*

Project Status
### Project Status

**Description**
 *Status for Project, Phase or Task*

Percentage completed
### Percentage completed

**Description**
 *Percentage completed*
**Help**
 *Defines the completion percentage for a project on a scale where 100% indicates that was completed*

Duration Unit
### Duration Unit

**Description**
 *Unit of Duration*
**Help**
 *Unit to define the length of time for the execution*

Complete
### Complete

**Description**
 *It is complete*
**Help**
 *Indication that this is complete*

Estimated Duration
### Estimated Duration

**Description**
 *Estimated Duration*
**Help**
 *Roughly calculate or judge the value, number, quantity, or extent of duration for an activity.*

Duration Real
### Duration Real


Indefinite
### Indefinite

**Description**
 *Indefinite*
**Help**
 *lasting for an unknown or unstated length of time.*

Is Milestone
### Is Milestone


Is Recurrent
### Is Recurrent

**Description**
 *The flag Is Recurrent, indicates if a project task is recurring*
**Help**
 *The flag Is Recurrent, indicates if a project task is recurring. If so, the Project Processor will generate new project task based on frequency type, frequency, and a maximum number of recurrences, until either the scheduled end date or the maximum number of recurrences is reached. On the other hand, also the complete recurring tasks are discarded.*

Deadline
### Deadline

**Description**
 *Deadline*
**Help**
 *The latest time or date by which something should be completed.*

Frequency Type
### Frequency Type

**Description**
 *Frequency of event*
**Help**
 *The frequency type is used for calculating the date of the next event.*

Frequency
### Frequency

**Description**
 *Frequency of events*
**Help**
 *The frequency is used in conjunction with the frequency type in determining an event. Example: If the Frequency Type is Week and the Frequency is 2 - it is every two weeks.*

Maximum Runs
### Maximum Runs

**Description**
 *Number of recurring runs*
**Help**
 *Number of recurring documents to be generated in total*

Remaining Runs
### Remaining Runs

**Description**
 *Number of recurring runs remaining*
**Help**
 *Number of recurring documents to be still generated*

Date next run
### Date next run

**Description**
 *Date the process will run next*
**Help**
 *The Date Next Run indicates the next time this process will run.*

Date last run
### Date last run

**Description**
 *Date the process was last run.*
**Help**
 *The Date Last Run indicates the last time that a process was run.*

Start Schedule
### Start Schedule

**Description**
 *Scheduled start date for this Order*

Finish Schedule
### Finish Schedule

**Description**
 *Scheduled Finish date for this Order*

Start Date
### Start Date

**Description**
 *First effective day (inclusive)*
**Help**
 *The Start Date indicates the first or starting date*

End Date
### End Date

**Description**
 *Last effective date (inclusive)*
**Help**
 *The End Date indicates the last date in this range.*

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

Invoice Rule
### Invoice Rule

**Description**
 *Invoice Rule for the project*
**Help**
 *The Invoice Rule for the project determines how orders (and consequently invoices) are created.  The selection on project level can be overwritten on Phase or Task*

Planned Amount
### Planned Amount

**Description**
 *Planned amount for this project*
**Help**
 *The Planned Amount indicates the anticipated amount for this project or project line.*

Product
### Product

**Description**
 *Product, Service, Item*
**Help**
 *Identifies an item which is either purchased or sold in this organization.*

Quantity
### Quantity

**Description**
 *Quantity*
**Help**
 *The Quantity indicates the number of a specific product or item for this document.*

Purchased
### Purchased

**Description**
 *Organization purchases this product*
**Help**
 *The Purchased check box indicates if this product is purchased by this organization.*

Vendor
### Vendor

**Description**
 *The Vendor of the product/service*

Bill of Materials
### Bill of Materials

**Description**
 *Bill of Materials*
**Help**
 *The Bill of Materials check box indicates if this product consists of a bill of materials.*

BOM & Formula
### BOM & Formula

**Description**
 *BOM & Formula*

Workflow
### Workflow

**Description**
 *Workflow or combination of tasks*
**Help**
 *The Workflow field identifies a unique Workflow in the system.*

Committed Amount
### Committed Amount

**Description**
 *The (legal) commitment amount*
**Help**
 *The commitment amount is independent from the planned amount. You would use the planned amount for your realistic estimation, which might be higher or lower than the commitment amount.*

Generate Sales Order
### Generate Sales Order

**Description**
 *Generate Sales Order from Project*
**Help**
 *The Generate Sales Order process will generate a new Order document based on the project phase or tasks. A price list and warehouse/service point must be defined on the project.  If a product is defined on phase level, the Phase information is used as the basis for the Order (milestone invoicing) - otherwise the individual tasks.*

Sales Order
### Sales Order

**Description**
 *Sales Order*
**Help**
 *The Order is a control document.  The  Order is complete when the quantity ordered is the same as the quantity shipped and invoiced.  When you close an order, unshipped (backordered) quantities are cancelled.*

Purchase Order
### Purchase Order

**Description**
 *Purchase Order*

Manufacturing Order
### Manufacturing Order

**Description**
 *Manufacturing Order*

Phase Line
### Phase Line

**Description**
 *Project Lines of Phase*
**Help**
 *Maintain Project Lines on Phase Level*

```
If not selected, the user cannot create a new Record.  This is automatically disabled, if the Tab is Read Only.
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

Project Phase
### Project Phase

**Description**
 *Phase of a Project*

Line No
### Line No

**Description**
 *Unique line for this document*
**Help**
 *Indicates the unique line for a document.  It will also control the display order of the lines within a document.*

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

Product Category
### Product Category

**Description**
 *Category of a Product*
**Help**
 *Identifies the category which this product belongs to.  Product categories are used for pricing and selection.*

Purchased
### Purchased

**Description**
 *Organization purchases this product*
**Help**
 *The Purchased check box indicates if this product is purchased by this organization.*

Vendor
### Vendor

**Description**
 *The Vendor of the product/service*

Bill of Materials
### Bill of Materials

**Description**
 *Bill of Materials*
**Help**
 *The Bill of Materials check box indicates if this product consists of a bill of materials.*

BOM & Formula
### BOM & Formula

**Description**
 *BOM & Formula*

Workflow
### Workflow

**Description**
 *Workflow or combination of tasks*
**Help**
 *The Workflow field identifies a unique Workflow in the system.*

Resource Assignment
### Resource Assignment

**Description**
 *Resource Assignment*

Planned Price
### Planned Price

**Description**
 *Planned price for this project line*
**Help**
 *The Planned Price indicates the anticipated price for this project line.*

Planned Quantity
### Planned Quantity

**Description**
 *Planned quantity for this project*
**Help**
 *The Planned Quantity indicates the anticipated quantity for this project or project line*

Get Price
### Get Price

**Description**
 *Get Price for Project Line based on Project Price List*

Planned Amount
### Planned Amount

**Description**
 *Planned amount for this project*
**Help**
 *The Planned Amount indicates the anticipated amount for this project or project line.*

Printed
### Printed

**Description**
 *Indicates if this document / line is printed*
**Help**
 *The Printed checkbox indicates if this document or line will included when printing.*

Planned Margin
### Planned Margin

**Description**
 *Project's planned margin amount*
**Help**
 *The Planned Margin Amount indicates the anticipated margin amount for this project or project line.*

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

Sales Order
### Sales Order

**Description**
 *Sales Order*
**Help**
 *The Order is a control document.  The  Order is complete when the quantity ordered is the same as the quantity shipped and invoiced.  When you close an order, unshipped (backordered) quantities are cancelled.*

Purchase Order
### Purchase Order

**Description**
 *Purchase Order*

Manufacturing Order
### Manufacturing Order

**Description**
 *Manufacturing Order*

Project Issue
### Project Issue

**Description**
 *Project Issues (Material, Labor)*
**Help**
 *Issues to the project initiated by the "Issue to Project" process. You can issue Receipts, Time and Expenses, or Stock.*

Processed
### Processed

**Description**
 *The document has been processed*
**Help**
 *The Processed checkbox indicates that a document has been processed.*

Task
### Task

**Description**
 *Actual Project Task*
**Help**
 *A Project Task in a Project Phase represents the actual work.*

```
If not selected, the user cannot create a new Record.  This is automatically disabled, if the Tab is Read Only.
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

Project Phase
### Project Phase

**Description**
 *Phase of a Project*

Standard Task
### Standard Task

**Description**
 *Standard Project Type Task*
**Help**
 *Standard Project Task in a Project Phase with standard effort*

Sequence
### Sequence

**Description**
 *Method of ordering records; lowest number comes first*
**Help**
 *The Sequence indicates the order of records*

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

Comment/Help
### Comment/Help

**Description**
 *Comment or Hint*
**Help**
 *The Help field contains a hint, comment or help about the use of this item.*

Active
### Active

**Description**
 *The record is active in the system*
**Help**
 *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*

Responsible
### Responsible

**Description**
 *Responsible*
**Help**
 *Having an obligation to do something, or having control over or care for someone, as part of one's job or role.*

Priority
### Priority

**Description**
 *Priority of a document*
**Help**
 *The Priority indicates the importance (high, medium, low) of this document*

Project Status
### Project Status

**Description**
 *Status for Project, Phase or Task*

Percentage completed
### Percentage completed

**Description**
 *Percentage completed*
**Help**
 *Defines the completion percentage for a project on a scale where 100% indicates that was completed*

Duration Unit
### Duration Unit

**Description**
 *Unit of Duration*
**Help**
 *Unit to define the length of time for the execution*

Complete
### Complete

**Description**
 *It is complete*
**Help**
 *Indication that this is complete*

Estimated Duration
### Estimated Duration

**Description**
 *Estimated Duration*
**Help**
 *Roughly calculate or judge the value, number, quantity, or extent of duration for an activity.*

Duration Real
### Duration Real


Indefinite
### Indefinite

**Description**
 *Indefinite*
**Help**
 *lasting for an unknown or unstated length of time.*

Is Milestone
### Is Milestone


Is Recurrent
### Is Recurrent

**Description**
 *The flag Is Recurrent, indicates if a project task is recurring*
**Help**
 *The flag Is Recurrent, indicates if a project task is recurring. If so, the Project Processor will generate new project task based on frequency type, frequency, and a maximum number of recurrences, until either the scheduled end date or the maximum number of recurrences is reached. On the other hand, also the complete recurring tasks are discarded.*

Frequency Type
### Frequency Type

**Description**
 *Frequency of event*
**Help**
 *The frequency type is used for calculating the date of the next event.*

Frequency
### Frequency

**Description**
 *Frequency of events*
**Help**
 *The frequency is used in conjunction with the frequency type in determining an event. Example: If the Frequency Type is Week and the Frequency is 2 - it is every two weeks.*

Maximum Runs
### Maximum Runs

**Description**
 *Number of recurring runs*
**Help**
 *Number of recurring documents to be generated in total*

Remaining Runs
### Remaining Runs

**Description**
 *Number of recurring runs remaining*
**Help**
 *Number of recurring documents to be still generated*

Date next run
### Date next run

**Description**
 *Date the process will run next*
**Help**
 *The Date Next Run indicates the next time this process will run.*

Date last run
### Date last run

**Description**
 *Date the process was last run.*
**Help**
 *The Date Last Run indicates the last time that a process was run.*

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

Project Task Category
### Project Task Category

**Description**
 *Set Category for project task*

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

Invoice Rule
### Invoice Rule

**Description**
 *Invoice Rule for the project*
**Help**
 *The Invoice Rule for the project determines how orders (and consequently invoices) are created.  The selection on project level can be overwritten on Phase or Task*

Planned Amount
### Planned Amount

**Description**
 *Planned amount for this project*
**Help**
 *The Planned Amount indicates the anticipated amount for this project or project line.*

Product
### Product

**Description**
 *Product, Service, Item*
**Help**
 *Identifies an item which is either purchased or sold in this organization.*

Quantity
### Quantity

**Description**
 *Quantity*
**Help**
 *The Quantity indicates the number of a specific product or item for this document.*

Purchased
### Purchased

**Description**
 *Organization purchases this product*
**Help**
 *The Purchased check box indicates if this product is purchased by this organization.*

Vendor
### Vendor

**Description**
 *The Vendor of the product/service*

Bill of Materials
### Bill of Materials

**Description**
 *Bill of Materials*
**Help**
 *The Bill of Materials check box indicates if this product consists of a bill of materials.*

BOM & Formula
### BOM & Formula

**Description**
 *BOM & Formula*

Workflow
### Workflow

**Description**
 *Workflow or combination of tasks*
**Help**
 *The Workflow field identifies a unique Workflow in the system.*

Committed Amount
### Committed Amount

**Description**
 *The (legal) commitment amount*
**Help**
 *The commitment amount is independent from the planned amount. You would use the planned amount for your realistic estimation, which might be higher or lower than the commitment amount.*

Generate Sales Order
### Generate Sales Order

**Description**
 *Generate Sales Order from Project*
**Help**
 *The Generate Sales Order process will generate a new Order document based on the project phase or tasks. A price list and warehouse/service point must be defined on the project.  If a product is defined on phase level, the Phase information is used as the basis for the Order (milestone invoicing) - otherwise the individual tasks.*

Sales Order
### Sales Order

**Description**
 *Sales Order*
**Help**
 *The Sales Order is a control document.  The  Order is complete when the quantity ordered is the same as the quantity shipped and invoiced.  When you close an order, unshipped (backordered) quantities are cancelled.*

Purchase Order
### Purchase Order

**Description**
 *Purchase Order*

Manufacturing Order
### Manufacturing Order

**Description**
 *Manufacturing Order*

Task Request
### Task Request

**Description**
 *Task Request*
**Help**
 *Requests assigned this task*

```
If not selected, the user cannot create a new Record.  This is automatically disabled, if the Tab is Read Only.
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

Document No
### Document No

**Description**
 *Document sequence number of the document*
**Help**
 *The document number is usually automatically generated by the system and determined by the document type of the document. If the document is not saved, the preliminary number is displayed in "<>".

If the document type of your document has no automatic document sequence defined, the field is empty if you create a new document. This is for documents which usually have an external number (like vendor invoice).  If you leave the field empty, the system will generate a document number for you. The document sequence used for this fallback number is defined in the "Maintain Sequence" window with the name "DocumentNo_<TableName>", where TableName is the actual name of the table (e.g. C_Order).*

Due type
### Due type

**Description**
 *Status of the next action for this Request*
**Help**
 *The Due Type indicates if this request is Due, Overdue or Scheduled.*

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

Company Agent
### Company Agent

**Description**
 *Purchase or Company Agent*
**Help**
 *Purchase agent for the document. Any Sales Rep must be a valid internal user.*

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

Purchase Order
### Purchase Order

**Description**
 *Purchase Order*
**Help**
 *The Purchase Order is a control document.  The Purchase Order is complete when the quantity ordered is the same as the quantity shipped and invoiced.  When you close an order, unshipped (backordered) quantities are cancelled.*

Purchase Order Line
### Purchase Order Line

**Description**
 *Purchase Order Line*
**Help**
 *The Purchase Order Line is a unique identifier for a line in an order.*

Receipt
### Receipt

**Description**
 *Material Receipt Document*
**Help**
 *The Material Shipment / Receipt*

Receipt Line
### Receipt Line

**Description**
 *Line on Receipt document*

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

Task Line
### Task Line

**Description**
 *Project Lines of Tasks*
**Help**
 *Maintain Project Lines of Tasks*

```
If not selected, the user cannot create a new Record.  This is automatically disabled, if the Tab is Read Only.
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

Project Task
### Project Task

**Description**
 *Actual Project Task in a Phase*
**Help**
 *A Project Task in a Project Phase represents the actual work.*

Line No
### Line No

**Description**
 *Unique line for this document*
**Help**
 *Indicates the unique line for a document.  It will also control the display order of the lines within a document.*

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

Product Category
### Product Category

**Description**
 *Category of a Product*
**Help**
 *Identifies the category which this product belongs to.  Product categories are used for pricing and selection.*

Purchased
### Purchased

**Description**
 *Organization purchases this product*
**Help**
 *The Purchased check box indicates if this product is purchased by this organization.*

Vendor
### Vendor

**Description**
 *The Vendor of the product/service*

Bill of Materials
### Bill of Materials

**Description**
 *Bill of Materials*
**Help**
 *The Bill of Materials check box indicates if this product consists of a bill of materials.*

BOM & Formula
### BOM & Formula

**Description**
 *BOM & Formula*

Workflow
### Workflow

**Description**
 *Workflow or combination of tasks*
**Help**
 *The Workflow field identifies a unique Workflow in the system.*

Resource Assignment
### Resource Assignment

**Description**
 *Resource Assignment*

Planned Price
### Planned Price

**Description**
 *Planned price for this project line*
**Help**
 *The Planned Price indicates the anticipated price for this project line.*

Planned Quantity
### Planned Quantity

**Description**
 *Planned quantity for this project*
**Help**
 *The Planned Quantity indicates the anticipated quantity for this project or project line*

Get Price
### Get Price

**Description**
 *Get Price for Project Line based on Project Price List*

Planned Amount
### Planned Amount

**Description**
 *Planned amount for this project*
**Help**
 *The Planned Amount indicates the anticipated amount for this project or project line.*

Printed
### Printed

**Description**
 *Indicates if this document / line is printed*
**Help**
 *The Printed checkbox indicates if this document or line will included when printing.*

Planned Margin
### Planned Margin

**Description**
 *Project's planned margin amount*
**Help**
 *The Planned Margin Amount indicates the anticipated margin amount for this project or project line.*

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

Sales Order
### Sales Order

**Description**
 *Sales Order*
**Help**
 *The Sales Order is a control document.  The Purchase Order is complete when the quantity ordered is the same as the quantity shipped and invoiced.  When you close an order, unshipped (backordered) quantities are cancelled.*

Purchase Order
### Purchase Order

**Description**
 *Purchase Order*

Manufacturing Order
### Manufacturing Order

**Description**
 *Manufacturing Order*

Project Issue
### Project Issue

**Description**
 *Project Issues (Material, Labor)*
**Help**
 *Issues to the project initiated by the "Issue to Project" process. You can issue Receipts, Time and Expenses, or Stock.*

Processed
### Processed

**Description**
 *The document has been processed*
**Help**
 *The Processed checkbox indicates that a document has been processed.*

Accounting
### Accounting

**Description**
 *Define Project Accounting*
**Help**
 *The Accounting Tab is used to define the Asset Account to use when a project is completed and the associated asset realized.*

```
The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.
The Accounting Tab checkbox indicates if this window contains accounting information. To display accounting information, enable this in Tools>Preference and Role.
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

Project
### Project

**Description**
 *Financial Project*
**Help**
 *A Project allows you to track and control internal or external activities.*

Accounting Schema
### Accounting Schema

**Description**
 *Rules for accounting*
**Help**
 *An Accounting Schema defines the rules used in accounting such as costing method, currency and calendar*

Active
### Active

**Description**
 *The record is active in the system*
**Help**
 *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*

Project Asset
### Project Asset

**Description**
 *Project Asset Account*
**Help**
 *The Project Asset account is the account used as the final asset account in capital projects*

Work In Progress
### Work In Progress

**Description**
 *Account for Work in Progress*
**Help**
 *The Work in Process account is the account used in capital projects until the project is completed*
