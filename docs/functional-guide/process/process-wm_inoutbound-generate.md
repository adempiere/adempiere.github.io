
Generare Outbound Order
# Generare Outbound Order


This process allows to generate a new document as the result of gathering Sales Orders, Manufacture Orders, Distribution Orders based on several criteria such as :

Help
## Help

Warehouse, Order, Document Type, Promised Date range, Ordered Dates, Business Partner, Country, Zip Code, Product and Shipper, these parameters can be configured leveraging the Smart Browse artifact.

Thus, it is required to previously define those parameters to be used in orther to determine wich products are to be included in the Picking Orders, these paraneters are:

*Area Type
*Section type
*Overwrite Delivery Rule
*Generate Picking List
*Print Picking List
*Stand-by Location
*Document Status for the Picking Order

Parameters
## Parameters


Order Reference
### Order Reference

**Description**
 *Transaction Reference Number (Sales Order, Purchase Order) of your Business Partner*
**Help**
 *The business partner order reference is the order reference for this specific transaction; Often Purchase Order numbers are given to print on Invoices for easier reference.  A standard number can be defined in the Business Partner (Customer) window.*

Outbound Locator
### Outbound Locator

**Description**
 *Warehouse Locator*
**Help**
 *The Locator indicates where in a Warehouse a product is located.*

:::tip
The field must have a value for the record to be saved to the database.
:::
Delivery Rule
### Delivery Rule

**Description**
 *Defines the timing of Delivery*
**Help**
 *The Delivery Rule indicates when an order should be delivered. For example should the order be delivered when the entire order is complete, when a line is complete or as the products become available.*

:::tip
The field must have a value for the record to be saved to the database.
:::
Document Type
### Document Type

**Description**
 *Document type or rules*
**Help**
 *The Document Type determines document sequence and processing rules*

Document Action
### Document Action

**Description**
 *The targeted status of the document*
**Help**
 *You find the current status in the Document Status field. The options are listed in a popup*

Ship Date
### Ship Date

**Description**
 *Shipment Date/Time*
**Help**
 *Actual Date/Time of Shipment (pick up)*

:::tip
The field must have a value for the record to be saved to the database.
:::
Pick Date
### Pick Date

**Description**
 *Date/Time when picked for Shipment*

:::tip
The field must have a value for the record to be saved to the database.
:::
Priority
### Priority

**Description**
 *Priority of a document*
**Help**
 *The Priority indicates the importance (high, medium, low) of this document*

Delivery Via
### Delivery Via

**Description**
 *How the order will be delivered*
**Help**
 *The Delivery Via indicates how the products should be delivered. For example, will the order be picked up or shipped.*

:::tip
The field must have a value for the record to be saved to the database.
:::
Shipper
### Shipper

**Description**
 *Method or manner of product delivery*
**Help**
 *The Shipper indicates the method of delivering product*

Freight Cost Rule
### Freight Cost Rule

**Description**
 *Method for charging Freight*
**Help**
 *The Freight Cost Rule indicates the method used when charging for freight.*

Freight Category
### Freight Category

**Description**
 *Category of the Freight*
**Help**
 *Freight Categories are used to calculate the Freight for the Shipper selected*
