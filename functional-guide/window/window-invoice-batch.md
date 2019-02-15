
Invoice Batch
# Invoice Batch


Expense Invoice Batch

Help
## Help

Enter expense invoices in batch.  After creating the lines, the actual invoices are created when processing the batch

Window Type
### Window Type

**Transaction**


Tabs
## Tabs


Invoice Batch
### Invoice Batch

**Description**
 *Enter Expense Invoice Batch Header*
**Help**
 *Set Currency and decide if this for AR (sales) Invoices or AP (vendor) invoices. Optionally enter a Control amount.*

:::tip
The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.
If not selected, the user cannot create a new Record.  This is automatically disabled, if the Tab is Read Only.
:::
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

Description
### Description

**Description**
 *Optional short description of the record*
**Help**
 *A description is limited to 255 characters.*

Document Date
### Document Date

**Description**
 *Date of the Document*
**Help**
 *The Document Date indicates the date the document was generated.  It may or may not be the same as the accounting date.*

Sales Transaction
### Sales Transaction

**Description**
 *This is a Sales Transaction*
**Help**
 *The Sales Transaction checkbox indicates if this item is a Sales Transaction.*

Company Agent
### Company Agent

**Description**
 *Purchase or Company Agent*
**Help**
 *Purchase agent for the document. Any Sales Rep must be a valid internal user.*

Currency
### Currency

**Description**
 *The Currency for this record*
**Help**
 *Indicates the Currency to be used when processing or reporting on this record*

Currency Type
### Currency Type

**Description**
 *Currency Conversion Rate Type*
**Help**
 *The Currency Conversion Rate Type lets you define different type of rates, e.g. Spot, Corporate and/or Sell/Buy rates.*

Control Amount
### Control Amount

**Description**
 *If not zero, the Debit amount of the document must be equal this amount*
**Help**
 *If the control amount is zero, no check is performed.
Otherwise the total Debit amount must be equal to the control amount, before the document is processed.*

Document Amt
### Document Amt

**Description**
 *Document Amount*

Create Invoices
### Create Invoices


Copy Lines
### Copy Lines

**Description**
 *Copy Lines from other Invoice*

Processed
### Processed

**Description**
 *The document has been processed*
**Help**
 *The Processed checkbox indicates that a document has been processed.*

Batch Line
### Batch Line

**Description**
 *Enter Expense Invoice Batch Line*
**Help**
 *A new invoice is created, if there is a different Document Number, Business Partner or Location (address).
Note that the Document Number may be overwritten - depending on the Number control of the selected Document Type.*

:::tip
If not selected, the user cannot create a new Record.  This is automatically disabled, if the Tab is Read Only.
:::
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

Invoice Batch
### Invoice Batch

**Description**
 *Expense Invoice Batch Header*

Line No
### Line No

**Description**
 *Unique line for this document*
**Help**
 *Indicates the unique line for a document.  It will also control the display order of the lines within a document.*

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

Description
### Description

**Description**
 *Optional short description of the record*
**Help**
 *A description is limited to 255 characters.*

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
 *Identifies the (ship from) address for this Business Partner*
**Help**
 *The Partner address indicates the location of a Business Partner*

User/Contact
### User/Contact

**Description**
 *User within the system - Internal or Business Partner Contact*
**Help**
 *The User identifies a unique user in the system. This could be an internal user or a business partner contact*

Quantity
### Quantity

**Description**
 *The Quantity Entered is based on the selected UoM*
**Help**
 *The Quantity Entered is converted to base product UoM quantity*

Charge
### Charge

**Description**
 *Additional document charges*
**Help**
 *The Charge indicates a type of Charge (Handling, Shipping, Restocking)*

Price
### Price

**Description**
 *Price Entered - the price based on the selected/base UoM*
**Help**
 *The price entered is converted to the actual price based on the UoM conversion*

Price includes Tax
### Price includes Tax

**Description**
 *Tax is included in the price*
**Help**
 *The Tax Included checkbox indicates if the prices include tax.  This is also known as the gross price.*

Tax
### Tax

**Description**
 *Tax identifier*
**Help**
 *The Tax indicates the type of tax used in document line.*

Line Amount
### Line Amount

**Description**
 *Line Extended Amount (Quantity * Actual Price) without Freight and Charges*
**Help**
 *Indicates the extended line amount based on the quantity and the actual price.  Any additional charges or freight are not included.  The Amount may or may not include tax.  If the price list is inclusive tax, the line amount is the same as the line total.*

Tax Amount
### Tax Amount

**Description**
 *Tax Amount for a document*
**Help**
 *The Tax Amount displays the total tax amount for a document.*

Line Total
### Line Total

**Description**
 *Total line amount incl. Tax*
**Help**
 *Total line amount*

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

Processed
### Processed

**Description**
 *The document has been processed*
**Help**
 *The Processed checkbox indicates that a document has been processed.*