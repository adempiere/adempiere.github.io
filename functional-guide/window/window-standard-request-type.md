
Standard Request Type
# Standard Request Type


Maintain Standard Request Types

Help
## Help

Standard Request Types are used to generate the requests. Options are Account Inquiry, Warranty Issue, etc.

Window Type
### Window Type

**Maintain**

:::tip
The Sales Transaction checkbox indicates if this item is a Sales Transaction.
:::

Tabs
## Tabs


Standard Request Type
### Standard Request Type

**Description**
 *Standard Type of request (e.g. Inquiry, Complaint, ..)*
**Help**
 *Standard Request Types are used to generate the requests. Options are Account Inquiry, Warranty Issue, etc.*

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

Search Key
### Search Key

**Description**
 *Search key for the record in the format required - must be unique*
**Help**
 *A search key allows you a fast method of finding a particular record.
If you leave the search key empty, the system automatically creates a numeric number.  The document sequence used for this fallback number is defined in the "Maintain Sequence" window with the name "DocumentNo_<TableName>", where TableName is the actual name of the table (e.g. C_Order).*

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

Sales Transaction
### Sales Transaction

**Description**
 *This is a Sales Transaction*
**Help**
 *The Sales Transaction checkbox indicates if this item is a Sales Transaction.*

Table
### Table

**Description**
 *Database Table information*
**Help**
 *The Database Table provides the information of the table definition*

Event Model Validator
### Event Model Validator


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

Valid from
### Valid from

**Description**
 *Valid from including this date (first day)*
**Help**
 *The Valid From date indicates the first day of a date range*

Valid to
### Valid to

**Description**
 *Valid to including this date (last day)*
**Help**
 *The Valid To date indicates the last day of a date range*

Sql WHERE
### Sql WHERE

**Description**
 *Fully qualified SQL WHERE clause*
**Help**
 *The Where Clause indicates the SQL WHERE clause to use for record selection. The WHERE clause is added to the query. Fully qualified means "tablename.columnname".*

Standard Request Type
### Standard Request Type

**Description**
 *Standard Request Type*

Standard Request
### Standard Request

**Description**
 *Define Standard Request*
**Help**
 *The Standard Request Tab defines any Request submitted by a Business Partner or internally.*

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

Sequence
### Sequence

**Description**
 *Method of ordering records; lowest number comes first*
**Help**
 *The Sequence indicates the order of records*

Active
### Active

**Description**
 *The record is active in the system*
**Help**
 *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*

Summary
### Summary

**Description**
 *Textual summary of this request*
**Help**
 *The Summary allows free form text entry of a recap of this request.*

Entry Confidentiality
### Entry Confidentiality

**Description**
 *Confidentiality of the individual entry*

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

Priority
### Priority

**Description**
 *Indicates if this request is of a high, medium or low priority.*
**Help**
 *The Priority indicates the importance of this request.*

Due type
### Due type

**Description**
 *Status of the next action for this Request*
**Help**
 *The Due Type indicates if this request is Due, Overdue or Scheduled.*

Status
### Status

**Description**
 *Request Status*
**Help**
 *Status if the request (open, closed, investigating, ..)*

Task Status
### Task Status

**Description**
 *Status of the Task*
**Help**
 *Completion Rate and Status of the Task*

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

Duration
### Duration

**Description**
 *Normal Duration in Duration Unit*
**Help**
 *Expected (normal) Length of time for the execution*

Duration Unit
### Duration Unit

**Description**
 *Unit of Duration*
**Help**
 *Unit to define the length of time for the execution*
