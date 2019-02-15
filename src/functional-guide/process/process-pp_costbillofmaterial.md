
Cost BOM Multi Level Review
# Cost BOM Multi Level Review


This report show every cost element to a Multi Level BOM or Formula 

Help
## Help

This report show every cost element to a Multi Level BOM or Formula 

Parameters
## Parameters


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

:::tip
The field must have a value for the record to be saved to the database.
:::
Warehouse
### Warehouse

**Description**
 *Storage Warehouse and Service Point*
**Help**
 *The Warehouse identifies a unique Warehouse where products are stored or Services are provided.*

Cost Type
### Cost Type

**Description**
 *Type of Cost (e.g. Current, Plan, Future)*
**Help**
 *You can define multiple cost types. A cost type selected in an Accounting Schema is used for accounting.*

:::tip
The field must have a value for the record to be saved to the database.
:::
Costing Method
### Costing Method

**Description**
 *Indicates how Costs will be calculated*
**Help**
 *The Costing Method indicates how costs will be calculated (Standard, Average, Lifo, FiFo).  The default costing method is defined on accounting schema level and can be optionally overwritten in the product category.  The costing method cannot conflict with the Material Movement Policy (defined on Product Category).*

:::tip
The field must have a value for the record to be saved to the database.
:::
Product
### Product

**Description**
 *Product, Service, Item*
**Help**
 *Identifies an item which is either purchased or sold in this organization.*

:::tip
The field must have a value for the record to be saved to the database.
:::