
Distribution Order
# Distribution Order


Distribution Order allow create Order inter warehouse to supply a demand 

Help
## Help

Distribution Order allow create Order inter warehouse to supply a demand 

Window Type
### Window Type

**Maintain**


Tabs
## Tabs


Distribution Order
### Distribution Order

**Description**
 *Distribution Order allow create Order inter warehouse to supply a demand*
**Help**
 *Distribution Order allow create Order inter warehouse to supply a demand*

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
 *Identifies the (ship from) address for this Business Partner*
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

Distribution Order
### Distribution Order


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

Process Distribution Order
### Process Distribution Order


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


Distribution Order Line
### Distribution Order Line

**Description**
 *Distribution Order Line*

```
If not selected, the user cannot create a new Record.  This is automatically disabled, if the Tab is Read Only.
```
Fields
## Fields


Line No
### Line No

**Description**
 *Unique line for this document*
**Help**
 *Indicates the unique line for a document.  It will also control the display order of the lines within a document.*

Product
### Product

**Description**
 *Product, Service, Item*
**Help**
 *Identifies an item which is either purchased or sold in this organization.*

Date Promised
### Date Promised

**Description**
 *Date Order was promised*
**Help**
 *The Date Promised indicates the date, if any, that an Order was promised for.*

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

Ordered Quantity
### Ordered Quantity

**Description**
 *Ordered Quantity*
**Help**
 *The Ordered Quantity indicates the quantity of a product that was ordered.*

Confirmed Quantity
### Confirmed Quantity

**Description**
 *Confirmation of a received quantity*
**Help**
 *Confirmation of a received quantity*

Shipper
### Shipper

**Description**
 *Method or manner of product delivery*
**Help**
 *The Shipper indicates the method of delivering product*

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

Qty In Transit
### Qty In Transit


Delivered Quantity
### Delivered Quantity

**Description**
 *Delivered Quantity*
**Help**
 *The Delivered Quantity indicates the quantity of a product that has been delivered.*

Locator
### Locator

**Description**
 *Warehouse Locator*
**Help**
 *The Locator indicates where in a Warehouse a product is located.*

Locator To
### Locator To

**Description**
 *Location inventory is moved to*
**Help**
 *The Locator To indicates the location where the inventory is being moved to.*

Instance
### Instance

**Description**
 *Product Attribute Set Instance*
**Help**
 *The values of the actual Product Attribute Instances.  The product level attributes are defined on Product level.*

Instance To
### Instance To

**Description**
 *Target Product Attribute Set Instance*

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
