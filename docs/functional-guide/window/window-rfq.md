
RfQ
# RfQ


Manage Request for Quotations

Help
## Help

Request for Quotation to be sent out to vendors of a RfQ Topic. After Vendor selection, optionally create Sales Order or Quote for Customer as well as Purchase Order  for Vendor(s)

Window Type
### Window Type

**Transaction**

:::tip
The Sales Transaction checkbox indicates if this item is a Sales Transaction.
:::

Tabs
## Tabs


RfQ
### RfQ

**Description**
 *Request for Quotation*
**Help**
 *Request for Quotation to be sent out to vendors of a RfQ Topic. After Vendor selection, optionally create Sales Order or Quote for Customer as well as Purchase Order  for Vendor(s)*

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

Sales Representative
### Sales Representative

**Description**
 *Sales Representative or Company Agent*
**Help**
 *The Sales Representative indicates the Sales Rep for this Region.  Any Sales Rep must be a valid internal user.*

RfQ Topic
### RfQ Topic

**Description**
 *Topic for Request for Quotations*
**Help**
 *A Request for Quotation Topic allows you to maintain a subscriber list of potential Vendors to respond to RfQs*

RfQ Type
### RfQ Type

**Description**
 *Request for Quotation Type*

Quote All Quantities
### Quote All Quantities

**Description**
 *Suppliers are requested to provide responses for all quantities*
**Help**
 *If selected, the response to the Request for Quotation needs to have a price for all Quantities*

Quote Total Amt
### Quote Total Amt

**Description**
 *The response can have just the total amount for the RfQ*
**Help**
 *If not selected, the response must be provided per line*

Invited Vendors Only
### Invited Vendors Only

**Description**
 *Only invited vendors can respond to an RfQ*
**Help**
 *The Request for Quotation is only visible to the invited vendors*

Self-Service
### Self-Service

**Description**
 *This is a Self-Service entry or this entry can be changed via Self-Service*
**Help**
 *Self-Service allows users to enter data or update their data.  The flag indicates, that this record was entered or created via Self-Service or that the user can change it via the Self-Service functionality.*

Responses Accepted
### Responses Accepted

**Description**
 *Are Responses to the Request for Quotation accepted*
**Help**
 *If selected, responses for the RfQ are accepted*

Response Date
### Response Date

**Description**
 *Date of the Response*
**Help**
 *Date of the Response*

Work Start
### Work Start

**Description**
 *Date when work is (planned to be) started*

Currency
### Currency

**Description**
 *The Currency for this record*
**Help**
 *Indicates the Currency to be used when processing or reporting on this record*

Delivery Days
### Delivery Days

**Description**
 *Number of Days (planned) until Delivery*

Work Complete
### Work Complete

**Description**
 *Date when work is (planned to be) complete*

Create & Invite
### Create & Invite

**Description**
 *Create RfQ and Invite Vendors*
**Help**
 *Create (missing) RfQ Responses and optionally send EMail Invitation/Reminder to Vendors to respond to RfQ*

Rank Responses
### Rank Responses

**Description**
 *Rank Completed RfQ Responses*
**Help**
 *Invalid responses are ranked with 999 per Quantity. The Quantity Responses are ranked among each other and the RfQ Best Response updated.  The response Lines is maked as Selected winner, where the line quantity purchase quantity is selected.  A total winner is only selected, if the RfQ type is "Quote All Lines" or "Quote Total only".

Then the rankings of all Quantity Responses are added for the total ranking of the response. The response with the lowest total ranking is marked as Selected Winner.*

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

Margin %
### Margin %

**Description**
 *Margin for a product as a percentage*
**Help**
 *The Margin indicates the margin for this product as a percentage of the limit price and selling price.*

Create Sales Order
### Create Sales Order

**Description**
 *Create Sales Order*
**Help**
 *A Sales Order is created for the entered Business Partner.  A sales order line is created for each RfQ line quantity, where "Offer Quantity" is selected.  If on the RfQ Line Quantity, an offer amount is entered (not 0), that price is used. 
If a magin is entered on RfQ Line Quantity, it overwrites the general margin.  The margin is the percentage added to the Best Response Amount.*

Order
### Order

**Description**
 *Order*
**Help**
 *The Order is a control document.  The  Order is complete when the quantity ordered is the same as the quantity shipped and invoiced.  When you close an order, unshipped (backordered) quantities are cancelled.*

Create Purchase Order
### Create Purchase Order

**Description**
 *Create Purchase Order(s) for RfQ Winner(s)*
**Help**
 *Create purchase order(s) for the resonse(s) and lines marked as Selected Winner using the selected Purchase Quantity (in RfQ Line Quantity) . If a Response is marked as Selected Winner, all lines are created (and Selected Winner of other responses ignored).  If there is no response marked as Selected Winner, the lines are used.*

Copy Lines
### Copy Lines

**Description**
 *Copy Lines from another RfQ*

Close RfQ
### Close RfQ

**Description**
 *Close RfQ and Responses*
**Help**
 *Close the RfQ and all it's Responses*

Processed
### Processed

**Description**
 *The document has been processed*
**Help**
 *The Processed checkbox indicates that a document has been processed.*

Line
### Line

**Description**
 *RfQ Line*
**Help**
 *Request for Quotation Line*

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

RfQ
### RfQ

**Description**
 *Request for Quotation*
**Help**
 *Request for Quotation to be sent out to vendors of a RfQ Topic. After Vendor selection, optionally create Sales Order or Quote for Customer as well as Purchase Order  for Vendor(s)*

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

Work Start
### Work Start

**Description**
 *Date when work is (planned to be) started*

Delivery Days
### Delivery Days

**Description**
 *Number of Days (planned) until Delivery*

Work Complete
### Work Complete

**Description**
 *Date when work is (planned to be) complete*

Quantity
### Quantity

**Description**
 *RfQ Line Quantity*
**Help**
 *Request for Quotation Line Quantity - You may request a quotation for different quantities*

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

RfQ Line
### RfQ Line

**Description**
 *Request for Quotation Line*
**Help**
 *Request for Quotation Line*

Active
### Active

**Description**
 *The record is active in the system*
**Help**
 *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*

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

RfQ Quantity
### RfQ Quantity

**Description**
 *The quantity is used when generating RfQ Responses*
**Help**
 *When generating the RfQ Responses, this quantity is included*

Benchmark Price
### Benchmark Price

**Description**
 *Price to compare responses to*

Purchase Quantity
### Purchase Quantity

**Description**
 *This quantity is used in the Purchase Order to the Supplier*
**Help**
 *When multiple quantities are used in an Request for Quotation, the selected Quantity is used for generating the purchase order.  If none selected the lowest number is used.*

Best Response Amount
### Best Response Amount

**Description**
 *Best Response Amount*
**Help**
 *Filled by Rank Response Process*

Offer Quantity
### Offer Quantity

**Description**
 *This quantity is used in the Offer to the Customer*
**Help**
 *When multiple quantities are used in an Request for Quotation, the selected Quantity is used for generating the offer.  If none selected the lowest number is used.*

Offer Amount
### Offer Amount

**Description**
 *Amount of the Offer*

Margin %
### Margin %

**Description**
 *Margin for a product as a percentage*
**Help**
 *The Margin indicates the margin for this product as a percentage of the limit price and selling price.*