
Migration
# Migration


Migration change management

Window Type
### Window Type

**Maintain**

```
The Sales Transaction checkbox indicates if this item is a Sales Transaction.
```

Tabs
## Tabs


Migration
### Migration


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

Entity Type
### Entity Type

**Description**
 *Dictionary Entity Type; Determines ownership and synchronization*
**Help**
 *The Entity Types "Dictionary", "Adempiere" and "Application" might be automatically synchronized and customizations deleted or overwritten.  

For customizations, copy the entity and select "User"!*

Release No
### Release No

**Description**
 *Internal Release Number*

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

Comments
### Comments

**Description**
 *Comments or additional information*
**Help**
 *The Comments field allows for free form entry of additional information.*

Active
### Active

**Description**
 *The record is active in the system*
**Help**
 *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*

Status Code
### Status Code


Apply migration
### Apply migration

**Description**
 *Apply or rollback migration*

Export migration to XML
### Export migration to XML

**Description**
 *Export migration to XML file*

Merge Migration
### Merge Migration


Processed
### Processed

**Description**
 *The document has been processed*
**Help**
 *The Processed checkbox indicates that a document has been processed.*

Step
### Step

**Description**
 *Migration step*

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

Comments
### Comments

**Description**
 *Comments or additional information*
**Help**
 *The Comments field allows for free form entry of additional information.*

Step type
### Step type

**Description**
 *Migration step type*

DBType
### DBType


Parse Statement
### Parse Statement

**Description**
 *Select if the SQL statement should be parsed based on terminating semi-colons.*
**Help**
 *Deselect if the SQL statement provided is a function definition (CREATE OR REPLACE FUNCTION...) rather than a collection of statements.  This prevents parsing of the function based on semi-colons which can occur in the function definition.  Also deselect this with single sql statements that have semi-colons in text within the statement.*

SQLStatement
### SQLStatement


Rollback Statement
### Rollback Statement

**Description**
 *SQL statement to rollback the current step.*

Action
### Action

**Description**
 *Indicates the Action to be performed*
**Help**
 *The Action field is a drop down list box which indicates the Action to be performed for this Item.*

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

Status Code
### Status Code


Apply migration step
### Apply migration step

**Description**
 *Apply or rollback a single migration step*

Error Msg
### Error Msg


Data
### Data

**Description**
 *Data for AD change*

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

Active
### Active

**Description**
 *The record is active in the system*
**Help**
 *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*

Column
### Column

**Description**
 *Column in the table*
**Help**
 *Link to the database column of the table*

Old Value
### Old Value

**Description**
 *The old file data*
**Help**
 *Old data overwritten in the field*

Old value null
### Old value null

**Description**
 *The old value was null.*

New Value
### New Value

**Description**
 *New field value*
**Help**
 *New data entered in the field*

New value null
### New value null

**Description**
 *The new value is null.*

Backup Value
### Backup Value

**Description**
 *The value of the column prior to migration.*

Backup value null
### Backup value null

**Description**
 *The backup value is null.*
