
Package
# Package


Manage Shipment Packages

Help
## Help

A Shipment can have one or more Packages.  A Package may be tracked.

Window Type
### Window Type

**Maintain**


Tabs
## Tabs


Package
### Package

**Description**
 *Shipment Package*
**Help**
 *A Shipment can have one or more Packages.  A Package may be tracked.*

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

Active
### Active

**Description**
 *The record is active in the system*
**Help**
 *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*

Receipt
### Receipt

**Description**
 *Material Receipt Document*
**Help**
 *The Material Shipment / Receipt*

Shipper
### Shipper

**Description**
 *Method or manner of product delivery*
**Help**
 *The Shipper indicates the method of delivering product*

Ship Date
### Ship Date

**Description**
 *Shipment Date/Time*
**Help**
 *Actual Date/Time of Shipment (pick up)*

Tracking Info
### Tracking Info


Date received
### Date received

**Description**
 *Date a product was received*
**Help**
 *The Date Received indicates the date that product was received.*

Info Received
### Info Received

**Description**
 *Information of the receipt of the package (acknowledgement)*

Package Line
### Package Line

**Description**
 *The detail content of the Package*
**Help**
 *Link to the shipment line*

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

Package
### Package

**Description**
 *Shipment Package*
**Help**
 *A Shipment can have one or more Packages.  A Package may be individually tracked.*

Receipt Line
### Receipt Line

**Description**
 *Line on Receipt document*

Quantity
### Quantity

**Description**
 *Quantity*
**Help**
 *The Quantity indicates the number of a specific product or item for this document.*

Description
### Description

**Description**
 *Optional short description of the record*
**Help**
 *A description is limited to 255 characters.*