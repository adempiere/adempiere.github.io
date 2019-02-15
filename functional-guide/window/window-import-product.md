
Import Product
# Import Product


Import Products

Help
## Help

The Import Products Window is an interim table which is used when importing external data into the system.  Selecting the 'Process' button will either add or modify the appropriate records.

Window Type
### Window Type

**Maintain**


Tabs
## Tabs


Import Product
### Import Product

**Description**
 *Import Products*
**Help**
 *Before importing, Adempiere checks the Unit of Measure (default if not set), the Product Category (default if not set), the Business Partner, the Currency (defaults to accounting currency if not set), the Product Type (only Items and Services), the uniqueness of UPC, Key and uniqueness and existence of the Vendor Product No.
Adempiere tries to map to existing products, if the UPC, the Key and the Vendor Product No matches (in this sequence). If the imported record could be matched, product field values will only be overwritten, if the corresponding  Import field is explicitly defined.  Example: the Product Category will only be overwritten if explicitly set in the Import.*

```
The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.
If not selected, the user cannot create a new Record.  This is automatically disabled, if the Tab is Read Only.
```
Fields
## Fields


Import Product
### Import Product

**Description**
 *Import Item or Service*

Imported
### Imported

**Description**
 *Has this import been processed*
**Help**
 *The Imported check box indicates if this import has been processed.*

Product
### Product

**Description**
 *Product, Service, Item*
**Help**
 *Identifies an item which is either purchased or sold in this organization.*

Import Error Message
### Import Error Message

**Description**
 *Messages generated from import process*
**Help**
 *The Import Error Message displays any error messages generated during the import process.*

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

Document Note
### Document Note

**Description**
 *Additional information for a Document*
**Help**
 *The Document Note is used for recording any additional information regarding this product.*

Comment/Help
### Comment/Help

**Description**
 *Comment or Hint*
**Help**
 *The Help field contains a hint, comment or help about the use of this item.*

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

UOM Code
### UOM Code

**Description**
 *UOM EDI X12 Code*
**Help**
 *The Unit of Measure Code indicates the EDI X12 Code Data Element 355 (Unit or Basis for Measurement)*

UOM
### UOM

**Description**
 *Unit of Measure*
**Help**
 *The UOM defines a unique non monetary Unit of Measure*

Product Category Key
### Product Category Key


Product Category
### Product Category

**Description**
 *Category of a Product*
**Help**
 *Identifies the category which this product belongs to.  Product categories are used for pricing and selection.*

Product Class Key
### Product Class Key

**Description**
 *The key value for the product class*
**Help**
 *A product class is a way to organize products*

Product Class
### Product Class

**Description**
 *Class of a Product*
**Help**
 *Identifies the Class which this product belongs to*

Product Classification Key
### Product Classification Key

**Description**
 *The key value for the product classification*
**Help**
 *A product classification is a way to organize products*

Product Classification
### Product Classification

**Description**
 *Classification of a Product*
**Help**
 *Identifies the classification which this product belongs to.*

Product Group Key
### Product Group Key

**Description**
 *The key value for the product group*
**Help**
 *A product group is a way to organize products*

Product Group
### Product Group

**Description**
 *Group of a Product*
**Help**
 *Identifies the Group which this product belongs to.*

Product Type
### Product Type

**Description**
 *Type of product*
**Help**
 *The type of product also determines accounting consequences.*

Classification
### Classification

**Description**
 *Classification for grouping*
**Help**
 *The Classification can be used to optionally group products.*

Volume
### Volume

**Description**
 *Volume of a product*
**Help**
 *The Volume indicates the volume of the product in the Volume UOM of the Client*

Weight
### Weight

**Description**
 *Weight of a product*
**Help**
 *The Weight indicates the weight  of the product in the Weight UOM of the Client*

Shelf Width
### Shelf Width

**Description**
 *Shelf width required*
**Help**
 *The Shelf Width indicates the width dimension required on a shelf for a product*

Shelf Height
### Shelf Height

**Description**
 *Shelf height required*
**Help**
 *The Shelf Height indicates the height dimension required on a shelf for a product*

Shelf Depth
### Shelf Depth

**Description**
 *Shelf depth required*
**Help**
 *The Shelf Depth indicates the depth dimension required on a shelf for a product*

Units Per Pallet
### Units Per Pallet

**Description**
 *Units Per Pallet*
**Help**
 *The Units per Pallet indicates the number of units of this product which fit on a pallet.*

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

Business Partner Key
### Business Partner Key

**Description**
 *The Key of the Business Partner*

Business Partner
### Business Partner

**Description**
 *Identifies a Business Partner*
**Help**
 *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*

ISO Currency Code
### ISO Currency Code

**Description**
 *Three letter ISO 4217 Code of the Currency*
**Help**
 *For details - http://www.unece.org/trade/rec/rec09en.htm*

Currency
### Currency

**Description**
 *The Currency for this record*
**Help**
 *Indicates the Currency to be used when processing or reporting on this record*

List Price
### List Price

**Description**
 *List Price*
**Help**
 *The List Price is the official List Price in the document currency.*

PO Price
### PO Price

**Description**
 *Price based on a purchase order*
**Help**
 *The PO Price indicates the price for a product per the purchase order.*

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

Royalty Amount
### Royalty Amount

**Description**
 *(Included) Amount for copyright, etc.*

Price effective
### Price effective

**Description**
 *Effective Date of Price*
**Help**
 *The Price Effective indicates the date this price is for. This allows you to enter future prices for products which will become effective when appropriate.*

Partner Product Key
### Partner Product Key

**Description**
 *Product Key of the Business Partner*
**Help**
 *The Business Partner Product Key identifies the number used by the Business Partner for this product. It can be printed on orders and invoices when you include the Product Key in the print format.*

Partner Category
### Partner Category

**Description**
 *Product Category of the Business Partner*
**Help**
 *The Business Partner Category identifies the category used by the Business Partner for this product.*

Manufacturer
### Manufacturer

**Description**
 *Manufacturer of the Product*
**Help**
 *The manufacturer of the Product (used if different from the Business Partner / Vendor)*

Minimum Order Qty
### Minimum Order Qty

**Description**
 *Minimum order quantity in UOM*
**Help**
 *The Minimum Order Quantity indicates the smallest quantity of this product which can be ordered.*

Order Pack Qty
### Order Pack Qty

**Description**
 *Package order size in UOM (e.g. order set of 5 units)*
**Help**
 *The Order Pack Quantity indicates the number of units in each pack of this product.*

Cost per Order
### Cost per Order

**Description**
 *Fixed Cost Per Order*
**Help**
 *The Cost Per Order indicates the fixed charge levied when an order for this product is placed.*

Promised Delivery Time
### Promised Delivery Time

**Description**
 *Promised days between order and delivery*
**Help**
 *The Promised Delivery Time indicates the number of days between the order date and the date that delivery was promised.*

Import Products
### Import Products

**Description**
 *Imports products from a file into the application*
**Help**
 *Import Products will bring a file of products, in a predefined format into the application.
The Parameters are default values for null import record values, they do not overwrite any data.
If you select an existing price list and you have List, Standard, and Limit Price defined, they are directly created/updated.*

Processed
### Processed

**Description**
 *The document has been processed*
**Help**
 *The Processed checkbox indicates that a document has been processed.*
