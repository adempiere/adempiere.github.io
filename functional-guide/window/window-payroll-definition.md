
Payroll Definition
# Payroll Definition


In a company, payroll is the sum of all financial records of salaries, wages, bonuses, and deductions.

Window Type
### Window Type

**Maintain**

```
The Sales Transaction checkbox indicates if this item is a Sales Transaction.
```

Tabs
## Tabs


Payroll
### Payroll

**Description**
 *In a company, payroll is the sum of all financial records of salaries, wages, bonuses, and deductions.*

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

Ignore Default Payroll
### Ignore Default Payroll

**Description**
 *Ignore Default Payroll for Employee*

Payroll Contract
### Payroll Contract


Payment Rule
### Payment Rule

**Description**
 *How you pay the invoice*
**Help**
 *The Payment Rule indicates the method of invoice payment.*

Print Format
### Print Format

**Description**
 *Data Print Format*
**Help**
 *The print format determines how data is rendered for print.*

Charge
### Charge

**Description**
 *Additional document charges*
**Help**
 *The Charge indicates a type of Charge (Handling, Shipping, Restocking)*

Browser Global Payroll Concept
### Browser Global Payroll Concept


Processed
### Processed

**Description**
 *The document has been processed*
**Help**
 *The Processed checkbox indicates that a document has been processed.*

Post Per Employee
### Post Per Employee

**Description**
 *A Payroll is posted per employee when the value is Yes, it is posted accumulated when the value is N*

Concept Sequence
### Concept Sequence

**Description**
 *Concept Sequence*

```
null
If not selected, the user cannot create a new Record.  This is automatically disabled, if the Tab is Read Only.
```
Payroll Concepts
### Payroll Concepts

**Description**
 *Define the concepts to a Payroll ie (salaries, wages, bonuses, and deductions)*

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

Payroll
### Payroll


Name
### Name

**Description**
 *Alphanumeric identifier of the entity*
**Help**
 *The name of an entity (record) is used as an default search option in addition to the search key. The name is up to 60 characters in length.*

Global Payroll Concept
### Global Payroll Concept

**Description**
 *The Payroll Concept allows to define all the perception and deductions elements needed to define a payroll.*

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

Displayed
### Displayed

**Description**
 *Determines, if this field is displayed*
**Help**
 *If the field is displayed, the field Display Logic will determine at runtime, if it is actually displayed*

Printed
### Printed

**Description**
 *Indicates if this document / line is printed*
**Help**
 *The Printed checkbox indicates if this document or line will included when printing.*

Year
### Year

**Description**
 *Year of Payroll*

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

Payroll
### Payroll


Active
### Active

**Description**
 *The record is active in the system*
**Help**
 *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*

Year
### Year

**Description**
 *Calendar Year*
**Help**
 *The Year uniquely identifies an accounting year for a calendar.*

Quantity
### Quantity

**Description**
 *Quantity*
**Help**
 *The Quantity indicates the number of a specific product or item for this document.*

Net Days
### Net Days

**Description**
 *Net Days in which payment is due*
**Help**
 *Indicates the number of days after invoice date that payment is due.*

Start Date
### Start Date

**Description**
 *First effective day (inclusive)*
**Help**
 *The Start Date indicates the first or starting date*

Processed
### Processed

**Description**
 *The document has been processed*
**Help**
 *The Processed checkbox indicates that a document has been processed.*

HRPayroll Create Periods
### HRPayroll Create Periods


Periods
### Periods

**Description**
 *Periods of pay*

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

Payroll
### Payroll


Year
### Year

**Description**
 *Calendar Year*
**Help**
 *The Year uniquely identifies an accounting year for a calendar.*

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

Period
### Period

**Description**
 *Period of the Calendar*
**Help**
 *The Period indicates an exclusive range of dates for a calendar.*

Period No
### Period No

**Description**
 *Unique Period Number*
**Help**
 *The Period No identifies a specific period for this year. Each period is defined by a start and end date.  Date ranges for a calendar and year cannot overlap.*

Start Date
### Start Date

**Description**
 *First effective day (inclusive)*
**Help**
 *The Start Date indicates the first or starting date*

End Date
### End Date

**Description**
 *Last effective date (inclusive)*
**Help**
 *The End Date indicates the last date in this range.*

Account Date
### Account Date

**Description**
 *Accounting Date*
**Help**
 *The Accounting Date indicates the date to be used on the General Ledger account entries generated from this document. It is also used for any currency conversion.*

Processed
### Processed

**Description**
 *The document has been processed*
**Help**
 *The Processed checkbox indicates that a document has been processed.*
