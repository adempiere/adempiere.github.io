
Migration Scripts
# Migration Scripts



Window Type
### Window Type

**Maintain**


Tabs
## Tabs


Migration Scripts
### Migration Scripts


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

Name
### Name

**Description**
 *Alphanumeric identifier of the entity*
**Help**
 *The name of an entity (record) is used as an default search option in addition to the search key. The name is up to 60 characters in length.*

File Name
### File Name

**Description**
 *Name of the local file or URL*
**Help**
 *Name of a file in the local directory space - or URL (file://.., http://.., ftp://..)*

Developer Name
### Developer Name


Apply Script
### Apply Script


Project
### Project

**Description**
 *Name of the Project*

Description
### Description

**Description**
 *Optional short description of the record*
**Help**
 *A description is limited to 255 characters.*

Reference
### Reference

**Description**
 *Reference for this record*
**Help**
 *The Reference displays the source document number.*

URL
### URL

**Description**
 *Full URL address - e.g. http://www.adempiere.org*
**Help**
 *The URL defines an fully qualified web address like http://www.adempiere.org*

Release No
### Release No

**Description**
 *Internal Release Number*

Status
### Status

**Description**
 *Status of the currently running check*
**Help**
 *Status of the currently running check*

Apply Migration Scripts
### Apply Migration Scripts


Script
### Script

**Description**
 *Dynamic Java Language Script to calculate result*
**Help**
 *Use Java language constructs to define the result of the calculation*
