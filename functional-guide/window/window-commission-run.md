
Commission Run
# Commission Run


Check and modify Commissions

Help
## Help

The Commission Run Window displays the results of processing commissions.  When the Generate Commission process is selected from the Commissions Window, the results are displayed here. If the result is satisfactory, generate an AP invoice to pay the commission.

Window Type
### Window Type

**Transaction**


Tabs
## Tabs


Commission Run
### Commission Run

**Description**
 *Commission run for a period*
**Help**
 *Commission run for a period defined in the Commission window.*

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

Document Type
### Document Type

**Description**
 *Document type or rules*
**Help**
 *The Document Type determines document sequence and processing rules*

Document Date
### Document Date

**Description**
 *Date of the Document*
**Help**
 *The Document Date indicates the date the document was generated.  It may or may not be the same as the accounting date.*

Commission Group
### Commission Group


Commission
### Commission

**Description**
 *Commission*
**Help**
 *The Commission Rules or internal or external company agents, sales reps or vendors.*

Description
### Description

**Description**
 *Optional short description of the record*
**Help**
 *A description is limited to 255 characters.*

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

Recalculate
### Recalculate

**Description**
 *Allow recalculation*
**Help**
 *When active, a recalculation is allowed*

Grand Total
### Grand Total

**Description**
 *Total amount of document*
**Help**
 *The Grand Total displays the total amount including Tax and Freight in document currency*

Document Status
### Document Status

**Description**
 *The current status of the document*
**Help**
 *The Document Status indicates the status of a document at this time.  If you want to change the document status, use the Document Action field*

Create Invoice
### Create Invoice

**Description**
 *Create Invoice from Commission Calculation*

Process Commission Run
### Process Commission Run


Processed
### Processed

**Description**
 *The document has been processed*
**Help**
 *The Processed checkbox indicates that a document has been processed.*

Approved
### Approved

**Description**
 *Indicates if this document requires approval*
**Help**
 *The Approved checkbox indicates if this document requires approval before it can be processed.*

Commission Amount
### Commission Amount

**Description**
 *Commission line amounts*
**Help**
 *For each commission line, a line is generated.  You can overwrite the amount and quantity to modify the commission amount, but the suggested way is creating additional Commission Detail lines.  Please be aware that manual changes will not reconcile with the Commission Details.*

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

Commission Run
### Commission Run

**Description**
 *Commission Run or Process*
**Help**
 *The Commission Run is a unique system defined identifier of a specific run of commission.  When a Commission is processed on the Commission Screen, the Commission Run will display.*

Commission Line
### Commission Line

**Description**
 *Commission Line*
**Help**
 *The Commission Line is a unique instance of a Commission Run.  If the commission run was done in summary mode then there will be a single line representing the selected documents totals.  If the commission run was done in detail mode then each document that was included in the run will have its own commission line.*

Business Partner
### Business Partner

**Description**
 *Identifies a Business Partner*
**Help**
 *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*

Maximum Percentage
### Maximum Percentage

**Description**
 *Maximum Percentage of the entire amount*
**Help**
 *Percentage of an amount (up to 100)*

Percentage
### Percentage

**Description**
 *Percent of the entire amount*
**Help**
 *Percentage of an amount (up to 100)*

Active
### Active

**Description**
 *The record is active in the system*
**Help**
 *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*

Converted Amount
### Converted Amount

**Description**
 *Converted Amount*
**Help**
 *The Converted Amount is the result of multiplying the Source Amount by the Conversion Rate for this target currency.*

Actual Quantity
### Actual Quantity

**Description**
 *The actual quantity*
**Help**
 *The Actual Quantity indicates the quantity as referenced on a document.*

Commission Amount
### Commission Amount

**Description**
 *Commission Amount*
**Help**
 *The Commission Amount is the total calculated commission.  It is based on the parameters as defined for this Commission Run.*

Commission Detail
### Commission Detail

**Description**
 *Commission Detail Information*
**Help**
 *You may alter the amount and quantity of the detail records, but the suggested way is to add new correcting lines.
The amounts are converted from the transaction currency to the Commission Currency (defined in the Commission window) using the start date and the spot exchange rate.*

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

Commission Amount
### Commission Amount

**Description**
 *Generated Commission Amount*
**Help**
 *The Commission Amount indicates the resulting amount from a Commission Run.*

Reference
### Reference

**Description**
 *Reference for this record*
**Help**
 *The Reference displays the source document number.*

Purchase Order Line
### Purchase Order Line

**Description**
 *Purchase Order Line*
**Help**
 *The Purchase Order Line is a unique identifier for a line in an order.*

Invoice Line
### Invoice Line

**Description**
 *Invoice Detail Line*
**Help**
 *The Invoice Line uniquely identifies a single line of an Invoice.*

Active
### Active

**Description**
 *The record is active in the system*
**Help**
 *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*

Info
### Info

**Description**
 *Information*
**Help**
 *The Information displays data from the source document line.*

Actual Amount
### Actual Amount

**Description**
 *The actual amount*
**Help**
 *Actual amount indicates the agreed upon amount for a document.*

Currency
### Currency

**Description**
 *The Currency for this record*
**Help**
 *Indicates the Currency to be used when processing or reporting on this record*

Converted Amount
### Converted Amount

**Description**
 *Converted Amount*
**Help**
 *The Converted Amount is the result of multiplying the Source Amount by the Conversion Rate for this target currency.*

Actual Quantity
### Actual Quantity

**Description**
 *The actual quantity*
**Help**
 *The Actual Quantity indicates the quantity as referenced on a document.*

Commission Amount
### Commission Amount

**Description**
 *Commission Amount*
**Help**
 *The Commission Amount is the total calculated commission.  It is based on the parameters as defined for this Commission Run.*