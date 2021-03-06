
Outbound Order
# Outbound Order


Outbound Order allow picking the products of Warehouse 

Help
## Help

The Outbound Document will generate the Shipment Customer.

Window Type
### Window Type

**Maintain**

```
The Sales Transaction checkbox indicates if this item is a Sales Transaction.
```

Tabs
## Tabs


Outbound Order
### Outbound Order


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

Sales Representative
### Sales Representative

**Description**
 *Sales Representative or Company Agent*
**Help**
 *The Sales Representative indicates the Sales Rep for this Region.  Any Sales Rep must be a valid internal user.*

Pick Date
### Pick Date

**Description**
 *Date/Time when picked for Shipment*

Ship Date
### Ship Date

**Description**
 *Shipment Date/Time*
**Help**
 *Actual Date/Time of Shipment (pick up)*

Priority
### Priority

**Description**
 *Priority of a document*
**Help**
 *The Priority indicates the importance (high, medium, low) of this document*

Drop Shipment
### Drop Shipment

**Description**
 *Drop Shipments are sent from the Vendor directly to the Customer*
**Help**
 *Drop Shipments do not cause any Inventory reservations or movements as the Shipment is from the Vendor's inventory. The Shipment of the Vendor to the Customer must be confirmed.*

Drop Shipment Partner
### Drop Shipment Partner

**Description**
 *Business Partner to ship to*
**Help**
 *If empty the business partner will be shipped to.*

Drop Shipment Location
### Drop Shipment Location

**Description**
 *Business Partner Location for shipping to*

Drop Shipment Contact
### Drop Shipment Contact

**Description**
 *Business Partner Contact for drop shipment*

Warehouse
### Warehouse

**Description**
 *Storage Warehouse and Service Point*
**Help**
 *The Warehouse identifies a unique Warehouse where products are stored or Services are provided.*

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

In & Out Bound Order
### In & Out Bound Order


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

Trx Organization
### Trx Organization

**Description**
 *Performing or initiating organization*
**Help**
 *The organization which performs or initiates this transaction (for another organization).  The owning Organization may not be the transaction organization in a service bureau environment, with centralized services, and inter-organization transactions.*

Document Status
### Document Status

**Description**
 *The current status of the document*
**Help**
 *The Document Status indicates the status of a document at this time.  If you want to change the document status, use the Document Action field*

Process In/Out Bound
### Process In/Out Bound

**Description**
 *Process In/Out Bound*
**Help**
 *Process In/Out Bound will create the Picking or Putaway  Order to pick or put the products into of Locators*

OutBound Order Line
### OutBound Order Line


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

UOM
### UOM

**Description**
 *Unit of Measure*
**Help**
 *The UOM defines a unique non monetary Unit of Measure*

Attribute Set Instance
### Attribute Set Instance

**Description**
 *Product Attribute Set Instance*
**Help**
 *The values of the actual Product Attribute Instances.  The product level attributes are defined on Product level.*

Movement Quantity
### Movement Quantity

**Description**
 *Quantity of a product moved.*
**Help**
 *The Movement Quantity indicates the quantity of a product that has been moved.*

Picked Qty
### Picked Qty


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

Description
### Description

**Description**
 *Optional short description of the record*
**Help**
 *A description is limited to 255 characters.*

Sales Order Line
### Sales Order Line

**Description**
 *Sales Order Line*
**Help**
 *The Sales Order Line is a unique identifier for a line in an order.*

MRP
### MRP

**Description**
 *MRP ID*

Distribution Order
### Distribution Order


Manufacturing Order
### Manufacturing Order

**Description**
 *Manufacturing Order*

Order
### Order

**Description**
 *Order*
**Help**
 *The Order is a control document.  The  Order is complete when the quantity ordered is the same as the quantity shipped and invoiced.  When you close an order, unshipped (backordered) quantities are cancelled.*
