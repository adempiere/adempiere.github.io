
Workflow Cost Roll-Up
# Workflow Cost Roll-Up


This Process allow integrate Labor and Overhead Cost to a Manufacturing Workflow 

Help
## Help

This Process allow integrate Labor and Overhead Cost to a Manufacturing Workflow 

Labor Cost Operation = (Setup Time / Qty Batch Size) * Duration * Labor Rate to this Resource 
Overhead Cost Operation =  (Setup Time / Qty Batch Size) * Duration * Overhead Rate to this Resource 

Labor Cost Workflow = Sum of every the Labor Cost Operation
Overhead Cost Workflow = Sum of every the Overhead Cost Operation

Cost Workflow = Labor Cost Workflow + Overhead Cost Workflow

Parameters
## Parameters


Accounting Schema
### Accounting Schema

**Description**
 *Rules for accounting*
**Help**
 *An Accounting Schema defines the rules used in accounting such as costing method, currency and calendar*

:::tip
The field must have a value for the record to be saved to the database.
:::
Cost Type
### Cost Type

**Description**
 *Type of Cost (e.g. Current, Plan, Future)*
**Help**
 *You can define multiple cost types. A cost type selected in an Accounting Schema is used for accounting.*

:::tip
The field must have a value for the record to be saved to the database.
:::
Cost Element
### Cost Element

**Description**
 *Product Cost Element*

Organization
### Organization

**Description**
 *Organizational entity within client*
**Help**
 *An organization is a unit of your client or legal entity - examples are store, department. You can share data between organizations.*

Warehouse
### Warehouse

**Description**
 *Storage Warehouse and Service Point*
**Help**
 *The Warehouse identifies a unique Warehouse where products are stored or Services are provided.*

Resource Plant
### Resource Plant

**Description**
 *Resource Plant*
**Help**
 *Defines the Plant to calculate standard cost of Workflow manufacturing*

Product
### Product

**Description**
 *Product, Service, Item*
**Help**
 *Identifies an item which is either purchased or sold in this organization.*

Product Category
### Product Category

**Description**
 *Category of a Product*
**Help**
 *Identifies the category which this product belongs to.  Product categories are used for pricing and selection.*

Product Class
### Product Class

**Description**
 *Class of a Product*
**Help**
 *Identifies the Class which this product belongs to*

Product Group
### Product Group

**Description**
 *Group of a Product*
**Help**
 *Identifies the Group which this product belongs to.*

Product Classification
### Product Classification

**Description**
 *Classification of a Product*
**Help**
 *Identifies the classification which this product belongs to.*
