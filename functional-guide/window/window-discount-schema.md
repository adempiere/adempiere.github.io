
Discount Schema
# Discount Schema


Maintain Trade Discount Schema

Help
## Help

Trade discount schema calculates the trade discount percentage

Window Type
### Window Type

**Maintain**

```
The Sales Transaction checkbox indicates if this item is a Sales Transaction.
```

Tabs
## Tabs


Discount Schema
### Discount Schema

**Description**
 *Trade Discount Schema*
**Help**
 *Trade discount schema calculates the trade discount percentage*

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

Discount Type
### Discount Type

**Description**
 *Type of trade discount calculation*
**Help**
 *Type of procedure used to calculate the trade discount percentage*

Script
### Script

**Description**
 *Dynamic Java Language Script to calculate result*
**Help**
 *Use Java language constructs to define the result of the calculation*

B.Partner Flat Discount
### B.Partner Flat Discount

**Description**
 *Use flat discount defined on Business Partner Level*
**Help**
 *For calculation of the discount, use the discount defined on Business Partner Level*

Flat Discount %
### Flat Discount %

**Description**
 *Flat discount percentage*

Quantity based
### Quantity based

**Description**
 *Trade discount break level based on Quantity (not value)*
**Help**
 *The calculation of the trade discount level is based on the quantity of the order and not the value amount of the order*

Accumulation Level
### Accumulation Level

**Description**
 *Level for accumulative calculations*

Renumber
### Renumber

**Description**
 *Renumber Discount entries*

Discount Break
### Discount Break

**Description**
 *Trade discount based on breaks (steps)*

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

Discount Schema
### Discount Schema

**Description**
 *Schema to calculate the trade discount percentage*
**Help**
 *After calculation of the (standard) price, the trade discount percentage is calculated and applied resulting in the final price.*

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

Product Category
### Product Category

**Description**
 *Category of a Product*
**Help**
 *Identifies the category which this product belongs to.  Product categories are used for pricing and selection.*

Product
### Product

**Description**
 *Product, Service, Item*
**Help**
 *Identifies an item which is either purchased or sold in this organization.*

Break Value
### Break Value

**Description**
 *Low Value of trade discount break level*
**Help**
 *Starting Quantity or Amount Value for break level*

B.Partner Flat Discount
### B.Partner Flat Discount

**Description**
 *Use flat discount defined on Business Partner Level*
**Help**
 *For calculation of the discount, use the discount defined on Business Partner Level*

Break Discount %
### Break Discount %

**Description**
 *Trade Discount in Percent for the break level*
**Help**
 *Trade Discount in Percent for the break level*
