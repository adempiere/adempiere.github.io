
Sales Rep Info
# Sales Rep Info


Company Agent (Sales Rep) Information

Help
## Help

This window allows you to view Company agent related information

Window Type
### Window Type

**Query Only**

```
The Sales Transaction checkbox indicates if this item is a Sales Transaction.
```

Tabs
## Tabs


Company Agent
### Company Agent

**Description**
 *Sales Representative Selection*

```
The Read Only indicates that this field may only be Read.  It may not be updated.
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

EMail Address
### EMail Address

**Description**
 *Electronic Mail Address*
**Help**
 *The Email Address is the Electronic Mail ID for this User and should be fully qualified (e.g. joe.smith@company.com). The Email Address is used to access the self service application functionality from the web.*

Title
### Title

**Description**
 *Name this entity is referred to as*
**Help**
 *The Title indicates the name that an entity is referred to as.*

Birthday
### Birthday

**Description**
 *Birthday or Anniversary day*
**Help**
 *Birthday or Anniversary day*

Phone
### Phone

**Description**
 *Identifies a telephone number*
**Help**
 *The Phone field identifies a telephone number*

Fax
### Fax

**Description**
 *Facsimile number*
**Help**
 *The Fax identifies a facsimile number for this Business Partner or  Location*

Supervisor
### Supervisor

**Description**
 *Supervisor for this user/organization - used for escalation and approval*
**Help**
 *The Supervisor indicates who will be used for forwarding and escalating issues for this user - or for approvals.*

Trx Organization
### Trx Organization

**Description**
 *Performing or initiating organization*
**Help**
 *The organization which performs or initiates this transaction (for another organization).  The owning Organization may not be the transaction organization in a service bureau environment, with centralized services, and inter-organization transactions.*

Orders
### Orders

**Description**
 *All Orders where the Agent "owns" the Order, the Business Partner or the Product*

```
The Read Only indicates that this field may only be Read.  It may not be updated.
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

Sales Transaction
### Sales Transaction

**Description**
 *This is a Sales Transaction*
**Help**
 *The Sales Transaction checkbox indicates if this item is a Sales Transaction.*

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

Sales Representative
### Sales Representative

**Description**
 *Sales Representative or Company Agent*
**Help**
 *The Sales Representative indicates the Sales Rep for this Region.  Any Sales Rep must be a valid internal user.*

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

Delivered
### Delivered


Invoiced
### Invoiced

**Description**
 *Is this invoiced?*
**Help**
 *If selected, invoices are created*

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

Order Lines
### Order Lines

**Description**
 *All Order Lines where the Agent "owns" the Order, the Business Partner or the Product*

```
The Read Only indicates that this field may only be Read.  It may not be updated.
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

Order
### Order

**Description**
 *Order*
**Help**
 *The Order is a control document.  The  Order is complete when the quantity ordered is the same as the quantity shipped and invoiced.  When you close an order, unshipped (backordered) quantities are cancelled.*

Line No
### Line No

**Description**
 *Unique line for this document*
**Help**
 *Indicates the unique line for a document.  It will also control the display order of the lines within a document.*

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

Description
### Description

**Description**
 *Optional short description of the record*
**Help**
 *A description is limited to 255 characters.*

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

Date Delivered
### Date Delivered

**Description**
 *Date when the product was delivered*

Date Invoiced
### Date Invoiced

**Description**
 *Date printed on Invoice*
**Help**
 *The Date Invoice indicates the date printed on the invoice.*

Warehouse
### Warehouse

**Description**
 *Storage Warehouse and Service Point*
**Help**
 *The Warehouse identifies a unique Warehouse where products are stored or Services are provided.*

Product
### Product

**Description**
 *Product, Service, Item*
**Help**
 *Identifies an item which is either purchased or sold in this organization.*

Description Only
### Description Only

**Description**
 *if true, the line is just description and no transaction*
**Help**
 *If a line is Description Only, e.g. Product Inventory is not corrected. No accounting transactions are created and the amount or totals are not included in the document.  This for including descriptional detail lines, e.g. for an Work Order.*

Resource Assignment
### Resource Assignment

**Description**
 *Resource Assignment*

Attribute Set Instance
### Attribute Set Instance

**Description**
 *Product Attribute Set Instance*
**Help**
 *The values of the actual Product Attribute Instances.  The product level attributes are defined on Product level.*

Ordered Quantity
### Ordered Quantity

**Description**
 *Ordered Quantity*
**Help**
 *The Ordered Quantity indicates the quantity of a product that was ordered.*

Reserved Quantity
### Reserved Quantity

**Description**
 *Reserved Quantity*
**Help**
 *The Reserved Quantity indicates the quantity of a product that is currently reserved.*

Delivered Quantity
### Delivered Quantity

**Description**
 *Delivered Quantity*
**Help**
 *The Delivered Quantity indicates the quantity of a product that has been delivered.*

Quantity Invoiced
### Quantity Invoiced

**Description**
 *Invoiced Quantity*
**Help**
 *The Invoiced Quantity indicates the quantity of a product that have been invoiced.*

Currency
### Currency

**Description**
 *The Currency for this record*
**Help**
 *Indicates the Currency to be used when processing or reporting on this record*

Tax
### Tax

**Description**
 *Tax identifier*
**Help**
 *The Tax indicates the type of tax used in document line.*

List Price
### List Price

**Description**
 *List Price*
**Help**
 *The List Price is the official List Price in the document currency.*

Discount %
### Discount %

**Description**
 *Discount in percent*
**Help**
 *The Discount indicates the discount applied or taken as a percentage.*

Unit Price
### Unit Price

**Description**
 *Actual Price*
**Help**
 *The Actual or Unit Price indicates the Price for a product in source currency.*

Line Amount
### Line Amount

**Description**
 *Line Extended Amount (Quantity * Actual Price) without Freight and Charges*
**Help**
 *Indicates the extended line amount based on the quantity and the actual price.  Any additional charges or freight are not included.  The Amount may or may not include tax.  If the price list is inclusive tax, the line amount is the same as the line total.*

Invoices
### Invoices

**Description**
 *All Invoices where the Agent "owns" the Invoice, the Business Partner or the Product*

```
The Read Only indicates that this field may only be Read.  It may not be updated.
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

Order Reference
### Order Reference

**Description**
 *Transaction Reference Number (Sales Order, Purchase Order) of your Business Partner*
**Help**
 *The business partner order reference is the order reference for this specific transaction; Often Purchase Order numbers are given to print on Invoices for easier reference.  A standard number can be defined in the Business Partner (Customer) window.*

Order
### Order

**Description**
 *Order*
**Help**
 *The Order is a control document.  The  Order is complete when the quantity ordered is the same as the quantity shipped and invoiced.  When you close an order, unshipped (backordered) quantities are cancelled.*

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

Sales Representative
### Sales Representative

**Description**
 *Sales Representative or Company Agent*
**Help**
 *The Sales Representative indicates the Sales Rep for this Region.  Any Sales Rep must be a valid internal user.*

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

Project
### Project

**Description**
 *Financial Project*
**Help**
 *A Project allows you to track and control internal or external activities.*

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

Invoice Line
### Invoice Line

**Description**
 *All Invoice Liness where the Agent "owns" the Invoice, the Business Partner or the Product*

```
The Read Only indicates that this field may only be Read.  It may not be updated.
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

Invoice
### Invoice

**Description**
 *Invoice Identifier*
**Help**
 *The Invoice Document.*

Line No
### Line No

**Description**
 *Unique line for this document*
**Help**
 *Indicates the unique line for a document.  It will also control the display order of the lines within a document.*

Description
### Description

**Description**
 *Optional short description of the record*
**Help**
 *A description is limited to 255 characters.*

Charge
### Charge

**Description**
 *Additional document charges*
**Help**
 *The Charge indicates a type of Charge (Handling, Shipping, Restocking)*

Product
### Product

**Description**
 *Product, Service, Item*
**Help**
 *Identifies an item which is either purchased or sold in this organization.*

Description Only
### Description Only

**Description**
 *if true, the line is just description and no transaction*
**Help**
 *If a line is Description Only, e.g. Product Inventory is not corrected. No accounting transactions are created and the amount or totals are not included in the document.  This for including descriptional detail lines, e.g. for an Work Order.*

Resource Assignment
### Resource Assignment

**Description**
 *Resource Assignment*

Attribute Set Instance
### Attribute Set Instance

**Description**
 *Product Attribute Set Instance*
**Help**
 *The values of the actual Product Attribute Instances.  The product level attributes are defined on Product level.*

Quantity Invoiced
### Quantity Invoiced

**Description**
 *Invoiced Quantity*
**Help**
 *The Invoiced Quantity indicates the quantity of a product that have been invoiced.*

Unit Price
### Unit Price

**Description**
 *Actual Price*
**Help**
 *The Actual or Unit Price indicates the Price for a product in source currency.*

List Price
### List Price

**Description**
 *List Price*
**Help**
 *The List Price is the official List Price in the document currency.*

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

Tax
### Tax

**Description**
 *Tax identifier*
**Help**
 *The Tax indicates the type of tax used in document line.*

Line Total
### Line Total

**Description**
 *Total line amount incl. Tax*
**Help**
 *Total line amount*
