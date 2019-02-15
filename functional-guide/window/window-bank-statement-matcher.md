
Bank Statement Matcher
# Bank Statement Matcher


Algorithm to match Bank Statement Info to Business Partners, Invoices and Payments

Help
## Help

An algorithm to find Business Partners, Invoices, Payments in imported Bank Statements

Window Type
### Window Type

**Maintain**

```
The Sales Transaction checkbox indicates if this item is a Sales Transaction.
```

Tabs
## Tabs


Bank Statement Matcher
### Bank Statement Matcher

**Description**
 *Algorithm to match Bank Statement Info to Business Partners, Invoices and Payments*
**Help**
 *An algorithm to find Business Partners, Invoices, Payments in imported Bank Statements. The class need to implement the interface org.compiere.impexp.BankStatementMatcherInterface*

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

Classname
### Classname

**Description**
 *Java Classname*
**Help**
 *The Classname identifies the Java classname used by this report or process.*

Sequence
### Sequence

**Description**
 *Method of ordering records; lowest number comes first*
**Help**
 *The Sequence indicates the order of records*

Matcher for Banks
### Matcher for Banks

**Description**
 *Matcher for Banks*
**Help**
 *Matcher for Banks*

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

Bank Statement Matcher
### Bank Statement Matcher

**Description**
 *Algorithm to match Bank Statement Info to Business Partners, Invoices and Payments*
**Help**
 *An algorithm to find Business Partners, Invoices, Payments in imported Bank Statements.  The class needs to implement org.compiere.impexp.BankStatementMatcherInterface*

Bank
### Bank

**Description**
 *Bank*
**Help**
 *The Bank is a unique identifier of a Bank for this Organization or for a Business Partner with whom this Organization transacts.*

Active
### Active

**Description**
 *The record is active in the system*
**Help**
 *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*

Sequence
### Sequence

**Description**
 *Method of ordering records; lowest number comes first*
**Help**
 *The Sequence indicates the order of records*

Description
### Description

**Description**
 *Optional short description of the record*
**Help**
 *A description is limited to 255 characters.*
