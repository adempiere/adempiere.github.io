
Message
# Message


Maintain Information and Error Messages

Help
## Help

The Message Window defines the Message Text and Message Tips for each system generated message.  It is for System Admin use only.

Window Type
### Window Type

**Maintain**

```
The Sales Transaction checkbox indicates if this item is a Sales Transaction.
```

Tabs
## Tabs


Message
### Message

**Description**
 *Information Error and Menu Messages*
**Help**
 *The Message Tab displays error message text and menu messages*

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

Message Type
### Message Type

**Description**
 *Type of message (Informational, Menu or Error)*
**Help**
 *The Message Type indicates the type of message being defined.  Valid message types are Informational, Menu and Error.*

Message Text
### Message Text

**Description**
 *Textual Informational, Menu or Error Message*
**Help**
 *The Message Text indicates the message that will display*

Message Tip
### Message Tip

**Description**
 *Additional tip or help for this message*
**Help**
 *The Message Tip defines additional help or information about this message.*

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

Message
### Message

**Description**
 *System Message*
**Help**
 *Information and Error messages*

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

Message Text
### Message Text

**Description**
 *Textual Informational, Menu or Error Message*
**Help**
 *The Message Text indicates the message that will display*

Message Tip
### Message Tip

**Description**
 *Additional tip or help for this message*
**Help**
 *The Message Tip defines additional help or information about this message.*
