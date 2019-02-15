
Import Journal
# Import Journal


Import General Ledger Batch/Journal/Line

Help
## Help

The Parameters are default values for null import record values, they do not overwrite any data.

Parameters
## Parameters


Client
### Client

**Description**
 *Client/Tenant for this installation.*
**Help**
 *A Client is a company or a legal entity. You cannot share data between Clients. Tenant is a synonym for Client.*

:::tip
The field must have a value for the record to be saved to the database.
:::
Organization
### Organization

**Description**
 *Organizational entity within client*
**Help**
 *An organization is a unit of your client or legal entity - examples are store, department. You can share data between organizations.*

:::tip
The field must have a value for the record to be saved to the database.
:::
Accounting Schema
### Accounting Schema

**Description**
 *Rules for accounting*
**Help**
 *An Accounting Schema defines the rules used in accounting such as costing method, currency and calendar*

:::tip
The field must have a value for the record to be saved to the database.
:::
Account Date
### Account Date

**Description**
 *Accounting Date*
**Help**
 *The Accounting Date indicates the date to be used on the General Ledger account entries generated from this document. It is also used for any currency conversion.*

:::tip
The field must have a value for the record to be saved to the database.
:::
Only Validate Data
### Only Validate Data

**Description**
 *Validate the date and do not process*

Import only if No Errors
### Import only if No Errors

**Description**
 *Only start the import, if there are no validation Errors*

Delete old imported records
### Delete old imported records

**Description**
 *Before processing delete old imported records in the import table*
