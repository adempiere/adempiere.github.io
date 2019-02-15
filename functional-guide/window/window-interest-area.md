
Interest Area
# Interest Area


Interest Area or Topic

Help
## Help

Interest Areas reflect interest in a topic by a contact. Interest areas can be used for marketing campaigns.

Window Type
### Window Type

**Maintain**

```
The Sales Transaction checkbox indicates if this item is a Sales Transaction.
```

Tabs
## Tabs


Interest Area
### Interest Area

**Description**
 *Interest Area or Topic*
**Help**
 *Interest Areas reflect interest in a topic by a contact. Interest areas can be used for marketing campaigns. If a list is not "Self Service", it is not visible for users via the web.*

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

Self-Service
### Self-Service

**Description**
 *This is a Self-Service entry or this entry can be changed via Self-Service*
**Help**
 *Self-Service allows users to enter data or update their data.  The flag indicates, that this record was entered or created via Self-Service or that the user can change it via the Self-Service functionality.*

Subscriptions
### Subscriptions

**Description**
 *User Subscriptions*

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

Interest Area
### Interest Area

**Description**
 *Interest Area or Topic*
**Help**
 *Interest Areas reflect interest in a topic by a contact. Interest areas can be used for marketing campaigns.*

User/Contact
### User/Contact

**Description**
 *User within the system - Internal or Business Partner Contact*
**Help**
 *The User identifies a unique user in the system. This could be an internal user or a business partner contact*

Active
### Active

**Description**
 *The record is active in the system*
**Help**
 *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*

Subscribe Date
### Subscribe Date

**Description**
 *Date the contact actively subscribed*
**Help**
 *Date the contact subscribe the interest area*

Opt-out Date
### Opt-out Date

**Description**
 *Date the contact opted out*
**Help**
 *If the field has a date, the customer opted out (unsubscribed) and cannot receive mails for the Interest Area*

LDAP Access
### LDAP Access

**Description**
 *User Access via LDAP*

```
The tab with advanced functionality is only displayed, if enabled in Tools>Preference.
The Read Only indicates that this field may only be Read.  It may not be updated.
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

Interest Area
### Interest Area

**Description**
 *Interest Area or Topic*
**Help**
 *Interest Areas reflect interest in a topic by a contact. Interest areas can be used for marketing campaigns.*

Ldap Processor
### Ldap Processor

**Description**
 *LDAP Server to authenticate and authorize external systems based on Adempiere*
**Help**
 *The LDAP Server allows third party software (e.g. Apache) to use the users defined in the system to authenticate and authorize them.  There is only one server per Adempiere system.  The "o" is the Client key and the optional "ou" is the Interest Area key.*

User/Contact
### User/Contact

**Description**
 *User within the system - Internal or Business Partner Contact*
**Help**
 *The User identifies a unique user in the system. This could be an internal user or a business partner contact*

Created
### Created

**Description**
 *Date this record was created*
**Help**
 *The Created field indicates the date that this record was created.*

Error
### Error

**Description**
 *An Error occurred in the execution*

Summary
### Summary

**Description**
 *Textual summary of this request*
**Help**
 *The Summary allows free form text entry of a recap of this request.*

Description
### Description

**Description**
 *Optional short description of the record*
**Help**
 *A description is limited to 255 characters.*
