
Expense Type
# Expense Type


Maintain Expense Report Types

Window Type
### Window Type

**Maintain**

```
The Sales Transaction checkbox indicates if this item is a Sales Transaction.
```

Tabs
## Tabs


Expense Type
### Expense Type

**Description**
 *Maintain Expense Report Type*

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

UOM
### UOM

**Description**
 *Unit of Measure*
**Help**
 *The UOM defines a unique non monetary Unit of Measure*

Invoiced
### Invoiced

**Description**
 *Is this invoiced?*
**Help**
 *If selected, invoices are created*

Product Category
### Product Category

**Description**
 *Category of a Product*
**Help**
 *Identifies the category which this product belongs to.  Product categories are used for pricing and selection.*

Tax Category
### Tax Category

**Description**
 *Tax Category*
**Help**
 *The Tax Category provides a method of grouping similar taxes.  For example, Sales Tax or Value Added Tax.*

Tax Type
### Tax Type

**Description**
 *Tax Type*

Expense Product
### Expense Product

**Description**
 *Product definition of Expense Type*

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

Comment/Help
### Comment/Help

**Description**
 *Comment or Hint*
**Help**
 *The Help field contains a hint, comment or help about the use of this item.*

Document Note
### Document Note

**Description**
 *Additional information for a Document*
**Help**
 *The Document Note is used for recording any additional information regarding this product.*

UPC/EAN
### UPC/EAN

**Description**
 *Bar Code (Universal Product Code or its superset European Article Number)*
**Help**
 *Use this field to enter the bar code for the product in any of the bar code symbologies (Codabar, Code 25, Code 39, Code 93, Code 128, UPC (A), UPC (E), EAN-13, EAN-8, ITF, ITF-14, ISBN, ISSN, JAN-13, JAN-8, POSTNET and FIM, MSI/Plessey, and Pharmacode)*

SKU
### SKU

**Description**
 *Stock Keeping Unit*
**Help**
 *The SKU indicates a user defined stock keeping unit.  It may be used for an additional bar code symbols or your own schema.*

Active
### Active

**Description**
 *The record is active in the system*
**Help**
 *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*

Summary Level
### Summary Level

**Description**
 *This is a summary entity*
**Help**
 *A summary entity represents a branch in a tree rather than an end-node. Summary entities are used for reporting and do not have own values.*

Product Category
### Product Category

**Description**
 *Category of a Product*
**Help**
 *Identifies the category which this product belongs to.  Product categories are used for pricing and selection.*

Classification
### Classification

**Description**
 *Classification for grouping*
**Help**
 *The Classification can be used to optionally group products.*

Tax Category
### Tax Category

**Description**
 *Tax Category*
**Help**
 *The Tax Category provides a method of grouping similar taxes.  For example, Sales Tax or Value Added Tax.*

Revenue Recognition
### Revenue Recognition

**Description**
 *Method for recording revenue*
**Help**
 *The Revenue Recognition indicates how revenue will be recognized for this product*

UOM
### UOM

**Description**
 *Unit of Measure*
**Help**
 *The UOM defines a unique non monetary Unit of Measure*

Sales Representative
### Sales Representative

**Description**
 *Sales Representative or Company Agent*
**Help**
 *The Sales Representative indicates the Sales Rep for this Region.  Any Sales Rep must be a valid internal user.*

Product Type
### Product Type

**Description**
 *Type of product*
**Help**
 *The type of product also determines accounting consequences.*

Purchased
### Purchased

**Description**
 *Organization purchases this product*
**Help**
 *The Purchased check box indicates if this product is purchased by this organization.*

Sold
### Sold

**Description**
 *Organization sells this product*
**Help**
 *The Sold check box indicates if this product is sold by this organization.*

Discontinued
### Discontinued

**Description**
 *This product is no longer available*
**Help**
 *The Discontinued check box indicates a product that has been discontinued.*

Discontinued At
### Discontinued At

**Description**
 *Discontinued At indicates Date when product was discontinued*

Image URL
### Image URL

**Description**
 *URL of  image*
**Help**
 *URL of image; The image is not stored in the database, but retrieved at runtime. The image can be a gif, jpeg or png.*

Description URL
### Description URL

**Description**
 *URL for the description*

Price
### Price

**Description**
 *Expense Type Pricing*
**Help**
 *The Pricing Tab displays the List, Standard and Limit prices for each price list a product is contained in.*

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

Product
### Product

**Description**
 *Product, Service, Item*
**Help**
 *Identifies an item which is either purchased or sold in this organization.*

Price List Version
### Price List Version

**Description**
 *Identifies a unique instance of a Price List*
**Help**
 *Each Price List can have multiple versions.  The most common use is to indicate the dates that a Price List is valid for.*

Active
### Active

**Description**
 *The record is active in the system*
**Help**
 *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*

List Price
### List Price

**Description**
 *List Price*
**Help**
 *The List Price is the official List Price in the document currency.*

Standard Price
### Standard Price

**Description**
 *Standard Price*
**Help**
 *The Standard Price indicates the standard or normal price for a product on this price list*

Limit Price
### Limit Price

**Description**
 *Lowest price for a product*
**Help**
 *The Price Limit indicates the lowest price for a product stated in the Price List Currency.*

Accounting
### Accounting

**Description**
 *Define Accounting Parameters*
**Help**
 *The Accounting Tab defines the defaults to use when generating accounting transactions for orders and invoices which contain this Expense Type. Not all accounts apply.*

```
The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.
The Accounting Tab checkbox indicates if this window contains accounting information. To display accounting information, enable this in Tools>Preference and Role.
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

Product
### Product

**Description**
 *Product, Service, Item*
**Help**
 *Identifies an item which is either purchased or sold in this organization.*

Accounting Schema
### Accounting Schema

**Description**
 *Rules for accounting*
**Help**
 *An Accounting Schema defines the rules used in accounting such as costing method, currency and calendar*

Active
### Active

**Description**
 *The record is active in the system*
**Help**
 *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*

Product Asset
### Product Asset

**Description**
 *Account for Product Asset (Inventory)*
**Help**
 *The Product Asset Account indicates the account used for valuing this a product in inventory.*

Product Expense
### Product Expense

**Description**
 *Account for Product Expense*
**Help**
 *The Product Expense Account indicates the account used to record expenses associated with this product.*

Product COGS
### Product COGS

**Description**
 *Account for Cost of Goods Sold*
**Help**
 *The Product COGS Account indicates the account used when recording costs associated with this product.*

Purchase Price Variance
### Purchase Price Variance

**Description**
 *Difference between Standard Cost and Purchase Price (PPV)*
**Help**
 *The Purchase Price Variance is used in Standard Costing. It reflects the difference between the Standard Cost and the Purchase Order Price.*

Invoice Price Variance
### Invoice Price Variance

**Description**
 *Difference between Costs and Invoice Price (IPV)*
**Help**
 *The Invoice Price Variance is used reflects the difference between the current Costs and the Invoice Price.*

Trade Discount Received
### Trade Discount Received

**Description**
 *Trade Discount Receivable Account*
**Help**
 *The Trade Discount Receivables Account indicates the account for received trade discounts in vendor invoices*

Trade Discount Granted
### Trade Discount Granted

**Description**
 *Trade Discount Granted Account*
**Help**
 *The Trade Discount Granted Account indicates the account for granted trade discount in sales invoices*

Product Revenue
### Product Revenue

**Description**
 *Account for Product Revenue (Sales Account)*
**Help**
 *The Product Revenue Account indicates the account used for recording sales revenue for this product.*
