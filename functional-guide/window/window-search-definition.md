
Search Definition
# Search Definition


Define transactioncodes for the QuickSearch bar

Window Type
### Window Type

**Maintain**

```
The Sales Transaction checkbox indicates if this item is a Sales Transaction.
```

Tabs
## Tabs


Searches
### Searches


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

Transaction Code
### Transaction Code

**Description**
 *The transaction code represents the search definition*

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

Default
### Default

**Description**
 *Default value*
**Help**
 *The Default Checkbox indicates if this record will be used as a default value.*

Search Type
### Search Type

**Description**
 *Which kind of search is used (Query or Table)*

Table
### Table

**Description**
 *Database Table information*
**Help**
 *The Database Table provides the information of the table definition*

Column
### Column

**Description**
 *Column in the table*
**Help**
 *Link to the database column of the table*

Query
### Query

**Description**
 *SQL*

Data Type
### Data Type

**Description**
 *Type of data*

Window
### Window

**Description**
 *Data entry or display window*
**Help**
 *The Window field identifies a unique Window in the system.*

PO Window
### PO Window

**Description**
 *Purchase Order Window*
**Help**
 *Window for Purchase Order (AP) Zooms*
