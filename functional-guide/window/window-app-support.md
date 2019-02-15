
App Support
# App Support


App Support for External Connection

Help
## Help

Connect ADempiere with a External Application

Window Type
### Window Type

**Maintain**

```
The Sales Transaction checkbox indicates if this item is a Sales Transaction.
```

Tabs
## Tabs


Support
### Support

**Description**
 *Support to App*

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

Search Key
### Search Key

**Description**
 *Search key for the record in the format required - must be unique*
**Help**
 *A search key allows you a fast method of finding a particular record.
If you leave the search key empty, the system automatically creates a numeric number.  The document sequence used for this fallback number is defined in the "Maintain Sequence" window with the name "DocumentNo_<TableName>", where TableName is the actual name of the table (e.g. C_Order).*

Application Type
### Application Type

**Description**
 *Application Type, used for identify a Application Type like Message Queue*
**Help**
 *You can define a type like Message Queue*

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

Default
### Default

**Description**
 *Default value*
**Help**
 *The Default Checkbox indicates if this record will be used as a default value.*

Classname
### Classname

**Description**
 *Java Classname*
**Help**
 *The Classname identifies the Java classname used by this report or process.*

Support Default Parameters
### Support Default Parameters

**Description**
 *Support to App*
**Help**
 *Default Parameters for connection*

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

App Support
### App Support

**Description**
 *App Support for External Connection*
**Help**
 *Used for define a new API for external Connection*

Active
### Active

**Description**
 *The record is active in the system*
**Help**
 *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*

Parameter Type
### Parameter Type


Reference
### Reference

**Description**
 *System Reference and Validation*
**Help**
 *The Reference could be a display type, list or table validation.*

Parameter Name
### Parameter Name


Default Parameter
### Default Parameter

**Description**
 *Default value of the parameter*
**Help**
 *The default value can be a variable like @#Date@*

Mandatory
### Mandatory

**Description**
 *Data entry is required in this column*
**Help**
 *The field must have a value for the record to be saved to the database.*

Description
### Description

**Description**
 *Optional short description of the record*
**Help**
 *A description is limited to 255 characters.*
