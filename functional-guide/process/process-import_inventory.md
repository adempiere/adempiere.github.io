
Import Inventory
# Import Inventory


Import Physical Inventory

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

```
The field must have a value for the record to be saved to the database.
```
Organization
### Organization

**Description**
 *Organizational entity within client*
**Help**
 *An organization is a unit of your client or legal entity - examples are store, department. You can share data between organizations.*

```
The field must have a value for the record to be saved to the database.
```
Locator
### Locator

**Description**
 *Warehouse Locator*
**Help**
 *The Locator indicates where in a Warehouse a product is located.*

```
The field must have a value for the record to be saved to the database.
```
Movement Date
### Movement Date

**Description**
 *Date a product was moved in or out of inventory*
**Help**
 *The Movement Date indicates the date that a product moved in or out of inventory.  This is the result of a shipment, receipt or inventory movement.*

```
The field must have a value for the record to be saved to the database.
```
Delete old imported records
### Delete old imported records

**Description**
 *Before processing delete old imported records in the import table*

Update Costing
### Update Costing


Accounting Schema
### Accounting Schema

**Description**
 *Rules for accounting*
**Help**
 *An Accounting Schema defines the rules used in accounting such as costing method, currency and calendar*

Cost Type
### Cost Type

**Description**
 *Type of Cost (e.g. Current, Plan, Future)*
**Help**
 *You can define multiple cost types. A cost type selected in an Accounting Schema is used for accounting.*

Cost Element
### Cost Element

**Description**
 *Product Cost Element*

Trx Organization
### Trx Organization

**Description**
 *Performing or initiating organization*
**Help**
 *The organization which performs or initiates this transaction (for another organization).  The owning Organization may not be the transaction organization in a service bureau environment, with centralized services, and inter-organization transactions.*
