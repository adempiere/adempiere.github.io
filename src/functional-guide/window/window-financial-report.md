
Financial Report
# Financial Report


Maintain Financial Reports

Help
## Help

Financial Reports are the combination of a Report Column Set and Line Set.

Window Type
### Window Type

**Maintain**

:::tip
The Sales Transaction checkbox indicates if this item is a Sales Transaction.
:::

Tabs
## Tabs


Financial Report
### Financial Report


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

Accounting Schema
### Accounting Schema

**Description**
 *Rules for accounting*
**Help**
 *An Accounting Schema defines the rules used in accounting such as costing method, currency and calendar*

Calendar
### Calendar

**Description**
 *Accounting Calendar Name*
**Help**
 *The Calendar uniquely identifies an accounting calendar.  Multiple calendars can be used.  For example you may need a standard calendar that runs from Jan 1 to Dec 31 and a fiscal calendar that runs from July 1 to June 30.*

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

Report Line Set
### Report Line Set


Report Column Set
### Report Column Set

**Description**
 *Collection of Columns for Report*
**Help**
 *The Report Column Set identifies the columns used in a Report.*

Report Cube
### Report Cube

**Description**
 *Define reporting cube for pre-calculation of summary accounting data.*
**Help**
 *Summary data will be generated for each period of the selected calendar, grouped by the selected dimensions..*

Jasper Process
### Jasper Process

**Description**
 *The Jasper Process used by the printengine if any process defined*

List Sources
### List Sources

**Description**
 *List Report Line Sources*
**Help**
 *List the Source Accounts for Summary Accounts selected*

List Transactions
### List Transactions

**Description**
 *List the report transactions*
**Help**
 *List the transactions of the report source lines*

Header Print Format
### Header Print Format


Pre Period Name
### Pre Period Name


Pos Period Name
### Pos Period Name


Create Report
### Create Report

**Description**
 *Create Financial Report*
**Help**
 *The default period is the current period. You can optionally enter other restrictions.  You can select an alternative Reporting Hierarchy.*

Print Format
### Print Format

**Description**
 *Data Print Format*
**Help**
 *The print format determines how data is rendered for print.*

Create Report (Jasper)
### Create Report (Jasper)

**Description**
 *Create Financial Report  (Jasper)*
**Help**
 *The default period is the current period. You can optionally enter other restrictions.  You can select an alternative Reporting Hierarchy.*
