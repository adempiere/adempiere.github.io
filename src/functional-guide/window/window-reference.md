
Reference
# Reference


Maintain System References

Help
## Help

The Reference Window defines field/display types and validations. This window is for System Admin use only.

Window Type
### Window Type

**Maintain**

:::tip
The Sales Transaction checkbox indicates if this item is a Sales Transaction.
:::

Tabs
## Tabs


Reference
### Reference

**Description**
 *Reference header definitions*
**Help**
 *The Reference Tab defines the references that are used to validate data*

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

Entity Type
### Entity Type

**Description**
 *Dictionary Entity Type; Determines ownership and synchronization*
**Help**
 *The Entity Types "Dictionary", "Adempiere" and "Application" might be automatically synchronized and customizations deleted or overwritten.  

For customizations, copy the entity and select "User"!*

Validation type
### Validation type

**Description**
 *Different method of validating data*
**Help**
 *The Validation Type indicates the validation method to use.  These include list, table or data type validation.*

Value Format
### Value Format

**Description**
 *Format of the value; Can contain fixed format elements, Variables: "_lLoOaAcCa09"*
**Help**
 *\ **Validation elements:**\ 
 	(Space) any character
_	Space (fixed character)
l	any Letter a..Z NO space
L	any Letter a..Z NO space converted to upper case
o	any Letter a..Z or space
O	any Letter a..Z or space converted to upper case
a	any Letters & Digits NO space
A	any Letters & Digits NO space converted to upper case
c	any Letters & Digits or space
C	any Letters & Digits or space converted to upper case
0	Digits 0..9 NO space
9	Digits 0..9 or space

Example of format "(000)_000-0000"*

Order By Value
### Order By Value

**Description**
 *Order list using the value column instead of the name column*
**Help**
 *Order list using the value column instead of the name column*

Reference Translation
### Reference Translation


:::tip
The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.
The Translation Tab checkbox indicate if a tab contains translation information. To display translation information, enable this in Tools>Preference.
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

Reference
### Reference

**Description**
 *System Reference and Validation*
**Help**
 *The Reference could be a display type, list or table validation.*

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

List Validation
### List Validation

**Description**
 *Reference List*
**Help**
 *The List Validation Tab defines lists to validate data*

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

Reference
### Reference

**Description**
 *System Reference and Validation*
**Help**
 *The Reference could be a display type, list or table validation.*

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

List Translation
### List Translation


:::tip
The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.
The Translation Tab checkbox indicate if a tab contains translation information. To display translation information, enable this in Tools>Preference.
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

Reference List
### Reference List

**Description**
 *Reference List based on Table*
**Help**
 *The Reference List field indicates a list of reference values from a database tables.  Reference lists populate drop down list boxes in data entry screens*

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

Description
### Description

**Description**
 *Optional short description of the record*
**Help**
 *A description is limited to 255 characters.*

Table Validation
### Table Validation

**Description**
 *Table validation*
**Help**
 *The Table Validation Tab defines tables to validate data*

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

Reference
### Reference

**Description**
 *System Reference and Validation*
**Help**
 *The Reference could be a display type, list or table validation.*

Table
### Table

**Description**
 *Database Table information*
**Help**
 *The Database Table provides the information of the table definition*

Key column
### Key column

**Description**
 *Unique identifier of a record*
**Help**
 *The Key Column indicates that this the unique identifier of a record on this table.*

Display Identifier
### Display Identifier

**Description**
 *Display the record identifier*
**Help**
 *Display the columns that are marked as part of the identifier for this table.*

Display column
### Display column

**Description**
 *Column that will display*
**Help**
 *The Display Column indicates the column that will display.*

Display Value
### Display Value

**Description**
 *Displays Value column with the Display column*
**Help**
 *The Display Value checkbox indicates if the value column will display with the display column.*

Display SQL
### Display SQL

**Description**
 *SQL for display of lookup value*
**Help**
 *Fully qualified subquery SQL*

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

Sql WHERE
### Sql WHERE

**Description**
 *Fully qualified SQL WHERE clause*
**Help**
 *The Where Clause indicates the SQL WHERE clause to use for record selection. The WHERE clause is added to the query. Fully qualified means "tablename.columnname".*

Sql ORDER BY
### Sql ORDER BY

**Description**
 *Fully qualified ORDER BY clause*
**Help**
 *The ORDER BY Clause indicates the SQL ORDER BY clause to use for record selection*

Window
### Window

**Description**
 *Data entry or display window*
**Help**
 *The Window field identifies a unique Window in the system.*

Alert
### Alert

**Description**
 *Display alert message when referenced record is accessed*

Used in Column
### Used in Column

**Description**
 *Used in Column (Reference)*

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

Table
### Table

**Description**
 *Database Table information*
**Help**
 *The Database Table provides the information of the table definition*

DB Column Name
### DB Column Name

**Description**
 *Name of the column in the database*
**Help**
 *The Column Name indicates the name of a column on a table as defined in the database.*

System Element
### System Element

**Description**
 *System Element enables the central maintenance of column description and help.*
**Help**
 *The System Element allows for the central maintenance of help, descriptions and terminology for a database column.*

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

Length
### Length

**Description**
 *Length of the column in the database*
**Help**
 *The Length indicates the length of a column as defined in the database.*

Reference
### Reference

**Description**
 *System Reference and Validation*
**Help**
 *The Reference could be a display type, list or table validation.*

Reference Key
### Reference Key

**Description**
 *Required to specify, if data type is Table or List*
**Help**
 *The Reference Value indicates where the reference values are stored.  It must be specified if the data type is Table or List.*

Dynamic Validation
### Dynamic Validation

**Description**
 *Dynamic Validation Rule*
**Help**
 *These rules define how an entry is determined to valid. You can use variables for dynamic (context sensitive) validation.*
