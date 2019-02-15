
Forecast
# Forecast


The Forecast window allows to maintain the sales forecast information for an organization.

:::tip
Beta functionality is not fully tested or completed.
:::
Window Type
### Window Type

**Maintain**

:::tip
The Sales Transaction checkbox indicates if this item is a Sales Transaction.
:::

Tabs
## Tabs


Forecast
### Forecast

**Description**
 *Material Forecast*
**Help**
 *Inside the forecast window the field  \ **Price List**\  has to be defined to determine the sales goal amounts and to obtain an estimated value for the sales plan by sales representative.


The Forecast report show the Sales Plan , the goal amounts which has to be accomplished, the information to be grouped by sales representative, product, warehouse and period.


The field \ **Operational Calendar**\  and \ **Periods Definition**\ , must be defined to determine the delivery promised date for the forecast products.


The forecast lines can be captured manually entering the sales representative, product, warehouse, quantity, period or it can be generated from a simulation using the Generate forecast process.


The products and its quantities are considered by MRP when  the forecast is already  processed, ADempiere allows to have several forecast simultaneously.


If you don’t want that MRP considers a Forecast processed,  it should be deactivated.*

:::tip
The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.
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

Active
### Active

**Description**
 *The record is active in the system*
**Help**
 *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*

Default
### Default

**Description**
 *Default value*
**Help**
 *The Default Checkbox indicates if this record will be used as a default value.*

Price List
### Price List

**Description**
 *Unique identifier of a Price List*
**Help**
 *Price Lists are used to determine the pricing, margin and cost of items purchased or sold.*

Campaign
### Campaign

**Description**
 *Marketing Campaign*
**Help**
 *The Campaign defines a unique marketing program.  Projects can be associated with a pre defined Marketing Campaign.  You can then report based on a specific Campaign.*

Operational Calendar
### Operational Calendar

**Description**
 *Operational Period, allows to define the periods for the Operational Calendar*

Current Period
### Current Period

**Description**
 *Period Definition, allows to define time cycles for the Operational Calendar*

Project
### Project

**Description**
 *Financial Project*
**Help**
 *A Project allows you to track and control internal or external activities.*

Project Phase
### Project Phase

**Description**
 *Phase of a Project*

Forecast
### Forecast

**Description**
 *Material Forecast*
**Help**
 *Material Forecast*

Process Now
### Process Now

**Description**
 *Forecast process generates demands for MRP, the demand can be deactivate.*
**Help**
 *To disable a specific demand only deactivate the line desired*

Processed
### Processed

**Description**
 *The document has been processed*
**Help**
 *The Processed checkbox indicates that a document has been processed.*

Line
### Line

**Description**
 *Forecast Line*
**Help**
 *The forecast lines can be captured manually entering the sales representative, product, warehouse, quantity, period or it can be generated from a simulation using the Generate forecast process.*

:::tip
If not selected, the user cannot create a new Record.  This is automatically disabled, if the Tab is Read Only.
:::
Fields
## Fields


Sales Representative
### Sales Representative

**Description**
 *Sales Representative or Company Agent*
**Help**
 *The Sales Representative indicates the Sales Rep for this Region.  Any Sales Rep must be a valid internal user.*

Warehouse
### Warehouse

**Description**
 *Storage Warehouse and Service Point*
**Help**
 *The Warehouse identifies a unique Warehouse where products are stored or Services are provided.*

Product
### Product

**Description**
 *Product, Service, Item*
**Help**
 *Identifies an item which is either purchased or sold in this organization.*

Quantity
### Quantity

**Description**
 *Quantity*
**Help**
 *The Quantity indicates the number of a specific product or item for this document.*

Calculated Quantity
### Calculated Quantity

**Description**
 *Calculated Quantity*

Operational Period
### Operational Period

**Description**
 *Forecast Definition Periods.*

Date Promised
### Date Promised

**Description**
 *Date Order was promised*
**Help**
 *The Date Promised indicates the date, if any, that an Order was promised for.*

Active
### Active

**Description**
 *The record is active in the system*
**Help**
 *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*
