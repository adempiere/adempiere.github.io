
Element
# Element


Maintain System Elements

Help
## Help

The System Element Window is the Central Repository for Field Names Descriptions and Help/Comments

Window Type
### Window Type

**Maintain**

```
The Sales Transaction checkbox indicates if this item is a Sales Transaction.
```

Tabs
## Tabs


Element
### Element

**Description**
 *Element*
**Help**
 *The Element Tab defines each system level element.*

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

DB Column Name
### DB Column Name

**Description**
 *Name of the column in the database*
**Help**
 *The Column Name indicates the name of a column on a table as defined in the database.*

Name
### Name

**Description**
 *Alphanumeric identifier of the entity*
**Help**
 *The name of an entity (record) is used as an default search option in addition to the search key. The name is up to 60 characters in length.*

Print Text
### Print Text

**Description**
 *The label text to be printed on a document or correspondence.*
**Help**
 *The Label to be printed indicates the name that will be printed on a document or correspondence. The max length is 2000 characters.*

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

Entity Type
### Entity Type

**Description**
 *Dictionary Entity Type; Determines ownership and synchronization*
**Help**
 *The Entity Types "Dictionary", "Adempiere" and "Application" might be automatically synchronized and customizations deleted or overwritten.  

For customizations, copy the entity and select "User"!*

Reference
### Reference

**Description**
 *System Reference and Validation*
**Help**
 *The Reference could be a display type, list or table validation.*

Length
### Length

**Description**
 *Length of the column in the database*
**Help**
 *The Length indicates the length of a column as defined in the database.*

Reference Key
### Reference Key

**Description**
 *Required to specify, if data type is Table or List*
**Help**
 *The Reference Value indicates where the reference values are stored.  It must be specified if the data type is Table or List.*

PO Name
### PO Name

**Description**
 *Name on PO Screens*

PO Print name
### PO Print name

**Description**
 *Print name on PO Screens/Reports*

PO Description
### PO Description

**Description**
 *Description in PO Screens*

PO Help
### PO Help

**Description**
 *Help for PO Screens*

Translation
### Translation


```
The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.
The Translation Tab checkbox indicate if a tab contains translation information. To display translation information, enable this in Tools>Preference.
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

System Element
### System Element

**Description**
 *System Element enables the central maintenance of column description and help.*
**Help**
 *The System Element allows for the central maintenance of help, descriptions and terminology for a database column.*

Language
### Language

**Description**
 *Language for this entity*
**Help**
 *The Language identifies the language to use for display and formatting*

Active
### Active

**Description**
 *The record is active in the system*
**Help**
 *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*

Translated
### Translated

**Description**
 *This column is translated*
**Help**
 *The Translated checkbox indicates if this column is translated.*

Name
### Name

**Description**
 *Alphanumeric identifier of the entity*
**Help**
 *The name of an entity (record) is used as an default search option in addition to the search key. The name is up to 60 characters in length.*

Print Text
### Print Text

**Description**
 *The label text to be printed on a document or correspondence.*
**Help**
 *The Label to be printed indicates the name that will be printed on a document or correspondence. The max length is 2000 characters.*

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

PO Name
### PO Name

**Description**
 *Name on PO Screens*

PO Print name
### PO Print name

**Description**
 *Print name on PO Screens/Reports*

PO Description
### PO Description

**Description**
 *Description in PO Screens*

PO Help
### PO Help

**Description**
 *Help for PO Screens*

Used in Column
### Used in Column

**Description**
 *Used  in Column*
**Help**
 *The Used in Column Tab defines the table and column this element resides in.*

```
The Read Only indicates that this field may only be Read.  It may not be updated.
```
Fields
## Fields


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

DB Column Name
### DB Column Name

**Description**
 *Name of the column in the database*
**Help**
 *The Column Name indicates the name of a column on a table as defined in the database.*

Used in Process Parameter
### Used in Process Parameter


```
The Read Only indicates that this field may only be Read.  It may not be updated.
```
Fields
## Fields


Process
### Process

**Description**
 *Process or Report*
**Help**
 *The Process field identifies a unique Process or Report in the system.*

Process Parameter
### Process Parameter


DB Column Name
### DB Column Name

**Description**
 *Name of the column in the database*
**Help**
 *The Column Name indicates the name of a column on a table as defined in the database.*
