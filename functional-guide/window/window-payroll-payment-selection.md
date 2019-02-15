
Payroll Payment Selection
# Payroll Payment Selection


Select Payroll Concept for Payment

Help
## Help

The Payroll Payment Selection Window allows you to select and process the Payroll Concepts you want to pay.
(a) You can create a Payment Selection and select the Payroll Concepts or generate based on Payroll Process.  You can change the amount to be paid or delete payroll concept, you do not want to pay.

(b) If you are happy with the Payment Selection, you create the payments.

(c) You print or export your payments in the Window Payroll Payment Print/Export

Window Type
### Window Type

**Maintain**


Tabs
## Tabs


Payroll Payment Selection
### Payroll Payment Selection


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

Payroll Process
### Payroll Process


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

Bank Account
### Bank Account

**Description**
 *Account at the Bank*
**Help**
 *The Bank Account identifies an account at this Bank.*

Payment date
### Payment date

**Description**
 *Date Payment made*
**Help**
 *The Payment Date indicates the date the payment was made.*

Approved
### Approved

**Description**
 *Indicates if this document requires approval*
**Help**
 *The Approved checkbox indicates if this document requires approval before it can be processed.*

Payroll Payment Selection ID
### Payroll Payment Selection ID


Total Amount
### Total Amount

**Description**
 *Total Amount*
**Help**
 *The Total Amount indicates the total document amount.*

Create From ...
### Create From ...


Payroll Prepare Payment
### Payroll Prepare Payment

**Description**
 *Create Prepared Payments (Checks) to be paid*
**Help**
 *You create the actual Payments via Payroll Payment Print/Export*

Processed
### Processed

**Description**
 *The document has been processed*
**Help**
 *The Processed checkbox indicates that a document has been processed.*

Payroll Payment Selection Line
### Payroll Payment Selection Line


:::tip
If not selected, the user cannot create a new Record.  This is automatically disabled, if the Tab is Read Only.
:::
Fields
## Fields


Payroll Movement
### Payroll Movement


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

Active
### Active

**Description**
 *The record is active in the system*
**Help**
 *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*

Payment Rule
### Payment Rule

**Description**
 *How you pay the invoice*
**Help**
 *The Payment Rule indicates the method of invoice payment.*

Open Amount
### Open Amount

**Description**
 *Open item amount*

Payment amount
### Payment amount

**Description**
 *Amount being paid*
**Help**
 *Indicates the amount this payment is for.  The payment amount can be for single or multiple invoices or a partial payment for an invoice.*

Payroll Payment Selection Check
### Payroll Payment Selection Check


:::tip
The Read Only indicates that this field may only be Read.  It may not be updated.
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

Payroll Payment Selection ID
### Payroll Payment Selection ID


Business Partner
### Business Partner

**Description**
 *Identifies a Business Partner*
**Help**
 *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*

Document No
### Document No

**Description**
 *Document sequence number of the document*
**Help**
 *The document number is usually automatically generated by the system and determined by the document type of the document. If the document is not saved, the preliminary number is displayed in "<>".

If the document type of your document has no automatic document sequence defined, the field is empty if you create a new document. This is for documents which usually have an external number (like vendor invoice).  If you leave the field empty, the system will generate a document number for you. The document sequence used for this fallback number is defined in the "Maintain Sequence" window with the name "DocumentNo_<TableName>", where TableName is the actual name of the table (e.g. C_Order).*

Payment Rule
### Payment Rule

**Description**
 *How you pay the invoice*
**Help**
 *The Payment Rule indicates the method of invoice payment.*

Quantity
### Quantity

**Description**
 *Quantity*
**Help**
 *The Quantity indicates the number of a specific product or item for this document.*

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

Payment
### Payment

**Description**
 *Payment identifier*
**Help**
 *The Payment is a unique identifier of this payment.*

Receipt
### Receipt

**Description**
 *This is a sales transaction (receipt)*

Printed
### Printed

**Description**
 *Indicates if this document / line is printed*
**Help**
 *The Printed checkbox indicates if this document or line will included when printing.*

Processed
### Processed

**Description**
 *The document has been processed*
**Help**
 *The Processed checkbox indicates that a document has been processed.*
